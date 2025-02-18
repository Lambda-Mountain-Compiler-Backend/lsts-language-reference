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

### `deep-hash : Tuple<x,y> -> USize`

### `.into : (Tuple<x,y>, Type<String>) -> String`

```
type Tuple<x,y,z> = Tuple { first: x, second: y, third: z };
```

### `== : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `!= : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `< : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `<= : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `> : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `>= : (Tuple<x,y,z>, Tuple<x,y,z>) -> Bool`

### `deep-hash : Tuple<x,y,z> -> USize`

### `.into : (Tuple<x,y,z>, Type<String>) -> String`

```
type Tuple<w,x,y,z> = Tuple { first: w, second: x, third: y, fourth: z };
```

etc.



