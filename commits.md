# What are the GitHub commit types?

While GitHub doesn't have standardized GitHub commit types, the common convention is to categorize commits, title them specifically, and add a description on *why* and *how* changes were made.

- **feat**: New feature.
- **fix**: Bug fix or patch.
- **docs**: Documentation changes.
- **style**: Formatting changes (doesn't affect code).
- **refactor**: Code restructuring (doesn't bug fix or add a feature).
- **perf**: Changes that improve performance.
- **test**: Missing tests or correcting existing tests.
- **chore**: Maintenance, updates, or dependency bumps.

```text
type: imperative short description
[optional body of why and how]
[optional footer for references and breaking changes]
```

A *breaking change* is a modification to a software project, codebase, or API that breaks backward compatibility. So they are definitely note-worthy.

<br>



# The 50/72 Rule

Formatting standards ensure commits are easy to scan: 

- **Subject line** (50 characters): Concise so it fits easily in terminal logs and pull request titles.
- **Imperative**: Write titles as commands.
- **Body line** (72 characters): Wrap detailed explanation so it renders perfectly. 