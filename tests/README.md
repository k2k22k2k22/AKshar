# Testing

The `tests/` directory holds all automated tests that verify the correctness of the AKshar compiler.

## What belongs here
- Unit tests for individual components (lexer, parser, optimizer, code generator)
- Integration tests that compile sample programs and compare the generated output against expected results
- End‑to‑end tests that exercise the full compilation pipeline
- Test utilities (fixtures, mock data, harness scripts) used by the test suite

## What does **not** belong here
- Production source code (compiler implementation)
- Example programs (those belong in `examples/`)
- Build scripts unrelated to testing (those belong in `tools/`)

## Testing philosophy
The compiler will be validated through a layered testing approach:
1. **Unit tests** isolate each module to catch regressions early.
2. **Integration tests** ensure modules work together correctly.
3. **System tests** compile real AKshar programs to guarantee end‑to‑end functionality.

Tests are expected to be written using the project's chosen test framework (e.g., CTest, Unity, or a language‑specific harness) and should be runnable via a single command such as `make test` once the build system is in place.
