# Coding Standards

> Copy this file to your project's `.clinerules/coding.md` and modify for your preferences.

## Language & Style
- Use TypeScript for all new files
- Use camelCase for variables and functions
- Use PascalCase for classes, components, and types
- Use UPPER_SNAKE for constants and environment variables

## File Organization
- One component per file
- Group related files in feature folders
- Keep files under 300 lines when possible

## Imports
- Group imports: external packages → internal modules → styles
- Use named exports (not default exports)
- Avoid barrel files (index.ts that re-export everything)

## Error Handling
- Use try/catch for async operations
- Return typed errors, not thrown strings
- Log errors with context

## Code Quality
- Write self-documenting code over comments
- Use comments to explain WHY, not WHAT
- Avoid magic numbers — use named constants