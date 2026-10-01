# Awesome React Production Stack

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of tools, libraries, and resources for building production-ready React applications.

**Language:** [🇬🇧 English](README.md) | [🇪🇸 Español](README-es.md)

---

## Contents

- [Frameworks & Meta-Frameworks](#frameworks--meta-frameworks)
- [State Management](#state-management)
- [Data Fetching](#data-fetching)
- [Routing](#routing)
- [Styling](#styling)
- [UI Component Libraries](#ui-component-libraries)
- [Forms](#forms)
- [Testing](#testing)
- [Development Tools](#development-tools)
- [Code Quality](#code-quality)
- [Monitoring & Error Tracking](#monitoring--error-tracking)
- [Internationalization](#internationalization)
- [Component Documentation](#component-documentation)
- [Templates & Starters](#templates--starters)
- [Learning Resources](#learning-resources)

---

## Frameworks & Meta-Frameworks

- [Next.js](https://github.com/vercel/next.js#readme) - The React framework for production. Supports SSR, SSG, ISR, and App Router.
- [Remix](https://github.com/remix-run/remix#readme) - Full-stack framework focused on user experience and web standards.
- [Gatsby](https://github.com/gatsbyjs/gatsby#readme) - GraphQL-based framework for building blazing-fast static sites.
- [Vike](https://github.com/vikejs/vike#readme) - Modular framework with support for SSR, SPA, and MPA.
- [Refine](https://github.com/refinedev/refine#readme) - Framework for building CRUD apps and admin panels without constraints.

## State Management

- [Zustand](https://github.com/pmndrs/zustand#readme) - Minimalist and scalable state management with a hook-based API.
- [Redux Toolkit](https://github.com/reduxjs/redux-toolkit#readme) - The official, recommended way to write Redux logic.
- [Jotai](https://github.com/pmndrs/jotai#readme) - Primitive and atomic state management for React.
- [MobX](https://github.com/mobxjs/mobx#readme) - Simple and scalable state management through observables.
- [XState](https://github.com/statelyai/xstate#readme) - State machines and statecharts for complex logic.

## Data Fetching

- [TanStack Query](https://github.com/TanStack/query#readme) - Powerful asynchronous state management for server data.
- [SWR](https://github.com/vercel/swr#readme) - React hooks for data fetching with automatic revalidation.
- [Apollo Client](https://github.com/apollographql/apollo-client#readme) - Comprehensive, production-ready GraphQL client.
- [Relay](https://github.com/facebook/relay#readme) - React framework for building data-driven GraphQL applications.
- [Axios](https://github.com/axios/axios#readme) - Promise-based HTTP client for the browser and Node.js.

## Routing

- [React Router](https://github.com/remix-run/react-router#readme) - Declarative routing for React.
- [TanStack Router](https://github.com/TanStack/router#readme) - Type-safe router with built-in caching and URL state management.

## Styling

- [Tailwind CSS](https://github.com/tailwindlabs/tailwindcss#readme) - Utility-first CSS framework for rapidly building custom designs.
- [Styled Components](https://github.com/styled-components/styled-components#readme) - CSS-in-JS with visual primitives for the component age.
- [Emotion](https://github.com/emotion-js/emotion#readme) - High-performance CSS-in-JS library.
- [Vanilla Extract](https://github.com/vanilla-extract-css/vanilla-extract#readme) - Type-safe stylesheets in TypeScript with zero runtime.
- [CSS Modules](https://github.com/css-modules/css-modules#readme) - Locally scoped CSS to avoid name collisions.

## UI Component Libraries

- [shadcn/ui](https://github.com/shadcn-ui/ui#readme) - Beautifully designed components built with Radix UI and Tailwind CSS.
- [Radix UI](https://github.com/radix-ui/primitives#readme) - Unstyled, accessible UI primitives.
- [Ant Design](https://github.com/ant-design/ant-design#readme) - Enterprise-class UI design language and component library.
- [Mantine](https://github.com/mantinedev/mantine#readme) - Full-featured React component library with hooks support.
- [Chakra UI](https://github.com/chakra-ui/chakra-ui#readme) - Simple, modular, and accessible component system.
- [Material UI](https://github.com/mui/material-ui#readme) - Ready-to-use React components implementing Material Design.
- [Headless UI](https://github.com/tailwindlabs/headlessui#readme) - Unstyled, accessible UI components.

## Forms

- [React Hook Form](https://github.com/react-hook-form/react-hook-form#readme) - Performant, flexible forms with hook-based validation.
- [Formik](https://github.com/jaredpalmer/formik#readme) - Build forms in React without the tears.
- [Zod](https://github.com/colinhacks/zod#readme) - Schema validation with static TypeScript type inference.
- [Yup](https://github.com/jquense/yup#readme) - Schema builder for JavaScript object validation.

## Testing

- [Vitest](https://github.com/vitest-dev/vitest#readme) - Blazing-fast testing framework powered by Vite.
- [Jest](https://github.com/jestjs/jest#readme) - JavaScript testing framework focused on simplicity.
- [React Testing Library](https://github.com/testing-library/react-testing-library#readme) - Testing utilities for working with React components intuitively.
- [Cypress](https://github.com/cypress-io/cypress#readme) - Fast, reliable end-to-end testing for anything in the browser.
- [Playwright](https://github.com/microsoft/playwright#readme) - Browser automation framework for modern testing.
- [MSW](https://github.com/mswjs/msw#readme) - Mock Service Worker for intercepting HTTP requests in tests.

## Development Tools

- [Vite](https://github.com/vitejs/vite#readme) - Next-generation frontend tooling with lightning-fast HMR.
- [Turbopack](https://github.com/vercel/turbo#readme) - Incremental bundler optimized for JavaScript and TypeScript.
- [Storybook](https://github.com/storybookjs/storybook#readme) - UI workshop for developing components in isolation.
- [React DevTools](https://github.com/facebook/react/tree/main/packages/react-devtools#readme) - Browser extension to inspect the React component tree.
- [Why Did You Render](https://github.com/welldone-software/why-did-you-render#readme) - Notifies you about avoidable re-renders in React.
- [React Scan](https://github.com/aidenybai/react-scan#readme) - Scans and eliminates performance issues in your React app.

## Code Quality

- [ESLint](https://github.com/eslint/eslint#readme) - Linting utility for identifying and reporting patterns in JavaScript.
- [Prettier](https://github.com/prettier/prettier#readme) - Opinionated code formatter.
- [TypeScript](https://github.com/microsoft/TypeScript#readme) - JavaScript with syntax for static types.
- [Biome](https://github.com/biomejs/biome#readme) - High-performance toolchain for formatting and linting code.

## Monitoring & Error Tracking

- [Sentry](https://github.com/getsentry/sentry#readme) - Error and performance monitoring in production.
- [LogRocket](https://logrocket.com/) - Replay user sessions with console logs and Redux state.
- [React Error Boundary](https://github.com/bvaughn/react-error-boundary#readme) - Error boundary component for catching errors in React.

## Internationalization

- [react-i18next](https://github.com/i18next/react-i18next#readme) - Internationalization framework for React based on i18next.
- [FormatJS](https://github.com/formatjs/formatjs#readme) - Internationalization for web applications with React Intl.
- [Lingui](https://github.com/lingui/js-lingui#readme) - Simple and powerful i18n library for React.

## Component Documentation

- [Storybook](https://github.com/storybookjs/storybook#readme) - Document and develop components in isolation.
- [Docusaurus](https://github.com/facebook/docusaurus#readme) - Static site generator optimized for documentation.
- [React Docgen](https://github.com/reactjs/react-docgen#readme) - Extracts information from React components for automatic documentation.

## Templates & Starters

- [Vite + React + TypeScript](https://github.com/vitejs/vite/tree/main/packages/create-vite#readme) - Official Vite template for React with TypeScript.
- [Next.js + TypeScript](https://github.com/vercel/next.js/tree/canary/examples/with-typescript#readme) - Official Next.js example with TypeScript.
- [React Production Starter](https://github.com/jaredpalmer/react-production-starter#readme) - Production-ready React template with SSR and build pipeline.
- [T3 Stack](https://github.com/t3-oss/create-t3-app#readme) - Full-stack stack with Next.js, TypeScript, Tailwind, and tRPC.

## Learning Resources

- [React Official Documentation](https://react.dev/) - The official React documentation.
- [React TypeScript Cheatsheets](https://github.com/typescript-cheatsheets/react#readme) - Cheatsheets for experienced React developers getting started with TypeScript.
- [Awesome React](https://github.com/enaqx/awesome-react#readme) - A collection of awesome things regarding the React ecosystem.
- [Patterns.dev](https://www.patterns.dev/) - Free book on design patterns for modern web applications.

---

## Contributing

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

MIT (LICENSE)

---

## Notes about this list

- Lowercase name: `awesome-react-production-stack`
- Awesome badge in the header
- Table of contents with links to all sections
- Objective descriptions, no marketing language
- GitHub links end with `#readme`
- CC0 license (not MIT/Apache, since this is a content list, not code)

### Recommended repository files
