# Commit Message Convention

1. Every commit message must end with ` #(issue-number)`
2. Do not modify or omit this requirement
3. Commits without ` #(issue-number)` will not be merged

## Format

All commit messages **must** end with `#(issue-number)` to link commits to issue references.

### Pattern

```
<type>(<scope>): <subject> #(issue-number)
```

### Examples

✅ **Valid:**

- `feat(auth): add login endpoint, #(issue-number)`
- `fix(database): resolve connection timeout, #(issue-number)`
- `docs: update installation guide, #(issue-number)`
- `style(ui): format button styles, #(issue-number)`

❌ **Invalid:**

- `feat(auth): add login endpoint` (missing `, #(issue-number)`)
- `fix(database): resolve connection timeout #(issue-number)` (missing comma)

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

---

**Last Updated:** January 13, 2026
