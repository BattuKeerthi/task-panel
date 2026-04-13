# Production Task Control Panel

A full-stack task management system with a Svelte frontend and Directus backend.

## Structure

- `frontend/` — SvelteKit app with Tailwind, reusable dashboard components, charting, task table, filters, bulk actions, and task form.
- `backend/` — Directus setup instructions, Docker compose, and collection schema.

## Run frontend

1. Open `frontend/`.
2. Copy `.env.example` to `.env` and set `VITE_DIRECTUS_URL`.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start development server:
   ```bash
   npm run dev -- --host
   ```

## Run backend

Use the backend instructions in `backend/README.md`.

## Notes

- The frontend integrates with Directus `tasks` collection.
- Use keyboard shortcuts: `Ctrl+N` for new task, `Ctrl+M` to complete selected, `Ctrl+F` to focus search.
