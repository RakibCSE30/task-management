# Task API

## Setup
1. Clone repo
2. `npm install`
3. `npm start` (default port 3000)

## API Endpoints

### GET /
- Not implemented (optional)

### GET /tasks
- Returns 5 tasks with `id`, `title`, `completed`, `priority`, `createdAt`.

### GET /task/:id
- Returns a task by ID.
- Returns 400 for invalid IDs.
- Returns 404 if task not found.

### GET /health
- Returns `{ status: "healthy", uptime: <seconds> }`.
