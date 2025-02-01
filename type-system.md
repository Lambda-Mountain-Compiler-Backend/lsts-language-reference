<link rel="stylesheet" type="text/css" href="styles.css">

### Lambda Calculus

Lambda Calculus just has variables, functions, and function applications.
It is a "dynamic" language without static types.

```
λx. x y z
```

### Simply Typed Lambda Calculus

Types can help distinguish terms and their intended purpose.
Each type is a simple name or an arrow.

```
1 : Integer
f : Integer -> Integer
```

### System F

System F adds the ability for objects to be parameterized with quantified type variables.
In LM type variables are represented with lowercase identifiers.

```
some : a -> Option<a>
```

### System F<:

System F<: adds the ability for objects to become subtypes (<:) of a hierarchical type system.

In standard notation this might look something like this:

```
type X implies Y;

(x : X) <: Y    # yes
```

In plural notation the subtyping relations can often be expanded to clarify a bit more of what is going on.

```
(x : X+Y) <: Y  # yes
```

### System F<: with Specialization

Specialization adds the ability to pun (overload) functions onto the same identifier.
Then, when applied, punned functions are "narrowed as necessary" to decide which function to apply.

<img src="https://github.com/andrew-johnson-4/lsts-language-reference/blob/main/abstraction.png?raw=true">

$$application \quad \frac{\Gamma \vdash f:(A \to B) + (C \to D) + (X \to Y) \quad \Gamma \vdash x:A + X \quad f(x)}{\Gamma \vdash f(x):B + Y}$$

### Logical Propositions

Nominal Types can be associated with logical properties.
When a Type carries a proposition, in order to soundly fulfill that proposition two things need to be independently proven:
1) The term carries the proposition's name (for example `List::Sorted`)
2) The name is only given to terms that satisfy the proposition's semantic conditions (`List::Sorted` lists are sorted)

Condition 1 is already working in the type system, however condition 2 will require some significant work.
This feature is a prerequisite for fully certified builds.

### Phi Types

Many novel type systems can be expressed as Phi Types.
The term "Phi Type" comes from the more widely recognized Phi Functions in Single Static Assignment form.
A Phi Function is used to merge variables coming from two separate parent code paths.
A Phi Type is similarly used to merge types coming from two separate parent code paths.

Example:

$$\frac{if \quad condition \quad then \quad truecase \quad else \quad falsecase}{logically \quad merge \quad truecase \quad and \quad falsecase}$$

becomes

$$\frac{if \quad condition \quad then \quad truecase \quad else \quad falsecase}{φ(truecase,falsecase)}$$

so only a new phi function needs to be defined.

Phi types can also have state transitions decorated onto the inference graph.
For example the `fclose` function will cause a state transition from `FileState::Open` to `FileState::Closed`.
