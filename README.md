# Hello LunaBook!
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
### *月のように静かで、本のように深い場所。*

<br/>

![Status](https://img.shields.io/badge/status-in%20development-6c63ff?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-c8a4d4?style=flat-square)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-8ecfb0?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-fullstack-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-frontend-000000?style=flat-square&logo=next.js&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-ready-5a0fc8?style=flat-square&logo=pwa&logoColor=white)

</div>

---

## 🌕 What is Lunabook?

> *In a world of endless noise, Lunabook is the quiet corner you've been looking for.*

Lunabook is a social network built around **long-form discussion** — a deliberate antidote to the shallow scroll culture of modern social media.

While most platforms optimize for short bursts of dopamine, Lunabook is designed for something rarer: **slow, thoughtful conversation**. The kind that makes you think. The kind that brings people genuinely closer.

Think of it as **Facebook × Reddit × iMessage × FaceTime** — but stripped of everything that makes those platforms exhausting.

---

## 🌙 Why Lunabook?

現代のSNSが抱える問題に、私たちは真剣に向き合っています。

| The Problem / 問題 | The Lunabook Way / Lunabookの答え |
|---|---|
| 短文投稿が思考を浅くする | 長文のみ。短文投稿は存在しない |
| 「いいね」が承認欲求を加速させる | 温もりのあるリアクションのみ（🌙など） |
| タイムラインが騒がしすぎる | 静かなスレッドで、深く・ゆっくり |
| 見知らぬ人との浅いつながり | プライベートルームで、本当の人たちと |

---

## ✨ Core Features / 主な機能

### 🪶 Quiet Threads — 静かなスレッド
Long-form discussions as the primary experience. Short replies and reaction spam are intentionally minimized. Every post is meant to be *read*, not just scrolled past.

長文でじっくり議論するためのメイン機能。短い返信やスタンプは意図的に最小限に。すべての投稿は「読まれるため」に存在します。

---

### 🏡 Private Rooms — プライベートルーム
Invite-only spaces for your real friends and family. Set a gentle theme — nature, travel, animals — and just... *be together*.

現実の友達や家族だけを招待できる完全閉鎖空間。自然、旅行、動物など、ゆるいテーマを設定して、ただ一緒にいられる場所。

---

### 🌙 Warmth Reactions — 温もり通知
No thumbs up. No fire emoji. Only soft, meaningful reactions — because some conversations deserve more than a tap.

「いいね」はありません。「この長文を読んで温かくなったよ」という気持ちだけを、月マークのような柔らかい絵文字で届けます。

---

### 📖 Memory Pages — 思い出のページ
Browse your past threads like turning pages of a cherished book. Every deep conversation, preserved.

過去の長文スレッドを、大切な本のページをめくるように振り返れる機能。

---

### 🌑 Luna Mode — 月読モード
At night, the UI softens. Notifications quiet down. The words take center stage.

夜になるとUIが暗く静かになり、長文が読みやすくなります。通知を抑えるオプション付き。

---

### 📹 Voice & Video Calls — 通話機能
Powered by **Jitsi Meet** (open-source), embedded natively in TypeScript. No third-party apps. No account walls. Just your people, on screen.

オープンソースの Jitsi Meet をTypeScriptでネイティブ埋め込み。アプリ不要・アカウント不要で、大切な人たちとすぐつながれます。

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

## 🛠️ Tech Stack / 技術スタック

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

## 📁 Project Structure / ディレクトリ構成

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

## 🚀 Getting Started / はじめかた

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

## 🤝 Contributing / コントリビュート

Lunabook is in its earliest phase — and we'd love thoughtful contributors who resonate with the vision.

このプロジェクトはまだ初期段階です。ビジョンに共感してくれる仲間を探しています。

1. Fork this repository
2. Create your feature branch: `git checkout -b feature/your-idea`
3. Commit with a clear message: `git commit -m 'feat: describe your change'`
4. Push to the branch: `git push origin feature/your-idea`
5. Open a Pull Request

> **Before contributing**, please read [`CONTRIBUTING.md`](./CONTRIBUTING.md) *(coming soon)* and make sure your idea aligns with the core philosophy: **depth over speed, warmth over virality**.

---

## 🌙 Philosophy / フィロソフィー

> *"The moon doesn't rush. It simply rises, and the world grows quieter."*
>
> 「月は急がない。ただ昇るだけで、世界は静かになる。」

Lunabook is not trying to compete with Twitter or Instagram. We're building something different — a space that trusts people to think slowly, speak carefully, and connect meaningfully.

Lunabookは、TwitterやInstagramと競うつもりはありません。ゆっくり考え、丁寧に言葉を選び、本当につながれる場所を作っています。

---

## 📄 License

MIT © Lunabook Project

---

<div align="center">

🌙 *If this resonates with you — star the repo, open an issue, or just say hello.*

*共感してくれたなら — スターを押して、Issueを開くか、気軽に声をかけてください。*

<br/>

**[⭐ Star](../../stargazers) · [🐛 Issues](../../issues) · [💬 Discussions](../../discussions)**

</div>
