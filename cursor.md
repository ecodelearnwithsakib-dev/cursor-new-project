# New Cursor Project

Project notes for the Cursor agent working in this folder.

## About

- Owner: Sakib
- Role: Software engineer
- A Node.js app built with TypeScript and Next.js.

## Tech stack

- Runtime: Node.js
- Language: TypeScript
- Framework: Next.js (App Router)
- Package manager: npm unless the repo already uses another one

## Preferences

- Work directly in code: create, debug, and iterate.
- Prefer concise, complete sentences.
- Do not commit unless asked.
- Do not push unless asked.

## Conventions

- Use TypeScript throughout. Avoid `any` unless there is no practical alternative.
- Prefer the Next.js App Router (`app/`), Server Components by default, and Client Components only when interactivity or browser APIs require them.
- Colocate route UI, loading, and error files with the route they belong to.
- Keep API logic in Route Handlers or server-only modules; do not leak secrets to the client.
- Follow existing file and naming patterns once the app is scaffolded.
- Keep changes scoped to the task.
- Verify UI changes in the browser before calling the work done.
