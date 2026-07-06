# React Template

A modern React + TypeScript template with Vite, Tailwind CSS, and Biome.

## Features

- ⚡️ [Vite](https://vitejs.dev/) - Next generation frontend build tool
- ⚛️ [React](https://react.dev/) 19 - UI library
- 📘 [TypeScript](https://www.typescriptlang.org/) - Typed JavaScript
- 🎨 [Tailwind CSS](https://tailwindcss.com/) v4 - Utility-first CSS framework
- 🔧 [Biome](https://biomejs.dev/) - Fast formatter for JavaScript, TypeScript, JSX, and JSON
- 🐶 [Husky](https://typicode.github.io/husky/) - Git hooks
- 📦 [pnpm](https://pnpm.io/) - Fast, disk space efficient package manager

## Getting Started

### Install dependencies

```bash
pnpm install
```

### Development

Start the development server:

```bash
pnpm dev
```

### Build

Build for production:

```bash
pnpm build
```

### Preview

Preview the production build:

```bash
pnpm preview
```

## Code Quality

### Lint & Format

Check code for issues:

```bash
pnpm check
```

Automatically fix issues:

```bash
pnpm check:fix
```

Check only staged files:

```bash
pnpm check:staged
```

## Project Structure

```
├── src/
│   ├── App.tsx      # Main application component
│   ├── main.tsx    # Application entry point
│   └── style.css   # Global styles
├── index.html      # HTML entry point
├── vite.config.ts  # Vite configuration
├── biome.json      # Biome configuration
├── tsconfig.json   # TypeScript configuration
└── package.json   # Project dependencies
```

## Tech Stack

| Category | Technology |
|----------|------------|
| Framework | React 19 |
| Build Tool | Vite 8 |
| Language | TypeScript 6 |
| Styling | Tailwind CSS 4 |
| Linting | Biome 2 |
| Git Hooks | Husky 9 |
| Package Manager | pnpm |