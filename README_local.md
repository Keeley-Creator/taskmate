# Taskmate Forest

A forest-themed planner web app with signup, login, task library, today's must-do list, and AI mate customization.

## Run locally

```bash
python3 app.py
```

Open http://127.0.0.1:8000

## Deployment note

This project currently uses a local SQLite database file. That works locally, but it is not suitable for durable persistence on Vercel serverless functions. To publish a real production URL, the next step is migrating storage to an external database such as Neon, Supabase, Turso, or another managed service.
