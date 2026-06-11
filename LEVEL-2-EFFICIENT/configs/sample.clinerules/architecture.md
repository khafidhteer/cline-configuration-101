# Architecture Decisions

> Copy this file to your project's `.clinerules/architecture.md` and modify for your preferences.

## Project Structure
- Feature-based folder organization
- Shared code in `src/shared/` or `src/lib/`
- Each feature is self-contained with its own components, hooks, and tests

## Components
- Prefer composition over inheritance
- Keep components focused on a single responsibility
- Extract reusable logic into custom hooks

## Data Flow
- Unidirectional data flow (top-down)
- Use React context or state management for global state
- API calls go through service layers, not directly in components

## API Design
- RESTful endpoints with consistent naming
- Version your APIs (`/api/v1/`)
- Return standard error responses

## Database
- Use repository pattern for data access
- All queries go through repositories, not directly from services
- Migrations are separate from schema definitions