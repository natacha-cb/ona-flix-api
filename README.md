# OnaFlix API

Backend API service for the OnaFlix movie streaming platform. Built with Express and TypeScript.

## Stack

- **Runtime:** Node.js 18+
- **Framework:** Express
- **Language:** TypeScript
- **Database:** PostgreSQL
- **Cache:** Redis (optional)
- **Validation:** Zod
- **Logging:** Winston

## Setup

```bash
npm install
cp .env.example .env
# Edit .env with your database credentials
npm run dev
```

## API Endpoints

- `GET /health` -- Service health check
- `GET /api/movies` -- List all movies
- `GET /api/search` -- Search with filters
- `GET /api/suggestions` -- Autocomplete suggestions
- `POST /api/movies/seed` -- Seed database
- `POST /api/movies/clear` -- Clear database

## Testing

```bash
npm test
npm run test:coverage
```
