<link rel="stylesheet" type="text/css" href="styles.css">

* [Syntax Cheatsheet](https://andrew-johnson-4.github.io/lsts-language-reference/lsts-syntax)
* [Type System Overview](https://andrew-johnson-4.github.io/lsts-language-reference/type-system)
* [Reserved Words and Reserved Types](https://andrew-johnson-4.github.io/lsts-language-reference/reserved-words)

### Primitive Types
  
| Size      | Name                                                                          |        | Size   | Name |
| --------- | ----------------------------------------------------------------------------- | ------ | ------ | ---- |
| ?         | [Sized](https://andrew-johnson-4.github.io/lsts-language-reference/lib-sized) | &nbsp; | 8      | [CString](https://andrew-johnson-4.github.io/lsts-language-reference/lib-cstring) |
| >= 1 bit  | [Bool](https://andrew-johnson-4.github.io/lsts-language-reference/lib-bool)   | &nbsp; | ?      | [String](https://andrew-johnson-4.github.io/lsts-language-reference/lib-string) |
| 1         | [U8](https://andrew-johnson-4.github.io/lsts-language-reference/lib-u8)       | &nbsp; | ?      | [S](https://andrew-johnson-4.github.io/lsts-language-reference/lib-s-expression) |
| 1         | [I8](https://andrew-johnson-4.github.io/lsts-language-reference/lib-i8)       | &nbsp; | ?      | [Tuple](https://andrew-johnson-4.github.io/lsts-language-reference/lib-tuple) |
| 2         | [U16](https://andrew-johnson-4.github.io/lsts-language-reference/lib-u16)     | &nbsp; | ?      | [List](https://andrew-johnson-4.github.io/lsts-language-reference/lib-list) |
| 2         | [I16](https://andrew-johnson-4.github.io/lsts-language-reference/lib-i16)     | &nbsp; | ?      | [Vector](https://andrew-johnson-4.github.io/lsts-language-reference/lib-vector) |
| 4         | [U32](https://andrew-johnson-4.github.io/lsts-language-reference/lib-u32)     | &nbsp; | ?      | [Hashtable](https://andrew-johnson-4.github.io/lsts-language-reference/lib-hashtable) |
| 4         | [I32](https://andrew-johnson-4.github.io/lsts-language-reference/lib-i32)     | &nbsp; | ?      | [Array](https://andrew-johnson-4.github.io/lsts-language-reference/lib-array) |
| 4         | [F32](https://andrew-johnson-4.github.io/lsts-language-reference/lib-f32)     | &nbsp; | ?      | [Regex](https://andrew-johnson-4.github.io/lsts-language-reference/lib-regex) |
| 8         | [U64](https://andrew-johnson-4.github.io/lsts-language-reference/lib-u64)     | &nbsp; | ?      | [Maybe](https://andrew-johnson-4.github.io/lsts-language-reference/lib-maybe) |
| 8         | [I64](https://andrew-johnson-4.github.io/lsts-language-reference/lib-i64)     | &nbsp; | &nbsp; | &nbsp; |
| 8         | [F64](https://andrew-johnson-4.github.io/lsts-language-reference/lib-f64)     | &nbsp; | &nbsp; | &nbsp; |
| word size | [USize](https://andrew-johnson-4.github.io/lsts-language-reference/lib-usize) | &nbsp; | &nbsp; | &nbsp; |

### Library Modules

* [IO](https://andrew-johnson-4.github.io/lsts-language-reference/lib-io)

### Github Links

* [LSTS (the programming language)](https://github.com/andrew-johnson-4/LSTS?tab=readme-ov-file#much-like-c)
* [LM (the compiler infrastructure)](https://github.com/andrew-johnson-4/lambda-mountain#lambda-mountain)
