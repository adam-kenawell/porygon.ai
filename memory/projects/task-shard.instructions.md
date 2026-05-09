# Task Shard — Project Memory

## Overview
- **Repo**: `adam-kenawell/task-shard` (public)
- **Type**: Standalone TypeScript library, same pattern as `pmd-visualizer`
- **Tagline**: "Shard your workflow"
- **URL**: `https://adam.kenawell.family/projects/task-shard`
- **Linked from**: `adam.kenawell.family` via `"task-shard": "file:../task-shard"` in package.json

## Architecture
- Pure client-side kanban board — no backend, localStorage for persistence
- Four columns: To Do, In Progress, Blocked, Completed
- Cards have: title, short description, full description, due date
- Click-to-expand cards show full description + edit/delete actions
- HTML5 drag-and-drop to move cards between columns
- Data is per-browser (localStorage scoped by origin)

## File Structure
- `src/types.ts` — `Task` interface, `ColumnId` type, `COLUMNS` constant
- `src/storage.ts` — localStorage CRUD helpers
- `src/board.ts` — DOM rendering, drag-and-drop, modal form
- `src/index.ts` — barrel exports

## Website Integration
- Project card in `src/pages/projects.astro`
- Full page at `src/pages/projects/task-shard.astro`
- Styles use `:global()` for library-generated DOM, matching site theme variables

## Session Date
2026-05-08
