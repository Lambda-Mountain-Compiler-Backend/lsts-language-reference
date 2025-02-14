<link rel="stylesheet" type="text/css" href="styles.css">

```
type S = SNil
       | SAtom { CString }
       | SCons { S[], S[] }
       | SPointer { ?[] }
```

### `.into : (S, Type<String>) -> String`

### `== : (S, S) -> Bool`

### `!= : (S, S) -> Bool`

### `< : (S, S) -> Bool`

### `<= : (S, S) -> Bool`

### `> : (S, S) -> Bool`

### `>= : (S, S) -> Bool`
