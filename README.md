# ChefBot AI

> AI-generated recipes from what's in your fridge

## Features
- Ingredient-based recipes
- Meal planning
- Grocery lists
- Dietary filters
- Cooking timer

## Stack
- Next.js 14 (App Router) + TypeScript
- Tailwind CSS
- OpenAI GPT-4o-mini
- Stripe Subscriptions
- Vercel deployment

## Quick Start

```bash
npm install
cp .env.example .env.local
# Fill in API keys
npm run dev
```

## Pricing
| Plan | Price |
|------|-------|
| Free | $0/mo |
| Pro  | $8/mo or $69/yr |

## Deploy
1. Push to `main` (CI runs lint/build checks)
2. Import the repo in Vercel
3. Configure the environment variables listed below
4. Deploy

## Environment Variables
Set these in `.env.local` for development and in Vercel for production:

- `NEXT_PUBLIC_APP_NAME`
- `NEXT_PUBLIC_APP_URL`
- `OPENAI_API_KEY`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `STRIPE_PRICE_PRO_MONTHLY`
- `STRIPE_PRICE_PRO_YEARLY`
- `DATABASE_URL`

## License
MIT (c) 2026 Aurora Rayes LLC
