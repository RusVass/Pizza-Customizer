# Pizza Customizer

## Run

1. `npm install`
2. `npm run dev`

## Tests

1. `npm run test`

## Lint and format

1. `npm run lint`
2. `npm run format`

## Description

Pizza order manager with CRUD, theme persistence (light/dark/system), and live price.

- React (Vite) + TypeScript
- Tailwind CSS
- Zustand
- React Hook Form + Zod

## Test Task

Technical Assessment: Pizza Customizer CRUD (Final Version)

Scope:
- Theme toggle with persistence and system preference via `matchMedia`.
- Apply theme via the `dark` class on `html` or `body` (implemented on `html`).
- Prevent FOUC with early inline script in `index.html`.
- Dashboard with pizza cards and delete action.
- Builder form for create and edit by id.
- Name field with Zod validation (2–40 chars).
- Size as radio group, dough as select.
- Toppings as grouped checkboxes by category.
- Live price based on size, dough, and toppings.
- Global state using Zustand with immutable updates.
- Store API: addPizza, updatePizza, deletePizza.
- UI kit for base elements in a separate folder.
- Types via interfaces for Pizza, Topping, Theme.
- Utility Types usage (e.g. `Omit`, `Pick`).
- Tests for core logic with at least 3 edge cases.

## Structure

- `src/components` — UI kit and layout
- `src/features` — pizza features
- `src/hooks` — custom hooks
- `src/store` — Zustand stores
- `src/utils` — utilities
- `src/types` — types
- `src/__tests__` — tests
