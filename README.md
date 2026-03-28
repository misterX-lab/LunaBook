<div align="center">

```
 ██╗     ██╗   ██╗███╗   ██╗ █████╗ ██████╗  ██████╗  ██████╗ ██╗  ██╗
 ██║     ██║   ██║████╗  ██║██╔══██╗██╔══██╗██╔═══██╗██╔═══██╗██║ ██╔╝
 ██║     ██║   ██║██╔██╗ ██║███████║██████╔╝██║   ██║██║   ██║█████╔╝ 
 ██║     ██║   ██║██║╚██╗██║██╔══██║██╔══██╗██║   ██║██║   ██║██╔═██╗ 
 ███████╗╚██████╔╝██║ ╚████║██║  ██║██████╔╝╚██████╔╝╚██████╔╝██║  ██╗
 ╚══════╝ ╚═════╝ ╚═╝  ╚═══╝╚═╝  ╚═╝╚═════╝  ╚═════╝  ╚═════╝╚═╝  ╚═╝
```

### *A place as quiet as the moon. A space as deep as a book.*

<br/>

![Status](https://img.shields.io/badge/status-in%20development-6c63ff?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-c8a4d4?style=flat-square)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-8ecfb0?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-fullstack-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-frontend-000000?style=flat-square&logo=next.js&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-ready-5a0fc8?style=flat-square&logo=pwa&logoColor=white)

</div>

---

> [!NOTE]
> This README is a living document. As Lunabook evolves — features, stack decisions, and structure may change. Check back for updates, and feel free to open a Discussion if something looks outdated.

---

## 🌕 What is Lunabook?

> *In a world of endless noise, Lunabook is the quiet corner you've been looking for.*

Lunabook is a social network built around **long-form discussion** — a deliberate antidote to the shallow scroll culture of modern social media.

While most platforms optimize for short bursts of dopamine, Lunabook is designed for something rarer: **slow, thoughtful conversation**. The kind that makes you think. The kind that brings people genuinely closer.

Think of it as **Facebook × Reddit × iMessage × FaceTime** — but stripped of everything that makes those platforms exhausting.

---

## 🌙 Why Lunabook?

| The Problem | The Lunabook Way |
|---|---|
| Short posts make thinking shallow | Long-form only — no short posts, by design |
| "Likes" accelerate approval-seeking | Warm, soft reactions only (🌙 and friends) |
| Timelines are loud and relentless | Quiet threads. Read slowly. Think deeply. |
| Shallow ties with strangers | Private rooms for the people who actually matter |

---

## 🌿 Who is Lunabook for?

Lunabook is built for people who:

- 🌲 Love nature and find peace in the outdoors
- ✈️ Travel not for photos, but for experiences
- 🐾 Feel deeply connected to animals
- 💡 Think outside the expected
- 🤝 Have few friends — but deep, lasting bonds

*If you've ever felt like social media wasn't made for you, Lunabook was made for you.*

---

## 🛠️ Tech Stack

Lunabook is built **TypeScript end-to-end** — one language, full stack, zero context-switching.

```
┌──────────────────────────────────────────────────────────────┐
│                           CLIENT                             │
│     Next.js (App Router)  ·  Tailwind CSS  ·  shadcn/ui     │
│                  PWA  ·  Smart TV (partial)                  │
├──────────────────────────────────────────────────────────────┤
│                           SERVER                             │
│           Node.js + TypeScript  ·  NestJS / Express          │
├──────────────────────────────────────────────────────────────┤
│                          DATABASE                            │
│                  PostgreSQL  ·  Prisma ORM                   │
├──────────────────────────────────────────────────────────────┤
│                      REAL-TIME / CALLS                       │
│                 Jitsi Meet (embedded, OSS)                   │
└──────────────────────────────────────────────────────────────┘
```

| Layer | Technology |
|---|---|
| Language | TypeScript (frontend + backend) |
| Frontend | Next.js · Tailwind CSS · shadcn/ui |
| Backend | Node.js · NestJS *(or Express)* |
| Database | PostgreSQL · Prisma ORM |
| Calls | Jitsi Meet (open-source, embedded) |
| Platform | PWA · Browser-first · Smart TV (partial) |

---

## 📁 Project Structure

```
lunabook/
├── apps/
│   ├── web/          # Next.js frontend (App Router)
│   └── server/       # NestJS / Express backend
├── packages/
│   ├── ui/           # Shared shadcn/ui components
│   ├── db/           # Prisma schema & migrations
│   └── types/        # Shared TypeScript types
├── docs/             # Design docs & ADRs
└── README.md
```

> Monorepo structure recommended — e.g. [Turborepo](https://turbo.build/) or [Nx](https://nx.dev/).

---

## 🚀 Getting Started

### Prerequisites

- Node.js `>= 20`
- PostgreSQL
- pnpm *(recommended)*

### Setup

```bash
# 1. Clone the repository
git clone https://github.com/your-username/lunabook.git
cd lunabook

# 2. Install dependencies
pnpm install

# 3. Configure environment variables
cp .env.example .env
# → Edit .env with your database URL and secrets

# 4. Run database migrations
pnpm db:migrate

# 5. Start development servers
pnpm dev
```

The app will be available at `http://localhost:3000` 🌙

---

## 🤝 Contributing

Lunabook is in its earliest phase — and we'd love thoughtful contributors who resonate with the vision.

1. Fork this repository
2. Create your feature branch: `git checkout -b feature/your-idea`
3. Commit with a clear message: `git commit -m 'feat: describe your change'`
4. Push to the branch: `git push origin feature/your-idea`
5. Open a Pull Request

> **Before contributing**, please read [`CONTRIBUTING.md`](./CONTRIBUTING.md) *(coming soon)* and make sure your idea aligns with the core philosophy: **depth over speed, warmth over virality**.

---

## 🌙 Philosophy

> *"The moon doesn't rush. It simply rises, and the world grows quieter."*

Lunabook is not trying to compete with Twitter or Instagram. We're building something different — a space that trusts people to think slowly, speak carefully, and connect meaningfully.

---

## 📄 License

MIT © Lunabook Project

---

<div align="center">

🌙 *If this resonates with you — star the repo, open an issue, or just say hello.*

<br/>

**[⭐ Star](../../stargazers) · [🐛 Issues](../../issues) · [💬 Discussions](../../discussions)**

</div>
