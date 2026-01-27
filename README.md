# StreamVerse Trailers – Modern Movie & TV Show Explorer
[Live Demo](https://movie-trailer-eight-indol.vercel.app/)

<div align="center">

## Desktop Experience

<table>
  <tr>
    <th align="center">🎬 StreamVerse — Movie & TV Explorer</th>
    <th align="center">🛒 E-Commerce Platform</th>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/2b7b801d-5dc9-4f60-a9b4-7cd1581dce68" width="420"/><br/>
      <img src="https://github.com/user-attachments/assets/c94da68e-6128-456d-8a49-c009f0f1d73e" width="420"/><br/>
      <img src="https://github.com/user-attachments/assets/f72d7251-3145-462b-a34a-3301e16120b5" width="420"/><br/>
      <img src="https://github.com/user-attachments/assets/d635f737-6183-4254-b711-5e0fe95f3d89" width="420"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/d3617004-350a-4c5e-8a78-708b06b1a2ae" width="420"/><br/>
      <img src="https://github.com/user-attachments/assets/50f4d78a-1f4c-4534-9b69-370db6e5944a" width="420"/><br/>
      <img src="https://github.com/user-attachments/assets/a5e5f7ac-dd2b-42bf-9d81-7b1b30302f82" width="420"/><br/>
      <img src="https://github.com/user-attachments/assets/5e732451-66e9-4934-a097-f17245979ae2" width="420"/>
    </td>
  </tr>
</table>




## Mobile Experience

<div style="display:flex; gap:16px; justify-content:center; overflow-x:auto;">
  <img width="260" src="https://github.com/user-attachments/assets/8bba34b0-ba0e-4a2c-a996-3b8dc10aaa3c"/>
  <img width="260" src="https://github.com/user-attachments/assets/228c0746-b5b0-45d8-9796-f101fa02570b"/>
  <img width="260" src="https://github.com/user-attachments/assets/8eb86711-ca80-45d1-bd89-5830a9f6aa0e"/>
</div>


</div>

# 🛍️ E-commerce Store — Modern React Storefront

**Live Demo:** https://ecommerce-store-hazel-rho.vercel.app/  
**Tech:** React 18 • TypeScript • Tailwind CSS • Redux Toolkit • Vite • Vercel

A fully responsive **modern e-commerce frontend** built with React and the latest frontend stack.  
This project demonstrates real-world UI/UX patterns, global state management, performance optimizations, and scalable frontend architecture suitable for production use.

---

## 🚀 Key Features

### 🧠 Core Functionality
- 🛒 Product catalog with dynamic product listing
- 🔍 Search and filter support
- 📦 Add to cart / Remove from cart
- 🧾 Cart summary with item count and total price
- 🛠️ Global state management with Redux Toolkit
- 📱 Fully responsive layout (desktop & mobile)

---

## 🧠 Advanced Architecture & Implementation Details

- 🎨 **Theme switching via Clerk**  
  Dark / Light theme toggle is implemented **through Clerk** using a **custom Account Page**, fully integrated with the global UI theme state.

- 🔐 **Custom Clerk Account Page**  
  Authentication is handled via Clerk with a **customized account page**, allowing extended control over user settings and UI behavior.

- 🔁 **Redux Toolkit with async thunks**  
  Global state management is built with **Redux Toolkit**, including:
  - async logic using `createAsyncThunk`
  - centralized loading and error handling
  - predictable and scalable state architecture

- ⚡ **Lazy loading & code splitting**  
  Route-level **lazy loading** is implemented in `App.tsx` using:
  - `React.lazy`
  - `Suspense`  
  This improves initial load performance and reduces bundle size.

- 🗂️ **Feature-based folder structure**  
  The application follows a **feature-based architecture**, where logic, Redux slices, and UI are grouped by domain, making the codebase scalable and easy to maintain.

---

## 🧱 What This Project Demonstrates

- Real-world React application architecture
- Strict TypeScript usage for type safety
- Redux Toolkit with async thunks
- Authentication and user management with Clerk
- Custom account page & theme handling via auth layer
- Performance optimization via lazy-loaded routes
- Feature-based project structure
- Fully responsive UI built with Tailwind CSS

---

## 📦 Tech Stack

| Category | Technology |
|----------|------------|
| Frontend | React 18 |
| Language | TypeScript |
| Styling | Tailwind CSS |
| State | Redux Toolkit |
| Tooling | Vite |
| Deployment | Vercel |

This stack ensures a **performant, maintainable, and scalable** frontend application.


<div align="center">

#  <strong>StreamVerse</strong>

**Universal details page** • **Official YouTube trailers** • **Netflix-style rows** • **Clerk Authentication**

A lightning-fast, cinematic movie & TV explorer built with **React 18 + Vite + TypeScript + Tailwind CSS**

[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![Clerk](https://img.shields.io/badge/Clerk-Authentication-5B2DFF?style=for-the-badge&logo=clerk&logoColor=white)](https://clerk.com)

</div>

**A fast, responsive movie & TV show explorer with a universal details page, official YouTube trailers in full-screen modal, Netflix-style navigation, and real user authentication via Clerk — built with modern React + TypeScript.**

### Key Features 

- **Universal Details Page**  
  Works perfectly for both movies and TV series — media type auto-detected from the TMDB ID.

- **Official YouTube Trailer** — Sleek full-screen immersive modal  
  Highest quality, zero distractions.

- **Fully Responsive Design** — Looks stunning everywhere  
  Mobile • Tablet • Desktop — pixel-perfect on every screen.

- **Smart & Bulletproof UX**  
  Beautiful loading states, rock-solid error handling, graceful fallbacks — no blank pages of death.

- **Netflix-Style Navigation**  
  Horizontal scrollable rows with buttery-smooth scrolling and dynamic ← → arrows.

- **Your Personal Watchlist**  
  Save and manage favorites.

- **Production-Ready Authentication by Clerk**  
  • One-click sign-in with Google 
  • Magic Links 

- **Integrated Search** — Right in the NavBar  
  Find anything instantly, always one click away.

### Tech Stack — Modern, Fast, Future-Proof

| Category         | Technology                      | Why It Rocks                                                   |
|------------------|---------------------------------|----------------------------------------------------------------|
| Frontend         | **React 18 + Vite**             | Lightning-fast dev server & optimized production builds        |
| Routing          | **React Router v6**             | Declarative, modern client-side routing                       |
| State            | **Redux Toolkit**               | Predictable state management for search, watchlist & loading  |
| Authentication   | **Clerk**                       | Production-ready auth in minutes    
| Data Fetching    | **Axios**                       | Lightweight, interceptors-powered HTTP client                  |
| Styling          | **Tailwind CSS**                | Utility-first, rapid, consistent & fully responsive           |
| API              | **TMDB API**                    | The richest, most reliable movie & TV data source              |
| Icons            | **Heroicons + react-icons/fa**  | Clean SVG arrows + elegant solid Font Awesome icons            |
| Deployment       | **Vercel**                      | Push to GitHub → instant edge-network production ⚡️          |

### Architecture Highlights 
- Full migration to **strict-mode TypeScript** (noImplicitAny, etc.) — bulletproof code
- Universal API helpers + safe fallbacks — app never crashes
- **Clerk authentication** — 10,000 monthly active users free forever
- Clean, performant, and ridiculously maintainable codebase

