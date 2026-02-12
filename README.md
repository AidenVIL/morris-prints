# Morris Prints

Scaffolded Vite + React frontend for the Morris Prints 3D printer website.

## Local dev

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

This project is configured to output the production build into the `docs/` folder so GitHub Pages can serve it.

## Next steps

- Set up a Supabase project and add the `VITE_SUPABASE_URL` and `VITE_SUPABASE_ANON_KEY` to GitHub secrets.
- Add Stripe keys to handle payments via serverless functions.
- Implement quoting logic and integration with printer data.
