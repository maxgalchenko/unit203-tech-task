# Unit203 – Tech assessment

<div align="center">

<img alt="React" src="https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white" />
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-13-black?logo=nextdotjs&logoColor=white" />
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-4.9-3178C6?logo=typescript&logoColor=white" />
<img alt="Styled Components" src="https://img.shields.io/badge/styled--components-5.3-DB7093?logo=styled-components&logoColor=white" />
<img alt="ESLint" src="https://img.shields.io/badge/ESLint-8-4B32C3?logo=eslint&logoColor=white" />
<img alt="Prettier" src="https://img.shields.io/badge/Prettier-2-1A2C34?logo=prettier&logoColor=F7B93E" />
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-18-339933?logo=node.js&logoColor=white" />

</div>

## Overview

Small Next.js (pages router) app built as a tech assessment. Demonstrates basic pages, API routes, and styled-components theming. Useful as a concise reference for structure and code style.

## Key Features

- Basic pages and layout using Next.js
- Simple API routes under `pages/api`
- Theming and global styles with `styled-components`

## Tech Stack

React 18, Next.js 13, TypeScript 4.9, Node.js 18

## Architecture

Next.js Pages Router with `pages/` and `pages/api/`. Styling via `styled-components` and global theme. No database or external services.

## Performance & Accessibility

Leverages Next.js defaults: React Strict Mode, image/svg optimization, and semantic HTML where applicable.

## Quality

- Linting: `eslint-config-next` • Formatting: Prettier
- Type safety: `tsconfig` with `strict: true`
- Tests: none
- CI: GitHub Actions (lint and prettier checks)

## Prerequisites

- Node.js: `18.17.0`

## Installation

```bash
git clone https://github.com/maxgalchenko/unit203-tech-task.git
cd unit203-tech-task
npm install
```

## Quick Start

```bash
npm run dev
# Production
npm run build
npm start
```

Open http://localhost:3000

## Available Scripts

- `npm run dev` – Start Next.js in development mode
- `npm run build` – Create production build
- `npm start` – Start production server
- `npm run lint` – Run Next.js ESLint
- `npm run lint-check` – Run ESLint across js, jsx, ts, tsx
- `npm run prettier-check` – Check formatting with Prettier

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
