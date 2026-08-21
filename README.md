<div align="center">

# SaaS Prokit

### The SaaS foundation your AI builds on.

**Org-first. AI-ready.** Better Auth, Prisma and Stripe on Next.js 16 or TanStack Start — wired, tested, and running on Cloudflare, Vercel or Docker the day you clone it.

[![Website](https://img.shields.io/badge/saasprokit.com-0B0B0B?style=for-the-badge&logo=googlechrome&logoColor=white)](https://saasprokit.com)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/sKBkUXsVuZ)
[![X](https://img.shields.io/badge/@luannguyenbkit-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/luannguyenbkit)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luannguyenbkit)

</div>

---

## 👋 I'm Luan Nguyen

I build the boring infrastructure so you don't have to.

Every multi-tenant B2B SaaS needs the same two weeks of work up front: organizations, invites, roles, 2FA, Stripe seats, transactional email, file uploads, a deploy pipeline. None of it is your product. All of it is required before your product can exist.

**SaaS Prokit** is that two weeks, already done — org-first from the first migration, not bolted on later.

> *Give indie developers and small teams the boring infrastructure, so the two weeks you would spend wiring auth and billing go into the one feature only you can build.*

---

## 📦 What's in the box

| | |
|---|---|
| **10** | shared packages |
| **28** | app routes — dashboard, auth flows, admin panel |
| **190+** | unit tests |
| **25** | Playwright e2e suites |
| **3** | deploy targets — Cloudflare, Vercel, Docker/AWS |

### Wired and tested on day one

- 🔐 **Authentication & 2FA** — Better Auth, sessions, password reset, TOTP
- 🏢 **Organizations** — multi-tenant from the schema up, invites, member management
- 🛡️ **Role-based access control** — permissions enforced server-side, not just hidden in the UI
- 💳 **Billing** — Stripe subscriptions, seats, webhooks, customer portal
- 📧 **Email** — transactional templates via Resend
- 📁 **File uploads** — validated, scoped to the org that owns them
- 🚀 **Deployment** — three targets, pre-configured, no "works on my machine"

---

## 🤖 Your coding agent already knows this codebase

The kit ships with **11 Claude Code skills** so your AI agent works from the codebase's own conventions instead of guessing at them.

| Plan | Code | Ship |
|---|---|---|
| `env-setup` | `auth` | `testing` |
| `routing` | `billing` | `deployment` |
| `data-access` | `forms` | |
| `conventions` | `tables` | |
| | `workflows` | |

Point an agent at a feature request and it already knows where data access lives, how forms are validated, and how to write the test.

---

## 🧱 Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js%2016-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack%20Start-EF4444?style=flat-square&logo=reactquery&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![Biome](https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=flat-square&logo=resend&logoColor=white)

---

## 💰 Buy the boilerplate once. Ship forever.

| Kit | Price | Status |
|---|---|---|
| **[Next.js · Better Auth Pro](https://saasprokit.com/multi-tenant-boilerplate-nextjs-better-auth)** | **$200** one-time | Available now |
| **[TanStack · Better Auth Pro](https://saasprokit.com/multi-tenant-boilerplate-tanstack-better-auth)** | **$200** one-time | Launching September 2026 |

Unlimited projects · lifetime updates · full source · agency and client work permitted · free setup and deploy support on [Discord](https://discord.gg/sKBkUXsVuZ).

**[→ Get the kit](https://saasprokit.com)** · [Changelog](https://saasprokit.com/multi-tenant-boilerplate-nextjs-better-auth/changelog) · [License](https://saasprokit.com/license)

<sub>Would rather it were already built? I also take on MVP builds — [get in touch](https://saasprokit.com/contact).</sub>

---

## 🔧 Open source

Things I've built in public along the way:

- **[turborepo-nextjs-prisma-postgres](https://github.com/luannguyenQV/turborepo-nextjs-prisma-postgres)** — a full forum: NestJS, Prisma, Auth.js, Postgres, shadcn/ui, Tailwind
- **[nestjs-hexagon-onion-ddd-boilerplate](https://github.com/luannguyenQV/nestjs-hexagon-onion-ddd-boilerplate)** — production NestJS with DDD, hexagonal/onion layering, CQRS
- **[strapi-press](https://github.com/luannguyenQV/strapi-press)** — headless blog on Strapi + Next.js + Turborepo
- **[coding-rules](https://github.com/luannguyenQV/coding-rules)** — the conventions I hold TypeScript, React, Next.js and NestJS code to
- **[react-collection](https://github.com/luannguyenQV/react-collection)** — shadcn, Zod, Yup, uploads and other patterns, isolated

---

## 📬 Say hi

Building something multi-tenant and stuck on the org model? I answer questions in [Discord](https://discord.gg/sKBkUXsVuZ) — no purchase needed.

**[saasprokit.com](https://saasprokit.com)** · [contact@saasprokit.com](mailto:contact@saasprokit.com) · [@luannguyenbkit](https://x.com/luannguyenbkit) · [LinkedIn](https://www.linkedin.com/in/luannguyenbkit)

<div align="center">
<sub>Ship the feature only you can build.</sub>
</div>
