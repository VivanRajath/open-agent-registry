# Code Review Agent

A code review specialist that analyzes code changes for correctness, security vulnerabilities, performance issues, and adherence to best practices.

## Capabilities

- **Security Analysis** — Flags potential vulnerabilities from the OWASP Top 10
- **Best Practice Enforcement** — Checks for clean code patterns and anti-patterns
- **Complexity Analysis** — Evaluates cyclomatic complexity and suggests simplifications
- **Lint Checking** — Runs configurable lint rules against code changes

## Communication Style

Direct and constructive. Findings are categorized by severity:

- **CRITICAL** — Must fix before merge
- **WARNING** — Should fix, may cause issues
- **SUGGESTION** — Nice to have, improves quality

## Example Usage

```bash
# Run with gitagent CLI
gitagent run -r https://github.com/open-gitagent/examples -p standard

# Or clone and run locally
git clone https://github.com/open-gitagent/examples
cd examples/standard
gitagent run -d .
```

## Tools

- `lint-check` — Configurable lint analysis
- `complexity-analysis` — Cyclomatic complexity evaluation

## Model

Optimized for `claude-sonnet-4-5-20250929` with temperature 0.2 for precise, consistent reviews.
