## Criar .env

```
### NEON DB
DATABASE_URL="postgresql://neondb_owner:YJf..."

### AUTENTIFICAÇÃO COM CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_dG9...
CLERK_SECRET_KEY=sk_test_snn...

### ASSINATURAS DE PLANOS DO STRIPE
STRIPE_PREMIUM_PLAN_PRICE_ID="price_1Q..."
STRIPE_SECRET_KEY="sk_test_51QJ..."
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY="pk_test_51QJzp..."
NEXT_PUBLIC_STRIPE_CUSTOMER_PORTAL_URL="https://billing.stripe.com/p/login/test_..."

### STRIPE CLI SECRET (stripe listen --forward-to http://localhost:3000/api/webhooks/stripe)
STRIPE_WEBHOOK_SECRET="whsec_0dc5ea115df18e408d00c5d7f3cc1ce78f14e78f21d1ca2147e43877a0b924b0"

### OpenAI KEY
OPENAI_API_KEY="sk-proj-nvj..."

### Redirecionamento localhost
APP_URL="http://localhost:3000"

### Redirecionamento Produção
APP_URL="https://financeai-xi.vercel.app/"

```

## Node Version
v20.12.2

## Rodar Localmente
```bash
npm install
npm run dev
```


<img src="/public/financeAI Project-financeAI Project.png">
