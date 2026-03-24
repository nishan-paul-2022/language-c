# C Language: From the Core

This repository is a large C practice collection organized by topic. It is designed for step-by-step learning, revision, and hands-on problem solving.

## What You Will Find

- 390+ C programs (currently 393 `.c` files)
- Topic-wise folders from basics to dynamic memory and file handling
- Small focused examples for concepts, logic building, and algorithm practice
- Supporting notes in the [c-programs-analysis.md](c-programs-analysis.md)

## Repository Structure

Programs are grouped by concept:

- `01-basics-and-problems`
- `02-input-output`
- `03-characters`
- `04-conversions`
- `05-arrays`
- `06-matrices`
- `07-pointers`
- `08-strings`
- `09-structures`
- `10-functions-and-preprocessor`
- `11-recursion`
- `12-number-theory`
- `13-math`
- `14-patterns`
- `15-dynamic-memory`
- `16-file-io`
- `17-misc`

## How to Compile and Run

### Option 1: VS Code

1. Open this repository in VS Code.
2. Open any `.c` file.
3. Use Run Without Debugging.

### Option 2: Terminal (gcc)

```bash
gcc -Wall -Wextra -std=c11 -o program path/to/file.c
./program
```

Example:

```bash
gcc -Wall -Wextra -std=c11 -o array_linear_search 05-arrays/array_linear_search.c
./array_linear_search
```

## License

This repository is licensed under the terms in [LICENSE](LICENSE).
