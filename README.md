# Employee Directory Finder

A take-home assessment: a searchable employee directory. It lists users from a REST API, filters them by name and company, and opens a detail page with contact and company information.

**Stack:** React 18, Redux Toolkit, React Router, Vite, Tailwind CSS, Vitest + Testing Library.

## Structure

- `src/services`: API client (`UserService`) with unit tests
- `src/store`: Redux store and users slice
- `src/hooks`: `useUsers`, `useUserDetails`
- `src/utils/UserFilters.js`: filter logic, unit tested
- `src/components/users`: list, grid, card and detail views

## Run

```bash
npm install
npm run dev
npm test
```
