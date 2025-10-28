# 🧠 TruthGuard — AI for Fake News Checking

## 📘 Overview
**TruthGuard** is an AI-powered web application that helps users identify misinformation and fake news.  
It analyzes text claims, evaluates sources, and generates credibility scores — empowering people to verify facts quickly and reliably.

Built using **React**, **TypeScript**, **Vite**, and **Tailwind CSS** for speed, scalability, and responsive design.

---

## 🚀 Features
- 📰 **Claim Verification** — Analyze and validate textual claims.  
- 🔍 **Source Analysis** — Check credibility of referenced sources.  
- 📊 **AI Credibility Scoring** — Automatically score reliability.  
- 🎨 **Modern UI** — Built with Tailwind CSS and shadcn/ui components.  
- ⚡ **Optimized Build** — Powered by Vite for ultra-fast performance.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React + TypeScript |
| Styling | Tailwind CSS, shadcn/ui |
| Build Tool | Vite |
| ORM / Config | Drizzle ORM setup |
| Hosting | GitHub Pages / Vercel / Netlify |

---

## 📂 Folder Structure

TruthGuard/

├── client/

│ ├── public/ # Static assets (icons, images)

│ ├── src/

│ │ ├── components/ # UI and feature components

│ │ ├── App.tsx # Main React component

│ │ └── main.tsx # App entry

│ ├── index.html # HTML entry

│ ├── package.json # Dependencies and scripts

│ ├── tailwind.config.ts # Tailwind setup

│ └── vite.config.ts # Vite configuration

├── design_guidelines.md

├── drizzle.config.ts

└── tsconfig.json

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
``bash
git clone https://github.com/<your-username>/TruthGuard.git
cd TruthGuard/client

2️⃣ Install dependencies
npm install

3️⃣ Run the app locally
npm run dev
