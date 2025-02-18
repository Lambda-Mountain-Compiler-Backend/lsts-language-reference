<link rel="stylesheet" type="text/css" href="styles.css">

### `set[] : (&Hashtable<k,v>, k, v) -> Nil`

### `.bind : (Hashtable<k,v>, k, v) -> Hashtable<k,v>`

### `.lookup : (&Hashtable<k,v>, k, default: v) -> v`

### `.has : (&Hashtable<k,v>, k) -> Bool`

### `.into : (&Hashtable<k,v>, Type<String>) -> String`

`HashtableIs` is an alternative hashtable type that uses shallow hashes and shallow equality as opposed to deep hashes and deep equality.

### `set[] : (&HashtableIs<k,v>, k, v) -> Nil`

### `.bind : (HashtableIs<k,v>, k, v) -> HashtableIs<k,v>`

### `.lookup : (&HashtableIs<k,v>, k, default: v) -> v`

### `.has : (&HashtableIs<k,v>, k) -> Bool`

### `.into : (&HashtableIs<k,v>, Type<String>) -> String`
