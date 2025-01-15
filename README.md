<link rel="stylesheet" type="text/css" href="styles.css">

# LSTS Language Reference

[LSTS Syntax](https://andrew-johnson-4.github.io/lsts-language-reference/lsts-syntax)

### Primitive Types
  
| Size     | Name                                                                          |    | Size   | Name |
| -------- | ----------------------------------------------------------------------------- | -- | ------ | ---- |
| ?        | [Sized](https://andrew-johnson-4.github.io/lsts-language-reference/lib-sized) |    | 8      | [CString](https://andrew-johnson-4.github.io/lsts-language-reference/lib-cstring) |
| >= 1 bit | [Bool](https://andrew-johnson-4.github.io/lsts-language-reference/lib-bool)   |    | ?      | [String](https://andrew-johnson-4.github.io/lsts-language-reference/lib-string) |
| 1        | [U8](https://andrew-johnson-4.github.io/lsts-language-reference/lib-u8)       |    | ?      | [S](https://andrew-johnson-4.github.io/lsts-language-reference/lib-s-expression) |
| 1        | [I8](https://andrew-johnson-4.github.io/lsts-language-reference/lib-i8)       |    | ?      | [Tuple](https://andrew-johnson-4.github.io/lsts-language-reference/lib-tuple) |
| 2        | [U16](https://andrew-johnson-4.github.io/lsts-language-reference/lib-u16)     |    | ?      | [List](https://andrew-johnson-4.github.io/lsts-language-reference/lib-list) |
| 2        | [I16](https://andrew-johnson-4.github.io/lsts-language-reference/lib-i16)     |    | ?      | [Vector](https://andrew-johnson-4.github.io/lsts-language-reference/lib-vector) |
| 4        | [U32](https://andrew-johnson-4.github.io/lsts-language-reference/lib-u32)     |    | ?      | [Hashtable](https://andrew-johnson-4.github.io/lsts-language-reference/lib-hashtable) |
| 4        | [I32](https://andrew-johnson-4.github.io/lsts-language-reference/lib-i32)     |    | ?      | [Array](https://andrew-johnson-4.github.io/lsts-language-reference/lib-array) |
| 4        | [F32](https://andrew-johnson-4.github.io/lsts-language-reference/lib-f32)     |    | ?      | [Regex](https://andrew-johnson-4.github.io/lsts-language-reference/lib-regex) |
| 8        | [U64](https://andrew-johnson-4.github.io/lsts-language-reference/lib-u64)     |    | &nbsp; | &nbsp; |
| 8        | [I64](https://andrew-johnson-4.github.io/lsts-language-reference/lib-i64)     |    | &nbsp; | &nbsp; |
| 8        | [F64](https://andrew-johnson-4.github.io/lsts-language-reference/lib-f64)     |    | &nbsp; | &nbsp; |

### Library Modules

* [IO](https://andrew-johnson-4.github.io/lsts-language-reference/lib-io)


