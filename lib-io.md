
```
type IO::File;

type phi FileState = Open | Closed;

let phi(left: FileState::Open, right: FileState::Open): FileState::Open;
let phi(left: FileState::Closed, right: FileState::Closed): FileState::Closed;
```

### `fopen : (path: String, mode: String) -> IO::File+Phi<FileState::Open>`

Minimal type wrapper around C `fopen` function to check for resource leaks.

### `fclose : (fp: IO::File+Phi<FileState::Open,FileState::Closed>) -> U32`

Minimal type wrapper around C `fclose` function to check for resource leaks.
