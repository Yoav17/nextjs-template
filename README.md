This is a [Next.js](https://nextjs.org/) 16 project tamplate that includes the following technologies:

- [TypeScript](https://typescriptlang.org/)
- [Bun](https://bun.com/)
- [Biome](https://biomejs.dev/)
- [Prisma](https://prisma.io/orm/)
- [Better Auth](https://better-auth.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Shadcn UI](https://ui.shadcn.com/)

## Goal

Focus on getting the project up and running as quickly as possible. Not worry about configuration but rather focus on shipping features.

## Getting Started

Create a `.env` file in the root of the project and add the enviroment variables from the .env.example file.

Install dependencies:

```bash
bun install
```

Generate Prisma client:

```bash
bunx prisma generate
```

Run dev server:

```bash
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## More opinionated settings

Configuration files are located in the root of the project, source code is located in the `src` folder.

Turbopack, React compiler and cache components are enabled.

No customaization for import aliases (\`@/\*\` by default).

## Other included dependencies

- [Neverthrow](https://github.com/supermacro/neverthrow/)
- [Zod](https://zod.dev/)
- [Nuqs](https://nuqs.dev/)
