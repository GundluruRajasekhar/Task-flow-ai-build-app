# TaskFlow AI

**AI-Powered Project & Task Management Platform**
Full Stack Development Internship — Innovation Hacks, Task 4

TaskFlow AI brings together the frontend, API, backend, and database built across Tasks 1–3 into one deployed platform for managing projects and tasks, with an AI assistant built into the task-creation workflow.

## 🎥 Demo Video

📺 **[Watch the narrated demo](#)** ← replace with your Loom/YouTube link once recorded

> A narrated walkthrough player is included at [`index.html`](./index.html) — open it, click **Play narrated demo**, and screen-record it (with system audio) to produce this video. See "Recording the demo" below.

## ✨ Features

- **Authentication** — register, log in, log out, protected routes
- **Dashboard** — project overview, task statistics, progress tracking, recent activity
- **Project management** — create, edit, delete, view project details
- **Task management** — create, assign, update status, set priority and due dates, search, filter
- **AI feature — Natural Language Task Creation** — type a task in plain English (e.g. *"Ask Priya to fix the login bug by Friday, high priority"*) and the AI parses it into a structured task (title, assignee, due date, priority) for you to confirm

## 🛠️ Tech Stack

> Fill in with what you actually used from Tasks 1–3.

| Layer | Technology |
|---|---|
| Frontend | _e.g. React_ |
| Backend / API | _e.g. Node.js + Express_ |
| Database | _e.g. MongoDB / PostgreSQL_ |
| AI | _e.g. OpenAI / Anthropic API_ |
| Auth | _e.g. JWT_ |
| Deployment | _e.g. Vercel + Render_ |

## 📂 Project Structure

```
.
├── index.html         # Narrated demo player (also usable as a static landing/demo page)
├── README.md          # This file
├── REQUIREMENTS.md    # Full functional & non-functional requirements
├── TASKS.md           # Build checklist / task breakdown
├── client/            # Frontend app
├── server/            # Backend API
└── ...
```

## 🚀 Getting Started

```bash
# clone
git clone <your-repo-url>
cd taskflow-ai

# install
npm install

# environment
cp .env.example .env
# fill in DB connection string, JWT secret, AI API key

# run
npm run dev
```

## 🔑 Environment Variables

```
DATABASE_URL=
JWT_SECRET=
AI_API_KEY=
```

## 📹 Recording the Demo

1. Open `index.html` in Chrome.
2. Start a screen recorder that captures system audio (Loom is easiest — free and gives you a shareable link).
3. Click **Play narrated demo** and let it run through all scenes.
4. Upload the recording to Loom or YouTube (unlisted), or drop the `.mp4` into a GitHub issue/PR comment to get a hosted, playable link.
5. Paste the link at the top of this README.

## 📄 License

Built for educational purposes as part of the Innovation Hacks Full Stack Development Internship.
