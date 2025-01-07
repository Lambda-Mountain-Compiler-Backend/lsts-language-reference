
### Syntax Reference

### Function Application

```
f(a, b)
```

### Array Indexing, Byte Indexing, Item Indexing

```
arr[i]       # Get one item
arr[i:j]     # Get slice from i until j
arr[:j]      # Get slice from start until j
arr[i:]      # Get slice from i until end
arr[i:-2]    # Get slice from i until 2 items before end
```

### Struct Constructor

```
A { 1, 2, 3 }
```

### Sequenced Expressions

```
do-this();     # The semi-colon separates expressions into an ordered sequence
before-this();
```

### Let

```
let x = 5;
```

### Variable Assignment

```
x = 6;
```

### If

```
if x then y;
if x then y else z;
if x { y };
if x { y } else { z };
```

### While

```
while condition { do-a-thing; };
```

### For

```
for x in y { do-a-thing; };
```

### Match

```
match a {
   lhs => rhs;
   "abc" => "def";           # match a string value "abc"
   "ab".. rest => "c";       # match a string starting with "ab"
   [1.. 2..] => 3            # this lhs will match only a two element sequence [1,2]
   [1.. 2.. _] => 3          # this lhs will match any sequence starting with 1 and 2
   A { binding=key:5 } => 4; # this will match a struct A with field "key" having value 5
};
```

### Function Definition

```
let f(a: A, b: B): C = c(a, b);
```

### Method Definition

```
let .f(this: A, b: B): C = c(this, b);
```

### Type Definition

```
type AB = CaseA { x: U64 } | CaseB { y: U64 };
```
