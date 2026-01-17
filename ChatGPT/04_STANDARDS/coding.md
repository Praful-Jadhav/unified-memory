# Coding Standards

## Core Principles

1.  **Readability**: Code is read more often than written. Write for the next developer (your future self).
2.  **Modularity**: Functions should do one thing well.
3.  **Robustness**: Handle errors gracefully; never fail silently.

## Style Guide

- **Naming**: Descriptive and consistent (e.g., `calculateTotal` vs `calc`).
- **Comments**: Explain _why_, not _what_. Code tells the _what_.
- **Formatting**: Use automated formatters (Prettier, Black, etc.) to eliminate style debates.

## Quality Bar

- **No Magic Numbers**: Use named constants.
- **No Global State**: Unless explicitly managed and documented.
- **Testable**: Code must be structured to allow automated testing.
