# New Cursor Project

A Node.js web app built with TypeScript and Next.js (App Router).

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **Package manager:** npm

## Getting started

```bash
npm install
```

Once the Next.js app is scaffolded:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in the browser.

## Scripts

| Script | Description |
| ------ | ----------- |
| `npm test` | Placeholder — no tests yet |

## Project conventions

- Use TypeScript throughout. Avoid `any` unless there is no practical alternative.
- Prefer the Next.js App Router (`app/`), Server Components by default, and Client Components only when interactivity or browser APIs require them.
- Colocate route UI, loading, and error files with the route they belong to.
- Keep API logic in Route Handlers or server-only modules; do not leak secrets to the client.

## License

ISC
