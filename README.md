<link rel="stylesheet" type="text/css" href="styles.css">

* [Syntax Cheatsheet](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lsts-syntax)
* [Type System Overview](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/type-system)
* [Reserved Words and Reserved Types](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/reserved-words)

### Primitive Types
  
| Size      | Name                                                                          |        | Size   | Name |
| --------- | ----------------------------------------------------------------------------- | ------ | ------ | ---- |
| ?         | [Sized](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-sized) | &nbsp; | 8      | [CString](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-cstring) |
| >= 1 bit  | [Bool](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-bool)   | &nbsp; | ?      | [String](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-string) |
| 1         | [U8](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-u8)       | &nbsp; | ?      | [S](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-s-expression) |
| 1         | [I8](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-i8)       | &nbsp; | ?      | [Tuple](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-tuple) |
| 2         | [U16](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-u16)     | &nbsp; | ?      | [List](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-list) |
| 2         | [I16](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-i16)     | &nbsp; | ?      | [Vector](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-vector) |
| 4         | [U32](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-u32)     | &nbsp; | ?      | [Hashtable](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-hashtable) |
| 4         | [I32](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-i32)     | &nbsp; | ?      | [Array](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-array) |
| 4         | [F32](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-f32)     | &nbsp; | ?      | [Regex](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-regex) |
| 8         | [U64](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-u64)     | &nbsp; | ?      | [Maybe](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-maybe) |
| 8         | [I64](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-i64)     | &nbsp; | &nbsp; | [Arrow](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-arrow) |
| 8         | [F64](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-f64)     | &nbsp; | &nbsp; | &nbsp; |
| word size | [USize](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-usize) | &nbsp; | &nbsp; | &nbsp; |

### Library Modules

* [IO](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/lib-io)

### Github Links

* [LSTS (the programming language)](https://github.com/lambda-mountain-compiler-backend/LSTS?tab=readme-ov-file#much-like-c)
* [LM (the compiler infrastructure)](https://github.com/lambda-mountain-compiler-backend/lambda-mountain#lambda-mountain)
