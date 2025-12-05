---
applyTo: '*'
---

# Conventional Commits Instructions

Adopt the Conventional Commits specification for all commit messages to ensure readable history and automated changelog generation.

## Main Rules

Commit message format:

<type>[optional scope]: <description>

- type: feat, fix, docs, style, refactor, perf, test, build, ci, chore, revert
- scope (optional): api, domain, infrastructure, tests, etc.
- description: imperative, lowercase, no period at end
- first line must not exceed 72 characters

## Examples

feat(api): add order endpoint  
fix(domain): correct order validation logic  
test(order): add unit tests for order creation  
chore: update dependencies  

## Best Practices

- Use English for all commit messages.
- One commit = one logical change.
- Use scope to specify the affected layer.
- For breaking changes, add ! after type or scope and detail in body.

---
