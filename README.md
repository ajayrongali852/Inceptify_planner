# Inceptify Planner — Collaborative Workspace & Document Manager

A modern, real-time, Notion-style collaborative workspace and document planner. Built with **Next.js 15 (App Router)**, **Convex** for real-time reactivity, **Clerk** for authentication, **BlockNote** for block-based rich text editing, and **EdgeStore** for media management.

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-Realtime_Backend-orange?style=for-the-badge)
![Clerk](https://img.shields.io/badge/Clerk-Authentication-blue?style=for-the-badge)

---

## 🌟 Key Features

- 📝 **Notion-Style Block Editor**: Powered by BlockNote with headings, checklists, code blocks, lists, and dynamic formatting.
- ⚡ **Real-Time Database & Sync**: Powered by Convex with optimistic mutations and reactive queries for instant multi-tab updates.
- 📁 **Infinite Hierarchical Documents**: Create nested documents, sub-pages, and organize notes dynamically.
- 🗑️ **Soft Delete & Trash Recovery**: Archiving system with document restore and permanent deletion.
- 🔒 **Enterprise Authentication**: User sign-in, sign-up, session management, and organization switching via Clerk.
- 🖼️ **Image & Cover Management**: Custom document icons and cover photo uploads powered by EdgeStore.
- 🌗 **Light & Dark Mode**: Seamless theme toggling with persistent user preference.
- 🔍 **Fuzzy Command Palette Search**: Quick navigation across all documents using cmdk.
- 🌐 **Publish & Share**: Publish documents publicly with read-only previews.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) (Turbopack, App Router, Server/Client components)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & [shadcn/ui](https://ui.shadcn.com/)
- **Backend / Database**: [Convex](https://www.convex.dev/) (real-time reactive data layer)
- **Auth**: [Clerk](https://clerk.com/)
- **Editor**: [BlockNote](https://www.blocknotejs.org/)
- **File Storage**: [EdgeStore](https://edgestore.dev/)
- **State Management**: [Zustand](https://zustand-demo.pmnd.rs/)

---

## 🚀 Getting Started

### 1. Prerequisites
- Node.js (v18.17+ or v20+)
- npm or pnpm or yarn

### 2. Clone and Install
`ash
git clone https://github.com/ajayrongali852/Inceptify_planner.git
cd Inceptify_planner
npm install
`

### 3. Environment Variables
Create a .env.local file in the root directory:

`env
# Convex
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# EdgeStore
EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
`

### 4. Run Locally
`ash
# Start Convex dev backend
npx convex dev

# In another terminal, start the Next.js dev server
npm run dev
`

Open [http://localhost:3000](http://localhost:3000) to view the application.

---

## 👨‍💻 Author

**Ajay Rongali**  
GitHub: [@ajayrongali852](https://github.com/ajayrongali852)
