<link rel="stylesheet" type="text/css" href="styles.css">

### `mk-vector : (Type<t>, capacity: U64) -> Vector<t>`

### `.push : (Into<&Vector<t>>, t) -> Nil`

### `.pop : Into<&Vector<t>> -> t`

### `.into : (Vector<t>, Type<List<t>>) -> List<t>`

### `[] : (Vector<t>, U64) -> t`

### `set[] : (Vector<t>, U64, t) -> Nil`

### `+ : (Vector<t>, Vector<t>) -> Vector<t>`

### `.sort : Vector<t> -> Vector<t>`

### `.unique : Vector<t> -> Vector<t>`

### `.into : (Vector<t>, Type<String>) -> String`

### `.next : &Vector<t> -> Maybe<t>`
