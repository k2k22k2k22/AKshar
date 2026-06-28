# Examples

The `examples/` directory contains sample AKshar programs that illustrate language features and serve as reference implementations for testing and documentation.

## What belongs here
- Small, self‑contained source files demonstrating specific language constructs (e.g., variable declarations, control flow, functions, types)
- Complete example programs that can be compiled with the AKshar compiler to produce executable output
- Annotated source showing intended usage patterns for the language

## What does **not** belong here
- Test code (unit or integration tests belong in `tests/`)
- Build scripts or tooling (those belong in `tools/`)
- Generated artifacts (compiled binaries, object files, etc.)

## Purpose
Example programs help developers understand how to write AKshar code, provide concrete cases for documentation, and serve as regression checks when the compiler evolves. They should be kept minimal and focused on illustrating one concept per file where possible.
