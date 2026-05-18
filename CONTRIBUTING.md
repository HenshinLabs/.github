# Contributing to HenshinLabs

Thank you for your interest in contributing to HenshinLabs projects. This document outlines the process and standards we expect from contributors.

## Getting Started

1. **Fork the repository** you want to contribute to
2. **Clone your fork** locally
3. **Create a feature branch** from `main`
4. **Make your changes** following our code standards
5. **Submit a pull request**

## Development Workflow

### Branch Naming

Use descriptive branch names:

```
feature/add-voice-recognition
fix/memory-leak-inference
docs/update-api-reference
refactor/cleanup-model-loader
```

### Commit Messages

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): description

feat(voice): add real-time voice activity detection
fix(model): resolve memory leak during inference
docs(readme): update installation instructions
refactor(ui): simplify state management
test(core): add unit tests for tokenizer
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`

### Pull Request Process

1. **Update documentation** if your change affects public APIs or user-facing behavior
2. **Add tests** for new functionality
3. **Ensure all existing tests pass** before submitting
4. **Write a clear PR description** explaining what changed and why
5. **Link related issues** using GitHub keywords (e.g., `Closes #42`)

### PR Description Template

```markdown
## What

Brief description of the change.

## Why

Motivation for the change.

## How

Technical approach and key decisions.

## Testing

How the change was tested.

## Checklist

- [ ] Code follows project style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] Tests added/updated
- [ ] No breaking changes (or clearly documented)
```

## Code Standards

### General

- Write clear, readable code with meaningful variable names
- Keep functions focused on a single responsibility
- Avoid premature optimization — clarity over cleverness
- Document complex algorithms and non-obvious decisions

### Kotlin / Android

- Follow [Kotlin coding conventions](https://kotlinlang.org/docs/coding-conventions.html)
- Use coroutines for async operations
- Prefer composition over inheritance
- Use Jetpack Compose for new UI code

### Python

- Follow [PEP 8](https://peps.python.org/pep-0008/)
- Use type hints for function signatures
- Write docstrings for public functions and classes
- Use `pytest` for testing

### Documentation

- Use clear, concise language
- Include code examples where helpful
- Keep README files up to date with current setup instructions

## Reporting Issues

### Bug Reports

Include:

- **Environment**: OS, runtime version, device (if mobile)
- **Steps to reproduce**: minimal, exact steps
- **Expected behavior**: what should happen
- **Actual behavior**: what actually happens
- **Logs/screenshots**: relevant error output

### Feature Requests

Include:

- **Problem statement**: what problem does this solve?
- **Proposed solution**: your suggested approach
- **Alternatives considered**: other approaches you evaluated
- **Additional context**: papers, references, prior art

## Research Contributions

We welcome research-oriented contributions. If you're contributing experimental code:

- Document your methodology in the PR description
- Include references to relevant papers
- Provide benchmark results where applicable
- Clearly mark experimental features as such

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md). We are committed to providing a welcoming and inclusive experience for everyone.

## Questions?

Open an issue or reach out at **ahelipoddar2003@gmail.com**.
