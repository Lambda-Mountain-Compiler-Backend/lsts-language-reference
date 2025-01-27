<link rel="stylesheet" type="text/css" href="styles.css">

```
type Maybe<x> = Some { contents:x } | None;
zero Maybe<x> = None;
```

### `.get-or(m: Maybe<x>, default: x) -> x`
