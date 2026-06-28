# Documentation

This directory is the central repository for all architectural and developer documentation related to **AKshar**, the C compiler project.

## What belongs here
- Design overviews (compiler pipeline, module responsibilities)
- Language specification and syntax/semantics notes
- Architecture diagrams, data flow charts, and decision records
- Development guides (contributing, coding standards, build process)
- Project roadmaps and milestone outlines

## What does **not** belong here
- Source code files (C source, headers, generated code)
- Test suites, example programs, or tooling scripts
- Binary artefacts or build output

## Relationship to the project
Documentation lives alongside the source repository to ensure it evolves with the code. Each major component (lexer, parser, optimizer, code generator, etc.) should have its own markdown file or sub‑directory under `docs/` documenting its purpose, interface, and design rationale.

The documentation is expected to be version‑controlled, reviewed, and updated as part of the development workflow.
