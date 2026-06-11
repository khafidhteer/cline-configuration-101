# Testing Standards

> Copy this file to your project's `.clinerules/testing.md` and modify for your preferences.

## General
- Write tests for all business logic and API endpoints
- One test file per source file: `component.ts` → `component.test.ts`

## Naming
- Use descriptive names: "should [expected behavior] when [condition]"
- Example: "should return 401 when token is expired"

## Structure
- Unit tests for isolated logic
- Integration tests for API endpoints
- Mock external APIs and databases, not internal modules

## Coverage
- Aim for 80%+ coverage on business logic
- Critical paths (auth, payments) need 100% coverage

## Running Tests
- `npm test` for unit tests
- `npm run test:e2e` for end-to-end tests