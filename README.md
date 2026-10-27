# Arsin — Corporate Website Showcase

**Next.js 16 · React 19 · TypeScript · Tailwind CSS 4**

A responsive, six-page corporate website showcase for an MDF lamination business. The project emphasizes clear navigation, reusable UI components, structured content, and practical contact options.

**[View live website](https://arsin-corporate-portfolio.vercel.app/)** · **[Developer's GitHub profile](https://github.com/Ned-Magician)**

![Arsin website — desktop homepage](./public/screenshots/home-desktop.png)

## Context

This publicly shareable project is related to **one paid corporate website engagement in 2026**. It is a **separate portfolio implementation**, not the client's private production source code. It does not represent a second client contract.

## Highlights

- Six routes: **Home, Services, Gallery, About, FAQ, Contact**
- Shared TypeScript data for navigation, services, FAQs, and contact details
- Reusable header, sections, and UI components
- Responsive layout and interactive mobile navigation
- Semantic HTML, visible keyboard focus styles, and page metadata
- Gallery and direct contact links; **no backend contact form**

| Homepage | Mobile navigation |
| --- | --- |
| ![Desktop layout](./public/screenshots/home-desktop.png) | ![Mobile menu](./public/screenshots/mobile-menu.png) |

## Implementation

```text
app/            Next.js App Router pages and layouts
components/     Reusable layout and page sections
data/           Typed content and navigation data
public/         Images, brand assets, screenshots
```

## Run locally

```bash
npm install
npm run dev
```

Then visit `http://localhost:3000`.

## Available quality checks

```bash
npm run lint
npm run typecheck
npm run build
```

These scripts are configured in `package.json`. Automated test coverage is **not** claimed.

## Scope

This repository demonstrates front-end UI engineering and publicly shareable project work. It should **not** be mistaken for a verified live client production deployment.

[**More selected work**](https://github.com/Ned-Magician)
