---
name: "cache-components"
description: "Integrates Next.js Partial Prerendering (PPR) and Cache Components best practices. Invoke when working with Next.js caching, PPR, or server components."
---

# Cache Components

This skill integrates Next.js Partial Prerendering (PPR) and Cache Components best practices into your development workflow.

## When to Use

- Creating data-fetching components that need optimal rendering strategies
- Implementing cache invalidation after data mutations
- Building pages with Partial Prerendering architecture
- Modernizing existing caching patterns

## Key Capabilities

### Automatic Cache-Optimized Data Components

When creating data-fetching components, automatically apply optimal rendering strategies:
- For shareable data (e.g., product catalogs): Use `'use cache'` syntax
- For user-specific content: Add `<Suspense>` boundaries for dynamic streaming

### Automatic Cache Invalidation

When generating Server Actions for data modification:
- Automatically inject cache invalidation logic (e.g., `updateTag()` method)
- Ensure data consistency across the application

### Smart Page Construction

- Enforce Partial Prerendering (PPR) architecture for optimal loading performance
- Identify and suggest modernization improvements
- Replace outdated page-level caching with component-level `'use cache'`

## Configuration

Activate by enabling `cacheComponents: true` in your project configuration.
