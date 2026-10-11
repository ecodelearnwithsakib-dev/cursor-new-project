# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Current state

This repo is a pre-scaffold placeholder for a Node.js + TypeScript + Next.js (App Router) web app. No application code exists yet:

- `package.json` is a bare `npm init` (CommonJS, `main: index.js`) whose only dependency is `dotenv`.
- There is no `app/`, `tsconfig.json`, Next.js config, linter, or test runner yet.
- `node_modules/` is committed and there is no `.gitignore`. When scaffolding, add a `.gitignore` (at least `node_modules/`, `.next/`, `.env*`) and untrack `node_modules/`.
- `cursor.md` holds the equivalent agent notes for Cursor. Keep it and this file in sync when conventions change.

## Commands

Package manager is npm.

```bash
npm install
npm run dev   # once Next.js is scaffolded; serves http://localhost:3000
npm test      # placeholder, currently exits with an error
```

When you scaffold Next.js or add lint/test tooling, update this section with the real build, lint, and single-test commands.

## Conventions

- TypeScript throughout. Avoid `any` unless there is no practical alternative.
- Use the App Router (`app/`). Server Components by default; Client Components only when interactivity or browser APIs require them.
- Colocate route UI, `loading`, and `error` files with their route.
- Keep API logic in Route Handlers or server-only modules. Don't expose secrets to the client.
- Once the app is scaffolded, follow its existing file and naming patterns.
- Keep changes scoped to the task.
- Verify UI changes in the browser before calling the work done.

## Working preferences

- Don't commit or push unless asked.
- Write concise, complete sentences.
