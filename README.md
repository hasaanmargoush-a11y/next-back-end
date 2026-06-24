# Nouvil Backend

This is the backend API server for Nouvil.

## Setup

1. Install dependencies:
   ```bash
   pnpm install
   ```

2. Create a local environment file if needed:
   ```bash
   cp .env.example .env
   ```

3. Run locally:
   ```bash
   pnpm dev
   ```

## Build

```bash
pnpm build
```

## Start

```bash
pnpm start
```

## Environment variables

- `DATABASE_URL` - Postgres connection string
- `SESSION_SECRET`
- `NODE_ENV`
- `PORT`
