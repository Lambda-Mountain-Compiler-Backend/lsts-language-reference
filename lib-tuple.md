<link rel="stylesheet" type="text/css" href="styles.css">

```
type Tuple<x,y> = Tuple { first: x, second: y };
```

### `== : (Tuple<x,y>, Tuple<x,y>) -> Bool`

### `!= : (Tuple<x,y>, Tuple<x,y>) -> Bool`

### `< : (Tuple<x,y>, Tuple<x,y>) -> Bool`

### `<= : (Tuple<x,y>, Tuple<x,y>) -> Bool`

### `> : (Tuple<x,y>, Tuple<x,y>) -> Bool`

### `>= : (Tuple<x,y>, Tuple<x,y>) -> Bool`

### `deep-hash : Tuple<x,y> -> U64`

### `print : Tuple<x,y> -> Nil`

### `.to-string : Tuple<x,y> -> String`

```
type Tuple<x,y,z> = Tuple { first: x, second: y, third: z };
```

### `== : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `!= : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `< : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `<= : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `> : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `>= : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `deep-hash : Tuple<x,y,z> -> U64`

### `print : Tuple<x,y,z> -> Nil`

### `.to-string : Tuple<x,y,z> -> String`

```
type Tuple<w,x,y,z> = Tuple { first: w, second: x, third: y, fourth: z };
```

etc.



