
### Syntax Reference

### Function Application

```
f(a, b)
```

### Sequenced Expressions

```
do-this();
before-this();
```

### Let

```
let x = 5;
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
   lhs1 => rhs1;
   lhs2 => rhs2;
   "abc" => "def";           # match a string value "abc"
   "ab".. rest => "c";       # match a string starting with "ab"
   [1.. 2..] => 3            # this lhs will match only a two element sequence [1,2]
   [1.. 2.. _] => 3          # this lhs will match any sequence starting with 1 and 2
   A { binding=key:5 } => 4; # this will match a struct A with field "key" having value 5
};
```
