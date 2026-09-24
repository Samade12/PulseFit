# PulseFit 2.0 — Sophisticated Full-Stack Fitness Tracker

A detailed fitness tracker with explicit HTML structure, responsive CSS, a REST API, authentication and SQLite persistence.

## Features

- Responsive desktop/tablet/mobile UI
- Login and registration
- Dashboard with weekly activity chart
- Workout logging and filtering
- Workout history and deletion
- Exercise library with search/category/difficulty filters
- Weight history and trend visualization
- Goal creation, progress and completion
- Hydration logging
- Profile/settings
- SQLite persistence
- bcrypt password hashing
- HTTP-only JWT cookie authentication
- Seeded exercise library

## Start

```bash
npm install
npm start
```

Open:

```text
http://localhost:3000
```

For development:

```bash
npm run dev
```

Set a strong `JWT_SECRET` environment variable before production deployment.
