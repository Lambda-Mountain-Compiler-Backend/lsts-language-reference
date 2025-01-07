
### `[] : (Array<base-type,?>, U64) -> base-type`

### `set[] : (Array<base-type,?>, U64, base-type) -> base-type`

### `+ : (Array<base-type,?>, U64) -> Array<base-type,?>`

Pointer arithmetic.

### `+ : (Array<base-type,?>, I64) -> Array<base-type,?>`

Pointer arithmetic.

### `== : (Array<base-type,?>, Array<base-type,?>) -> Bool`

Pointers are have linear addresses.

### `!= : (Array<base-type,?>, Array<base-type,?>) -> Bool`

Pointers are have linear addresses.

### `< : (Array<base-type,?>, Array<base-type,?>) -> Bool`

Pointers are have linear addresses.

### `<= : (Array<base-type,?>, Array<base-type,?>) -> Bool`

Pointers are have linear addresses.

### `> : (Array<base-type,?>, Array<base-type,?>) -> Bool`

Pointers are have linear addresses.

### `>= : (Array<base-type,?>, Array<base-type,?>) -> Bool`

Pointers are have linear addresses.

### `close : base-type -> Array<base-type,?>`

`close` tries to seal a value into a new indirect memory region.

### `open : Array<base-type,?> -> base-type`

`open` tries to open a value from an indirect memory region.

### `open : base-type -> base-type`

If a value is already directly accessible, then `open` is a noop.
