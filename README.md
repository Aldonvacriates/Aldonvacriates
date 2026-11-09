# Aldo Herrera

### Full-Stack Engineer | TypeScript, React Native, Next.js, Python

I build and run production web and mobile products through my company, Aldo Website LLC: sites and apps for small-business clients in Utah and Mexico, plus products of my own. Coding Temple 2025 grad, bilingual in English and Spanish, and open to full-stack, mobile and AI engineering roles (remote, hybrid, or around Park City, UT).

---

### Live products

- **[Pawfect Strolls](https://www.pawfectstrolls.com)** (client): dog walking and pet sitting in Park City, UT. Marketing site plus a client portal with scheduling, GPS-tracked walks, Stripe payments and a Gemini chat assistant. React, Vite, Supabase, Stripe.
- **[Estación 33](https://www.estacion33.com)** (client): restaurant in Iguala, Guerrero, Mexico. Bilingual online ordering for delivery or pickup, table reservations and live order tracking over Supabase Realtime. Next.js 15, Supabase, MercadoPago.
- **Aldo's Toolkit** (own product): Expo app of dev and security tools, published on the [App Store](https://apps.apple.com/us/app/aldos-toolkit/id6781942185) and [Google Play](https://play.google.com/store/apps/details?id=xyz.aldowebsitellc.toolkit). React Native/Expo, Supabase.
- **[ventaslocales](https://www.ventaslocales.com)** (own product): Spanish-first local-business directory (search, map, deals, events, reviews) plus a micro-site builder that serves each business on its own subdomain. Next.js 16, Supabase, Tailwind CSS 4.
- **[Nuestra Fiesta](https://www.getnuestrafiesta.com)** (own product): bilingual party-planning PWA with guest RSVPs, a gift registry, a vendor directory and a Gemini planning assistant. React, Vite, Supabase.
- **[aldowebsitellc.com](https://aldowebsitellc.com)**: company site with services, a Stripe shop and a blog. Next.js 15, Supabase, Stripe.

Source for client and company products is private; happy to walk through the code in an interview.

---

### Field Force Contractor (team project)

[field-force-contractor](https://github.com/Aldonvacriates/field-force-contractor) is an offline-first field-service app for oil-services contractors, built by a Coding Temple Tech Residency team. React Native/Expo, TypeScript, Flask, SQLAlchemy, Postgres.

- 8 contributors and 448 commits from Mar 7 to May 12, 2026. Of the 63 pull requests merged on the team's private repo, I authored 20 and merged 29 (19 of them from teammates), more than anyone else on the team in both.
- Built the AI features (Flask blueprint and Expo screens): a chat assistant, inspection-report drafting and photo analysis that auto-flags high-severity tickets, all on one provider interface over Gemini, Anthropic and Ollama with retry and cross-provider fallback ([providers.py](https://github.com/Aldonvacriates/field-force-contractor/blob/main/backend/app/blueprints/ai/providers.py)).
- Built the offline photo outbox (on-device SQLite queue with client-generated UUIDs) and its Flask [upload route](https://github.com/Aldonvacriates/field-force-contractor/blob/main/backend/app/blueprints/photos/routes.py), which is idempotent on that UUID, re-encodes uploads to strip metadata and stores a SHA-256 content hash.
- Added the PPE checklist gate to the team's biometric, PIN and GPS start-task flow.

---

### Other public repos

- [mechanic-shop-api](https://github.com/Aldonvacriates/mechanic-shop-api): Flask REST API with role-scoped JWT, rate limiting and caching.
- [Ecommerce-Final](https://github.com/Aldonvacriates/Ecommerce-Final): React 19 + TypeScript storefront with Firebase Auth, React Query and GitHub Actions CI/CD.
- [task-manager-ts](https://github.com/Aldonvacriates/task-manager-ts): typed React task manager with Auth0-protected routes, zod and react-hook-form.
- [shayze](https://github.com/Aldonvacriates/shayze): concept site (demo content), a transport-booking front end built as a PWA.

---

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

---

### Currently

Studying for the eJPT and CompTIA Security+ certifications.

---

### Get in touch

[![Portfolio](https://img.shields.io/badge/Portfolio-FF6B35?style=for-the-badge&logo=googlechrome&logoColor=white)](https://aldowebsitellc.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aldoph)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aldo@aldowebsitellc.xyz)
[![Credential](https://img.shields.io/badge/Credential-1F2937?style=for-the-badge&logo=verified&logoColor=white)](https://www.credential.net/profile/aldowebsite/wallet)
