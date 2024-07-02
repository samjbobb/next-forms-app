# Forms with Next.js and Server Actions

From https://github.com/vercel/next.js/tree/canary/examples/next-forms with some versions updated to get this working on 2024-07-02.

`pnpm install` to install the dependencies (or `npm install` probably works).

Run a local instance of Postgres via your preferred method.

```
CREATE TABLE todos (
  id SERIAL PRIMARY KEY,
  text TEXT NOT NULL
);
```

Create a `.env` with 

`POSTGRES_URL=postgresql://...`

`pnpm dev` to run the development server.