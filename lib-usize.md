<link rel="stylesheet" type="text/css" href="styles.css">

`USize` is a variable size unsigned integer that will be as big as a word.

```
ifdef SYSTEM-32-BIT (
   type USize = U32;
);

ifdef SYSTEM-64-BIT (
   type USize = U64;
);
```
