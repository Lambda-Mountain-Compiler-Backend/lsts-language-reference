
### `[] : (base-type[], U64) -> base-type`

### `set[] : (base-type[], U64, base-type) -> base-type`

### `+ : (base-type[], U64) -> base-type[]`

Pointer arithmetic.

### `+ : (base-type[], I64) -> base-type[]`

Pointer arithmetic.

### `== : (base-type[], base-type[]) -> Bool`

Pointers are have linear addresses.

### `!= : (base-type[], base-type[]) -> Bool`

Pointers are have linear addresses.

### `< : (base-type[], base-type[]) -> Bool`

Pointers are have linear addresses.

### `<= : (base-type[], base-type[]) -> Bool`

Pointers are have linear addresses.

### `> : (base-type[], base-type[]) -> Bool`

Pointers are have linear addresses.

### `>= : (base-type[], base-type[]) -> Bool`

Pointers are have linear addresses.

### `close : base-type -> base-type[]`

`close` tries to seal a value into a new indirect memory region.

### `open : base-type[] -> base-type`

`open` tries to open a value from an indirect memory region.

### `open : base-type -> base-type`

If a value is already directly accessible, then `open` is a noop.

### `& : LocalVariable+base-type -> base-type[]`

Local variables have logical addresses that can be referenced with `&`.

### `& :GlobalVariable+base-type -> base-type[]`

Global variables have logical addresses that can be referenced with `&`.
