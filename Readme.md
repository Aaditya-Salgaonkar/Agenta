# 🚀 SaaS MVP Builder – AI-Powered Startup Generator

*Built by: Aaditya Salgaonkar*

---

## 🚀 Inspiration

Every year, thousands of startup dreams never see the light of day. Non-technical founders struggle to prototype. Developers drown in boilerplate.

Agenta was born from a bold vision:

> "What if anyone could turn a raw idea into a full-stack SaaS MVP — in minutes?"

As a solo founder, I set out to build this dream into reality. **Agenta empowers dreamers to become doers** — by removing the hardest part: writing all that code from scratch.

---

## ✨ What it does

Agenta is an **AI-powered SaaS MVP Generator.**

You give it your idea. It gives you a fully working codebase with:

* 📂 Real project folder structure
* 🧠 Smart, AI-picked features
* 🔐 Auth-ready (Supabase)
* ⚙️ Backend API routes
* 🖼️ Frontend UI (Next.js + Tailwind + Shadcn)
* 🧪 No fake logic. Real working code

And all of this happens in real time, streamed file-by-file with a beautiful progress bar.

Once done, you can preview, manage, or download your ready-to-run ZIP — the entire SaaS MVP.

---

## ⚙️ Features

✅ **AI-Powered Code Generator** – Built using GPT-4, Claude, and Mistral 8x7B via OpenRouter. Generates real, structured code.
✅ **Live Streaming via SSE** – Watch your code being written, file-by-file — live.
✅ **Auth-Ready & Scalable** – Supabase-based auth with login, signup, sessions.
✅ **Prompt-Preserving Engine** – Retains your raw startup idea in model prompts.
✅ **Smart Feature Picking** – CRUD, dashboards, chats, blogs, uploads, and more.
✅ **Instant Zip Download** – Get the full project zipped and ready to deploy.
✅ **Modern UI Design** – Dark mode UI with Tailwind, Shadcn, Framer Motion.
✅ **MVP Manager Dashboard** – Preview and manage all generated MVPs in one place.

---

## 💡 The Problem We're Solving

Every year, thousands of startup ideas die young — not because they're bad ideas, but because founders lack the technical skills or resources to execute.

* Hiring developers is expensive
* Building MVPs takes weeks (or months)
* No-code tools are limited or require technical know-how

The startup ecosystem has a massive **execution gap.**

---

## 💪 How I built it

**Stack:**

* Express.js — Backend controller + streaming logic
* Next.js App Router — Modern frontend with server components
* Supabase — Auth & MVP metadata
* OpenRouter — GPT-4, Claude, Mistral
* SSE — File streaming (Server-Sent Events)
* Tailwind + Shadcn + Framer Motion — UI
* TypeScript — Strict typing across full-stack

**Architecture:**

1. User submits a startup idea
2. AI selects features + generates code, file by file
3. Each file is streamed in real-time via SSE
4. All files are zipped and stored
5. Supabase stores prompt + metadata
6. Frontend displays progress + lets users download ZIP

---

## 🧷 Challenges I ran into

* ⚡ Handling file streaming + zip compression simultaneously
* 📡 Creating real-time SSE streaming with synced animations
* 🧪 Ensuring clean, bug-free, complete file output
* 🔀 Preserving user formatting while sending detailed prompts
* 🔍 Mapping user intent → features → clean code

---

## 🏆 Accomplishments I’m proud of

* 📅 Built the full-stack platform — solo
* 📡 Real-time, live code generation with SSE
* 💎 Premium dark-themed UI with animations
* 🔐 Supabase-based auth, metadata logging, secure downloads
* 💯 All output code is real, no placeholders

---

## 📚 What I learned

* Real-time streaming (SSE) from backend to frontend
* Prompt engineering across GPT-4, Claude, and Mistral
* File output management with live UI sync
* Premium UX with Tailwind + Framer Motion
* AI-first full-stack architecture patterns

---

## 🔮 What’s next for Agenta

* 🧠 **AI Lab** – tweak model parameters, stacks, features
* 📈 **Investor Dashboard** – auto-generate lean canvas & pitch snippets
* 🚀 **1-Click Deploy** – Supabase, Vercel, or Railway
* 💪 **In-App Editor with AI Suggestions** – inline improvements
* 🌐 **Template Marketplace** – share & remix MVP templates
* 🔝 **Collab Prompting + Sharing** – build MVPs together in real-time

Agenta exists so that no founder’s vision ever dies due to a lack of code.
**Let’s give everyone the power to launch.**

---

## ⚙️ Tech Stack

| Layer           | Stack                                                         |
| --------------- | ------------------------------------------------------------- |
| Frontend        | Next.js 14 (App Router, Server Components)                    |
| Backend         | Node.js + Express                                             |
| Database & Auth | Supabase (PostgreSQL, Auth, Storage)                          |
| AI Models       | GPT-4, Claude, Mistral 8x7B via OpenRouter + Gemini 1.5 Flash |
| Styling         | TailwindCSS + Shadcn + Framer Motion                          |
| Deployment      | GitHub API + Netlify API                                      |
| Hosting         | Vercel (Frontend) + Render (Backend)                          |

---

## 🛠️ Setup Instructions

### Prerequisites

* Node.js 18+
* Supabase project (Auth + DB)
* OpenRouter API key
* Gemini API key (Google Cloud)
* GitHub & Netlify personal access tokens

### Clone Repository

```bash
git clone https://github.com/Aaditya-Salgaonkar/hack-the-vibe-platform.git
cd hack-the-vibe-platform
```

### 🌐 Environment Variables

Create a `.env` file:

```env
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_anon_key
OPENROUTER_API_KEY=your_openrouter_key
GEMINI_API_KEY=your_gemini_key
GITHUB_TOKEN=your_github_token
NETLIFY_TOKEN=your_netlify_token
```

### 🧪 Run Backend

```bash
cd backend
npm install
npm run dev  # http://localhost:5000
```

### 🎨 Run Frontend

```bash
cd frontend
npm install
npm run dev  # http://localhost:3000
```

## 🌍 Live Deployment

* 🔗 Frontend: [agenta-aaditya-salgaonkar-maximally.vercel.app](https://agenta-aaditya-salgaonkar-maximally.vercel.app)
* 🔗 Backend: [agenta-aaditya-salgaonkar-maximally.onrender.com](https://agenta-aaditya-salgaonkar-maximally.onrender.com)

---

## 👨‍💻 Author

**Aaditya Salgaonkar**
Full Stack Engineer | Goa, India 🇮🇳
📧 [aadityasalgaonkar@gmail.com](mailto:aadityasalgaonkar@gmail.com)

---

## 📄 License

MIT License — for hackathon and educational purposes.

---

## 🙏 Acknowledgements

* Supabase
* OpenRouter
* Google Gemini API
* Netlify
* GitHub
