---
name: "frontend-code-review"
description: "Automated frontend code review for .tsx, .ts, .js files. Invoke before git commit or when reviewing specific frontend files for quality, performance, and business logic issues."
---

# Frontend Code Review

This skill automates frontend code review with a focus on code quality, performance, and business logic.

## When to Use

- Before committing code changes (git commit)
- Reviewing specific files for refactoring or optimization
- Getting structured fix reports for identified issues

## Review Dimensions

### Code Quality
- General coding standards for clean, consistent, maintainable code
- Example: Use `cn` utility function for dynamic CSS classes instead of string concatenation

### Performance
- Frontend performance best practices
- Example: Wrap complex props (objects, arrays) with `useMemo` to prevent unnecessary re-renders

### Business Logic
- Business-specific rules to prevent logic errors
- Example: Avoid using `workflowStore` in certain components to prevent white screen issues

## Output Format

Issues are categorized as:
- **Urgent**: Must be fixed before merge
- **Suggestions**: Recommended improvements

Each issue includes:
- File path and line number
- Code snippet
- Actionable fix recommendation

## Usage

```
Review my staged changes
Review src/components/Button.tsx
```
