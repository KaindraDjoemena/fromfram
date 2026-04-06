
## setup server database pakai docker

### contoh .env

```bash
DATABASE_URL=postgresql://fromfram:fromfram@localhost:5432/fromfram
JWT_SECRET=
```

### setup server

```bash
# running server db
docker compose up -d

# migrasi db
npx prisma migrate dev

npm run dev
```