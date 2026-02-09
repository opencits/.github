# Repository Guidelines

## Project Structure & Module Organization
This repository currently contains only top-level documentation. Key files:
- `README.md`: brief repository description.
- `LICENSE`: license text.
- `AGENTS.md`: contributor guide (this document).

There are no `src/`, `tests/`, or asset directories yet. If you add code, place it under a clearly named top-level folder (for example, `src/` for source and `tests/` for tests) and update `README.md` to reflect the structure.

## Build, Test, and Development Commands
No build or test tooling is configured at this time. If you introduce tooling, document the exact commands here and in `README.md` (for example: `npm test`, `make build`, or `pytest`). Keep commands deterministic and ensure they run from the repository root.

## Coding Style & Naming Conventions
There are no established style or linting configurations in the repository. Follow these minimal conventions to keep things consistent:
- Use clear, descriptive file and folder names in lowercase with hyphens (for example, `docs-setup.md`).
- Keep Markdown headings hierarchical and avoid skipping levels.
- When adding code, align with the language’s standard formatter (and add the formatter to the repo).

## Testing Guidelines
No test framework is currently defined. If you add tests, choose a standard framework for the language, document it here, and include a minimal example. Name tests clearly and group them under `tests/` (for example, `tests/test_example.py` or `tests/example.spec.ts`).

## Commit & Pull Request Guidelines
Git history only contains an `Initial commit`, so there is no established convention. Use concise, imperative commit messages (for example, “Add contributor guide”).

For pull requests:
- Provide a short summary of changes.
- Note any new directories or tooling added.
- Link relevant issues or context if available.

## Agent-Specific Instructions
Automation or agent behavior is not defined in this repository. If you add scripts or CI workflows, document how to run them and any required environment variables.
