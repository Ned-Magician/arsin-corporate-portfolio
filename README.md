# Arsin Corporate Website

A responsive, multi-page corporate website built with **Next.js, React, TypeScript, and Tailwind CSS** for a public frontend portfolio showcase.

The website represents an MDF lamination business. This repository is a **separate public showcase**, not the client's production source code.

**[Live Demo](https://arsin-corporate-portfolio.vercel.app/)**

## Tech Stack

- Next.js 16 (App Router)
- React 19
- TypeScript
- Tailwind CSS 4
- ESLint
- Git & GitHub
- Vercel deployment

## What It Demonstrates

- Six routes: Home, Services, Gallery, About, FAQ, and Contact
- Reusable layout, section, and UI components
- Shared, typed content for navigation, services, FAQs, and contact details
- Desktop navigation and an interactive mobile menu
- Semantic HTML and keyboard-visible focus styles
- Responsive layouts and Next.js image handling
- Page metadata and production build tooling

The contact page provides business information and direct contact links; it is not an online inquiry submission form.

## Project Structure

```text
app/
  about/
  contact/
  faq/
  gallery/
  services/
components/
  layout/
  sections/
  services/
  ui/
data/
  contact.ts
  faqs.ts
  navigation.ts
  services.ts
```

## Run Locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Quality Checks

```bash
npm run lint
npm run typecheck
npm run build
```

These scripts are available in `package.json`. Automated test coverage is not claimed here.

## Scope

This repository is intended to demonstrate publicly shareable frontend implementation and design. It should not be mistaken for the client's private production repository.
