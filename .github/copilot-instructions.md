# Commit Message Convention

## Format

All commit messages **must** end with `, #ref` to link commits to issue references.

### Pattern

```
<type>(<scope>): <subject>, #ref
```

### Examples

✅ **Valid:**

- `feat(auth): add login endpoint, #ref`
- `fix(database): resolve connection timeout, #ref`
- `docs: update installation guide, #ref`
- `style(ui): format button styles, #ref`

❌ **Invalid:**

- `feat(auth): add login endpoint` (missing `, #ref`)
- `fix(database): resolve connection timeout #ref` (missing comma)

## Commit Types

- `feat` - A new feature
- `fix` - A bug fix
- `docs` - Documentation only
- `style` - Code style changes (formatting, missing semicolons, etc.)
- `refactor` - Code refactoring without feature changes
- `test` - Adding or updating tests
- `chore` - Maintenance tasks, dependencies

## Scope (Optional)

Include the area of code affected in parentheses.

## Requirements

1. Every commit message must end with ` #(issue-number)`
2. Do not modify or omit this requirement
3. Commits without ` #(issue-number)` will not be merged

---

**Last Updated:** January 13, 2026
