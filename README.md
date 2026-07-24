<div align="center">

# Frontend Projects — React • Next.js • TypeScript

A collection of production-ready frontend projects built with **React, Next.js, TypeScript, and Tailwind CSS**, demonstrating real-world UI/UX, scalable architecture, and clean code practices.

🎬 **StreamVerse** — https://movie-trailer-eight-indol.vercel.app/
🛍️ **studio-store** — https://studio-store-psi.vercel.app/

</div>
---

<div align="center">

## 🎬 StreamVerse

**Movie & TV explorer** — trailers, cast, similar titles, and a personal watchlist

Built with **React 19 + Vite + TypeScript + Redux Toolkit + Tailwind CSS**

**Live demo:** https://movie-trailer-eight-indol.vercel.app/

[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Clerk](https://img.shields.io/badge/Clerk-Authentication-5B2DFF?style=for-the-badge&logo=clerk&logoColor=white)](https://clerk.com)

</div>

### What it does

A fast, responsive movie & TV discovery app powered by the TMDB API. Browse popular, upcoming, top-rated, and trending titles, watch official YouTube trailers, and build a personal watchlist — all behind real authentication.

### Key features

- **Universal details page** — one page handles both movies and TV shows, media type auto-detected from the route
- **Trailers in a compact popup** — click the trailer button on any card to watch without leaving the page; click the card itself to open the full details page
- **Trending, with Day/Week toggle** — a curated row plus a full browsable grid with infinite scroll, no page-reload feel when switching tabs
- **Similar titles** — every details page ends with a "More Like This" row pulled from TMDB's recommendation endpoint
- **Personal watchlist** — save favorites, persisted through Redux state
- **Real authentication** — sign-in via Clerk (Google, magic links)
- **Search** — built into the navbar, searches movies, TV shows, and people at once
- **Fully responsive** — works cleanly from small phones up to desktop, including touch-friendly controls where hover doesn't apply

### Tech stack

| Category | Technology |
|---|---|
| Frontend | React 19 + Vite |
| Language | TypeScript (strict mode) |
| Routing | React Router v7 |
| State | Redux Toolkit |
| Authentication | Clerk |
| Data fetching | Axios |
| Styling | Tailwind CSS |
| API | TMDB API |
| Icons | Heroicons + react-icons |
| Deployment | Vercel |

### Architecture notes

- Strict TypeScript throughout (`noImplicitAny` and friends) — no implicit `any` slipping through
- API layer split by resource (`api/movie`, `api/tv`, `api/search`, `api/trending`, …) with consistent error handling and safe fallbacks, so a failed request never crashes the UI
- Redux slices organized by feature (movies, TV, favorites, UI), with shared fields (cast, videos, similar titles) reused across both movie and TV detail views
- Infinite scroll implemented with `IntersectionObserver`, both for horizontal category rows and the vertical trending grid

---

<div align="center">

## 🛍️ studio-store

**Premium sports apparel store** — headless storefront on the Shopify Storefront API

Built with **Next.js 16 (App Router) + React 19 + TypeScript + Zustand + Tailwind CSS v4**

**Live demo:** https://studio-store-psi.vercel.app/

</div>

### What it does

A headless e-commerce storefront that pulls product and inventory data from Shopify's Storefront API through Next.js's App Router, rather than shipping a traditional Shopify theme.

### Tech stack

| Category | Technology |
|---|---|
| Framework | Next.js 16 (App Router) |
| Frontend | React 19 |
| Language | TypeScript |
| Commerce | Shopify Storefront API (via `@shopify/cli`) |
| Client state | Zustand |
| Styling | Tailwind CSS v4 |
| Theming | next-themes (dark/light mode) |
| Icons | lucide-react |
| Deployment | Vercel |

### Architecture notes

- Headless commerce — storefront and product data live in Shopify, the frontend is fully decoupled and built independently on Next.js
- App Router structure (`app/`, `components/`, `hooks/`, `lib/`, `types/`) — colocated by concern, typed end to end
