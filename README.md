<h1 align="center">Hi, I'm Najib Saab 👋</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=4000&pause=3000&color=14A0FF&background=FFFFFF00&width=820&center=true&vCenter=true&lines=Senior+Full-Stack+Engineer+%7C+5%2B+years+commercial+experience;TypeScript+%C2%B7+NestJS+%C2%B7+Go+%C2%B7+React+%C2%B7+Angular+%C2%B7+PostgreSQL;Cloud-native+%26+DevOps%3A+Docker+%C2%B7+Cloudflare+Workers+%C2%B7+AWS;Creator+of+njX+UI+%E2%80%94+CSS+component+library;Open+to+remote+collaboration+%F0%9F%8C%8D" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=njbSaab&style=flat-square&color=14a0ff" alt="Profile views" />
  <a href="https://github.com/njbSaab/njx-css-ui">
    <img src="https://img.shields.io/github/stars/njbSaab/njx-css-ui?style=flat-square&color=14a0ff&label=njX+UI+stars" alt="njX UI stars" />
  </a>
  <img src="https://img.shields.io/badge/Location-Kyiv%2C%20?style=flat-square" alt="Location" />
  <img src="https://img.shields.io/badge/Remote-OK-22c55e?style=flat-square" alt="Remote OK" />
</p>

---

## 👨‍💻 About Me

I'm **Najib Saab** — Senior Full-Stack Engineer from **Kyiv** with **5+ years** of commercial experience.
I own products end-to-end: architecture, backend APIs, databases, infrastructure, CI/CD, monitoring and the UI.
Over the last 3 years I've been building high-volume B2C platforms (iGaming / affiliate, sports data, subscription SaaS, lead-gen funnels) as the sole full-stack and DevOps owner.

- 🏗️ **Creator of [njX UI](https://njxui.dev)** — lightweight CSS component library, 25+ components, 9 themes, ~40KB, zero dependencies
- ⚙️ Backend: **NestJS** (Clean Architecture · CQRS · DDD) · **Go** (net/http, chi, pgx — high-concurrency services) · Hono Workers · Python (FastAPI, Django)
- 🖥️ Frontend: **React 19** · **Angular 15–20** (OOP + FSD, SSR) · Svelte 5 · Astro (SSR / SSG) · PWA 
- 🗄️ Data: **PostgreSQL** (pgvector, jsonb, advisory locks) · MySQL / MariaDB · Redis · MongoDB · Cloudflare D1 · Prisma · TypeORM · Drizzle · pgx
- 🔁 Queues & caching: BullMQ · Cloudflare Queues · PostgreSQL job queues (`SKIP LOCKED`) · Celery · two-tier caches · singleflight
- 🚀 DevOps: up to **5 production VDS from scratch** — Linux hardening, Nginx / Caddy, TLS, Docker, PM2, CI/CD, zero-downtime deploys · **AWS** (EC2, S3, Lambda) · **Cloudflare end-to-end** (DNS, proxy, email, Workers, D1, R2, Queues, Pages)
- 📈 Observability: Sentry · Grafana · Prometheus · Uptime Kuma · structured logging · Telegram ops alerts
- 🤖 AI: LLM pipelines via OpenRouter / Groq / Claude / Gemini · embeddings + pgvector · FastAPI AI microservices · agent automation
- 🛍️ Building a portfolio of **Shopify apps** on Cloudflare Workers (webhooks → queues → consumers, 600+ tests)
- 📍 Kyiv · Remote OK · 50+ projects · Full development cycle
- 📫 **hi@njxui.dev**
  
---

## 🎨 njX UI — My Open Source Project

<a href="https://njxui.dev">
  <img src="https://img.shields.io/badge/🌐%20Live%20Demo-njxui.dev-14a0ff?style=for-the-badge" alt="Live Demo" />
</a>
<a href="https://github.com/njbSaab/njx-css-ui">
  <img src="https://img.shields.io/badge/GitHub-njx--css--ui-181717?style=for-the-badge&logo=github" alt="GitHub" />
</a>
<a href="https://www.npmjs.com/package/njx-ui">
  <img src="https://img.shields.io/npm/v/njx-ui?style=for-the-badge&color=cb3837&label=npm" alt="npm" />
</a>

> **njX UI** is a lightweight CSS component library — 25+ components, 9 color themes, zero JavaScript dependencies, ~40KB minified. Drop one `<link>` tag and go.

<div align="center">
  <img src="https://raw.githubusercontent.com/njbSaab/njx-css-ui/main/img/gif/overview-1.gif" alt="njX UI — library overview" width="100%" />
</div>

```html
<!-- Latest version -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/njx-ui/css/style.min.css">
<script src="https://cdn.jsdelivr.net/npm/njx-ui/js/njx.js"></script>

<!-- Pinned version (recommended for production) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/njx-ui@1.0.4/css/style.min.css">
<script src="https://cdn.jsdelivr.net/npm/njx-ui@1.0.4/js/njx.js"></script>
```

---

## 🧩 What I've Built Recently

| Project | What it is | Stack |
|---|---|---|
| **Sports / Esports Events Hub** | Go microservice aggregating events & results from a data provider and serving partner feeds with grant-based access, two-tier cache, singleflight, advisory-locked jobs | Go 1.26 · chi · pgx · PostgreSQL 16 · Docker |
| **Seamless Registration Platform** | Single backend for 40+ landing pages: one-step partner registration, anti-fraud, multi-tenant mail service (OTP, 100k campaigns, drip chains) on PostgreSQL queues, Prometheus metrics | Go · Fastify · PostgreSQL · Drizzle · Angular 20 · Vue 3 |
| **Sports Predictions + AI Content Agent** | Real-time prediction platform (WebSocket, BullMQ) and an autonomous news agent with a 10-stage LLM quality funnel and pgvector dedup | NestJS 11 · Go · Python / FastAPI · pgvector · React 19 · Expo |
| **FreeSlot — Slots Catalog** | Self-populating catalog with AI recommendations and 5 languages; 2,800+ req/s, p95 ≈ 20–40 ms | NestJS · Django · PostgreSQL + pgvector · Redis · React 19 · Vue 3 |
| **Quiz-Funnel Platform** | Multi-brand lead-gen funnels: server-authoritative scoring, multi-tenant email chains, 38 KB gzip Svelte PWA, live DB migrations | NestJS 11 · Prisma · MySQL · BullMQ · Svelte 5 · Angular 18 |
| **Telegram SMM Platform** | 6 independent services (~19k LOC): bot, GraphQL API, admin, email microservice, landing generator, edge predictions API | NestJS · GraphQL · Angular · Astro / Vue · Bun · Cloudflare Workers + D1 |
| **Shopify Apps on Cloudflare** | 5 apps on one engine: HMAC webhooks → Queues → consumers, Bulk Operations sync, batched alerts, App Pricing billing | TypeScript · Hono · Workers · D1 · Queues · R2 · Vitest |

---

## 🛠️ Tech Stack

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,scss,tailwind,figma,js,ts,go,python,angular,react,nextjs,vue,svelte,astro,nodejs,nestjs,fastapi,django,graphql,postgresql,mysql,redis,prisma,docker,nginx,cloudflare,aws,github,githubactions&theme=dark" alt="Tech Stack" />
  </a>
</p>

---

## 📊 GitHub Stats

<table>
  <tr>
    <td colspan="2">
      <img
        src="https://github-readme-activity-graph.vercel.app/graph?username=njbSaab&custom_title=Najib%27s%20Contribution%20Graph&theme=tokyo-night&hide_border=true&radius=8"
        alt="Contribution Graph"
        style="max-width:100%; display:block;"
      />
    </td>
  </tr>
</table>

---

## 🤝 Connect with Me

<p align="center">
  <a href="https://github.com/njbSaab" target="_blank">
    <img src="https://skillicons.dev/icons?i=github" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/nj-saab" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" />
  </a>
  <a href="mailto:sdr.expert@gmail.com">
    <img src="https://skillicons.dev/icons?i=gmail" alt="Email" />
  </a>
</p>

---

## 🔧 Who I am in code

```javascript
const najib = {
  name:       "Najib Saab",
  alias:      "nj / @Nj_Saab",
  location:   "Kyiv",
  remote:     true,
  role:       "Senior Full-Stack Engineer",
  experience: "5+ years commercial · 3 years owning systems end-to-end",
  projects:   "50+",

  openSource: {
    name:    "njX UI",
    type:    "CSS component library",
    stack:   ["Pure CSS", "CSS Variables", "9 themes", "~40KB"],
    url:     "https://njxui.dev",
  },

  backend: {
    primary: ["NestJS", "Clean Architecture", "CQRS", "DDD", "TypeScript"],
    go:      ["net/http", "chi", "pgx", "singleflight", "high-concurrency services"],
    also:    ["Fastify", "Hono", "Bun", "Python", "FastAPI", "Django"],
    api:     ["REST", "GraphQL", "WebSocket", "OpenAPI", "Microservices"],
    auth:    ["JWT", "OTP / passwordless", "OAuth2", "RBAC", "HMAC webhooks"],
  },

  frontend: {
    primary: ["React 19", "Next.js", "Angular", "OOP + FSD", "SSR"],
    also:    ["Vue 3", "Svelte 5", "Astro", "Expo / React Native"],
    state:   ["TanStack Query", "Zustand", "Redux", "NgRx", "RxJS", "Pinia"],
    css:     ["SCSS", "Tailwind", "njX UI"],
    targets: ["SPA", "PWA", "SSG landings", "Telegram Mini Apps"],
  },

  data: {
    relational: ["PostgreSQL", "pgvector", "MySQL / MariaDB"],
    nosql:      ["Redis", "MongoDB"],
    edge:       ["Cloudflare D1", "R2"],
    orm:        ["Prisma", "TypeORM", "Drizzle", "pgx"],
    queues:     ["BullMQ", "Cloudflare Queues", "PostgreSQL SKIP LOCKED", "Celery"],
  },

  devops: {
    servers:    ["up to 5 VDS from scratch", "Linux hardening", "Nginx / Caddy", "TLS"],
    containers: ["Docker", "Docker Compose", "PM2"],
    cloud:      ["Cloudflare Workers / D1 / R2 / Queues", "AWS EC2 / S3 / Lambda"],
    delivery:   ["GitHub Actions", "CI/CD", "zero-downtime deploys"],
    observe:    ["Sentry", "Grafana", "Prometheus", "Uptime Kuma"],
  },

  ai:        ["OpenRouter", "Groq", "Claude", "Gemini", "embeddings + pgvector", "LLM pipelines"],
  contact:   "sdr.expert@gmail.com",
};
```
