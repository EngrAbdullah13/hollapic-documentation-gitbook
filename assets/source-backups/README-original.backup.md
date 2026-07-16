# HollaPic

HollaPic is an AI ecommerce image generation app with a React/Vite frontend and a TypeScript/Express backend. It supports OTP authentication, credit based generation, Stripe plans, Brand DNA, shared workspace access, Cloudflare R2 image storage, and OpenAI powered prompt planning/image generation.

## Documentation

Full project documentation is here:

```text
docs/HOLLAPIC_PROJECT_DOCUMENTATION.md
```

It covers:

- What technology we use and why.
- Frontend architecture.
- Backend architecture.
- Database schema.
- Authentication and OTP.
- Credits and Stripe.
- Image generation workflows.
- Brand DNA.
- Shared workspace access.
- Admin tools.
- Deployment and migrations.
- Testing and developer workflows.

## Project Structure

```text
hollapic-ai-app/
  frontend/   React + Vite website
  backend/    Express API, Prisma, Stripe, OpenAI, R2
  scripts/    Local helper scripts
  docs/       Project documentation
```

## Local Setup

Install dependencies:

```powershell
npm install
npm install --prefix frontend
npm install --prefix backend
```

Create `backend/.env` with the required local values. See the full documentation for the complete environment variable list.

Run migrations:

```powershell
npm run migrate
```

Start frontend and backend together:

```powershell
npm run dev
```

Open:

```text
http://localhost:5173
```

Backend health:

```text
http://localhost:5000/health
```

## Useful Commands

```powershell
npm run dev
npm run dev:frontend
npm run dev:backend
npm run build
npm run build:frontend
npm run build:backend
npm run migrate
npm run start
```

## Production Notes

- Production target is Heroku.
- Run Prisma migrations with `npm run migrate`.
- Do not use `prisma db push` for production.
- Stripe webhook endpoint must point to `/api/stripe/webhook`.
- The backend serves the built frontend in production.
