<link rel="stylesheet" type="text/css" href="styles.css">

### `hash : Sized<size> -> Bool`

The hash is not a cryptographic hash.

### `is : (Sized<size>,Sized<size>) -> Bool`

`is` checks for binary equality of two memory regions.

### `mem-is-non-zero : Sized<size> -> Bool`

`mem-is-non-zero` checks if a memory region is zeroed out.
