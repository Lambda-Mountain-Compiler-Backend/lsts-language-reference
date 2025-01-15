<link rel="stylesheet" type="text/css" href="styles.css">

```
type S = SNil
       | SAtom { CString }
       | SCons { S[], S[] }
       | SPointer { ?[] }
```

### `print : S -> Nil`

### `to-string : S -> String`

### `== : (S, S) -> Bool`

### `!= : (S, S) -> Bool`

### `< : (S, S) -> Bool`

### `<= : (S, S) -> Bool`

### `> : (S, S) -> Bool`

### `>= : (S, S) -> Bool`
