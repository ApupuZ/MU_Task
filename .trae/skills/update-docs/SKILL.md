---
name: "update-docs"
description: "Guided workflow for updating Next.js documentation based on code changes. Invoke when code changes affect documentation or when creating new feature docs."
---

# Update Docs

This skill provides a guided workflow for updating Next.js project documentation based on source code changes.

## When to Use

- Analyzing code change impact on documentation
- Updating existing documentation for changed APIs/features
- Creating scaffold documentation for new features

## Key Capabilities

### Code-to-Docs Mapping

Analyzes git diff to identify which documentation files need updates based on predefined mappings.

### Documentation Updates

For existing documentation:
- Add or modify props tables
- Update code examples
- Add deprecation notices
- Follow project conventions (e.g., `<AppOnly>` / `<PagesOnly>`)

### New Documentation Scaffolding

For new features:
- Provides standard templates for different doc types (API reference, guides)
- Ensures proper structure, naming, and frontmatter

## Reference Files

- `CODE-TO-DOCS-MAPPING.md`: Maps source files to documentation files
- `DOC-CONVENTIONS.md`: Style guide for consistent documentation

## Usage

```
Update docs for my changes
Create documentation for new component
```
