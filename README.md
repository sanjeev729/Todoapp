# Todoapp

A minimal Todo application built with **Astro** (and **Tailwind CSS** for styling).

## Tech stack
- **Astro** for the static/site framework
- **Tailwind CSS** for styling

## Prerequisites
- Node.js **>= 22.12.0**

## Getting started
From the project root:

```sh
npm install
npm run dev
```

Open the URL shown in your terminal (Astro typically runs on `http://localhost:4321`).

## Build & preview
```sh
npm run build
npm run preview
```

## Project structure

```text
.
├── public/
│   ├── favicon.ico
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── TodoApp.astro
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
├── tsconfig.json
└── DESIGN.md
```

## Design language
UI/visual guidance for this project lives in **`DESIGN.md`**. If you update components or layouts, keep the styling consistent with that document.

