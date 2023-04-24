---
theme: the-unnamed
themeConfig:
  background: "#000"
layout: cover
highlighter: shiki
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Svelte Kit](https://kit.svelte.dev/)

Fullstack on steroids

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# Quickstart

```
npm create skeleton-app@latest my-skeleton-app
cd my-skeleton-app
```

---
layout: cover
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# The 'KIT' Part

client server by convention

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# Project structure

```bash
my-project/
├ src/
│ ├ lib/
│ │ ├ server/
│ │ │ └ [your server-only lib files]
│ │ └ [your lib files]
│ ├ params/
│ │ └ [your param matchers]
│ ├ routes/
│ │ ├ api
│ │ │ └ [your backend for frontend api routes]
│ │ └ [your frontend routes]
│ ├ app.html
│ ├ error.html
├ static/
│ └ [your static assets]
├ tests/
│ └ [your tests]
├ package.json
├ svelte.config.js
├ tsconfig.json
└ vite.config.js
```

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# File types

- `+page.svelte` Svelte Component for this route
- `+page.ts` Client side data load
- `+page.server.ts` Server side data load

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# Frontend page types

- Single Page Applicaiton (SPA) / Client-side rendering (CSR)
- Dynamic server side rendering (SSR)
- Static Site Generation (SSG)

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# State / routing with query params

?type

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# Form actions

Progressive enhancement

---
layout: cover
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# Svelte

a compiler not a framework

---
layout: section
class: "text-left"
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

> a React component is typically around 40% larger

<br />

> The Svelte implementation of TodoMVC weighs 3.6kb zipped. <br />
> For comparison, React plus ReactDOM without any app code
> weighs about 45kb zipped. <br />
> It takes about 10x as long for the browser just to evaluate React as it does for Svelte to be
> up and running with an interactive TodoMVC.

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# 1 gigabyte of data ~ 0,478 kg CO2

|                 | Angular         | React            | Svelte           |
|-----------------|-----------------|------------------|------------------|
| bundle size     | 180.3KB         | 6.3KB            | 3.8KB            |
| CO2 per visit   | 0,0000828 grams | 0,00000287 grams | 0,00000175 grams |
| 10,000 visitors | 0,82938 grams   | 0,02898 grams    | 0,01748 grams    |

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# Memory allocation in MBs ± 95% confidence interval - ([Krausest](https://github.com/krausest/js-framework-benchmark))

| Name                                       | svelte-v3.50.1   | vue-v3.2.47      | react-v18.2.0    | angular-v15.0.1  |
|--------------------------------------------|------------------|------------------|------------------|------------------|
| Memory usage after page load.              | 0.7  <br>(1.03)  | 0.9  <br>(1.38)  | 1.1  <br>(1.73)  | 1.6  <br>(2.47)  |
| Memory usage after adding 1,000 rows.      | 2.7  <br>(1.52)  | 3.8  <br>(2.09)  | 5.0  <br>(2.76)  | 4.7  <br>(2.61)  |
| Memory usage after adding 10,000 rows.     | 20.1  <br>(1.72) | 27.7  <br>(2.38) | 36.2  <br>(3.10) | 29.8  <br>(2.56) |
| geometric mean of all factors in the table | 1.39             | 1.90             | 2.46             | 2.55             |

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# Reactive Statements

the `$:` syntax

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# Transitions & Animations

---
layout: cover
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Skeleton](https://www.skeleton.dev/)

The UI toolkit for Svelte and Tailwind.

---
layout: cover
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Vitest](https://vitest.dev/)

Blazing Fast Unit Test Framework

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Vitest UI](https://vitest.dev/guide/ui.html)

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# [Testing Library](https://testing-library.com/)

testing without all the implementation details

- Tests only break when your app breaks, not implementation details
- Framework Agnostic

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# [fast-check](https://github.com/dubzzz/fast-check)

property based testing

---
layout: cover
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Vercel](https://www.vercel.com)

Develop. Preview. Ship

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Incremental Static Regeneration](https://vercel.com/docs/concepts/incremental-static-regeneration/overview)

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Vercel Image Optimization](https://vercel.com/docs/concepts/image-optimization)

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Vercel Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions)

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Vercel Edge Network](https://vercel.com/docs/concepts/edge-network/overview)

---
layout: cover
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# [Supabase](https://supabase.com/)

the open source Firebase alternative

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# Green IT - it's all about resources

- less code
- less memory
- smaller bundle size
- smaller sites
- better caches
- less cpu
- efficient & fast Developers 

---
layout: image-right
image: 'https://unsplash.com/photos/TNacNuuEl1o/download?force=true&w=1920'
---

# Alternatives

- [NEXT.js](https://nextjs.org)
- [Nuxt](https://nuxt.com/)
- [RAILS](https://rubyonrails.org/)
- [Remix](https://remix.run/)
- [SolidStart](https://start.solidjs.com)

---
layout: default
background: 'https://unsplash.com/photos/uAfZBP-GtiA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjgxOTcyOTk5&force=true&w=1920'
---

# Credits

- [SVELTE](https://svelte.dev/)
- [SVELTEKIT](https://kit.svelte.dev/)
- [Svelte Society](https://sveltesociety.dev/)
- [Learn Svelte](https://learn.svelte.dev/)
- [Vercel](https://vercel.com)
- [supabase - open source Firebase alternative](https://supabase.com/)
- [Why Svelte is more environmentally friendly](https://sustainablewww.org/principles/svelte-vs-react-vs-angular-why-svelte-is-more-environmental-friendly)
- [Skeleton - The UI toolkit for Svelte and Tailwind.](https://www.skeleton.dev/)
- [PokeAPI](https://pokeapi.co/)
- [YouTube @Huntabyte](https://www.youtube.com/@Huntabyte)
- [YouTube @jmagrippis](https://www.youtube.com/@jmagrippis)

---
layout: end
---

