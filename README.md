# Turbo Monorepo Template

This is a starter template for a monorepo using [Turborepo](https://turbo.build/).

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `apps/docs`: A documentation site
- `apps/web`: A web application
- `packages/ui`: A stub React component library shared by both `web` and `docs` applications
- `packages/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `packages/tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% TypeScript.

## Utilities

This Turborepo has some additional tools already setup for you:

- TypeScript for static type checking
- ESLint for code linting
- Prettier for code formatting

## Build

To build all apps and packages, run the following command:

```bash
pnpm build
```

## Develop

To develop all apps and packages, run the following command:

```bash
pnpm dev
```

## Remote Caching

Turborepo can use a technique known as Remote Caching to share cache artifacts across machines, enabling you to share build caches with your team and CI/CD pipelines.

By default, Turborepo will cache locally. To enable Remote Caching you will need an account with Vercel. If you don't have an account you can create one, then enter the following commands:

```bash
npx turbo login
npx turbo link
```

## Useful Links

Learn more about the power of Turborepo:

- Pipelines
- Caching
- Remote Caching
- Filtering
- Configuration Options
- CLI Usage
