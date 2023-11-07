# ai-agents


stripe listen --forward-to localhost:3000/api/webhook
npx prisma studio
npm run dev

1. npx prisma studio - run studio data
2. node scripts/seed.ts -  seed the categories
3. npx prisma migrate reset

= important
4. npx prisma generate
5. npx prisma db push