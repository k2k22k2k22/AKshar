# Developer Tools

The `tools/` directory holds scripts and utilities that assist developers in building, maintaining, and interacting with the AKshar compiler.

## What belongs here
- Build scripts (e.g., `build.sh`, `configure`, `Makefile` helpers)
- Helper utilities for code generation, benchmark runs, or documentation generation
- Linting or formatting wrappers specific to the project
- Scripts for cleaning generated artefacts (`clean.sh`)
- Automation tools for CI integration (e.g., scripts invoked by GitHub Actions)

## What does **not** belong here
- Source code of the compiler components (those belong in `src/` when introduced)
- Test cases (they belong in `tests/`)
- Example programs (they belong in `examples/`)
- Binary artefacts or compiled output

## Relationship to the build system
These tools are intended to be invoked by the project's build system or manually by developers. They should be documented, version‑controlled, and kept platform‑agnostic where possible.
