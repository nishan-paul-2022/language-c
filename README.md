# C Language: From the Core

This repository is a large C practice collection organized by topic. It is designed for step-by-step learning, revision, and hands-on problem solving.

## What You Will Find

- 390+ C programs (currently 393 `.c` files)
- Topic-wise folders from basics to dynamic memory and file handling
- Small focused examples for concepts, logic building, and algorithm practice
- Supporting notes in the [docs/c-programs-analysis.md](docs/c-programs-analysis.md)

## Repository Structure

Programs are grouped by concept:

- `c-topic-basics-and-problems`
- `c-topic-input-output`
- `c-topic-characters`
- `c-topic-conversions`
- `c-topic-arrays`
- `c-topic-matrices`
- `c-topic-pointers`
- `c-topic-strings`
- `c-topic-structures`
- `c-topic-functions-and-preprocessor`
- `c-topic-recursion`
- `c-topic-number-theory`
- `c-topic-math`
- `c-topic-patterns`
- `c-topic-dynamic-memory`
- `c-topic-file-io`
- `c-topic-misc`

Additional folders:

- `docs` for analysis and documentation
- `files` for sample data used by file I/O programs

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
gcc -Wall -Wextra -std=c11 -o array_linear_search c-topic-arrays/array_linear_search.c
./array_linear_search
```

## License

This repository is licensed under the terms in [LICENSE](LICENSE).
