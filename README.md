# 🎓 EduAgent — AI-Powered Academic Workspace

An all-in-one academic planner, study coach, and productivity assistant designed for university students and lifelong learners.

![React](https://img.shields.io/badge/React-19-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC)
![License](https://img.shields.io/badge/License-MIT-green)

## 🌟 Overview

EduAgent replaces fragmented student tools such as Notion, Google Calendar, Pomodoro apps, and Quizlet by bringing task management, daily routine scheduling, project breakdown, flashcards, quizzes, and an AI study coach into a single unified workspace.

## ✨ Features

- 📊 **Smart Dashboard:** Tracks pending deadlines, weekly study hours, course progress, and upcoming exams.
- ✅ **Task Management:** Organizes tasks by course, priority (High, Medium, Low), and status (To Do, In Progress, Done).
- 📅 **Daily Routine & Schedule:** Visual time-blocking for lectures, study sessions, and personal routines.
- 🎯 **Project-Based Learning (PBL):** Manages multi-phase academic projects with milestone timelines and AI-powered milestone breakdown.
- 🗓️ **Unified Calendar & Reminders:** Centralized assignment deadlines, daily routines, and reminder alerts.
- ⏱️ **Focus Mode:** Distraction-free Pomodoro timer with 25/5, 50/10, and deep-work presets.
- 🤖 **AI Study Coach:** On-demand concept tutor and assignment planner with academic-integrity guardrails.
- 📚 **Smart Flashcards & Quizzes:** Generates active-recall flashcards and multiple-choice practice quizzes from notes or topics.
- 📈 **Study Analytics:** Interactive charts comparing planned and actual study sessions.

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React 19, TypeScript, Tailwind CSS v4, Radix UI, Lucide Icons |
| Routing & SSR | TanStack Router, TanStack Start v1 |
| Data Fetching | TanStack Query v5 |
| Database & Authentication | PostgreSQL, Lovable Cloud, Row-Level Security (RLS), Social OAuth |
| AI Integration | Lovable AI Gateway (gpt-6-astra), OpenAI API fallback (gpt-4o-mini) |
| Data Visualization | Recharts, date-fns |
| Tooling & Testing | Vite, Bun, Vitest, Testing Library, ESLint, Prettier |

## 📂 Project Structure

```text
EduAgent/
├── src/
│   ├── components/
│   │   ├── edu/
│   │   │   ├── Workspace.tsx
│   │   │   ├── NewViews.tsx
│   │   │   └── StudyView.tsx
│   │   └── ui/
│   ├── lib/
│   │   ├── ai.functions.ts
│   │   ├── edu-store.ts
│   │   └── utils.ts
│   ├── routes/
│   │   ├── __root.tsx
│   │   ├── index.tsx
│   │   ├── auth.tsx
│   │   └── _authenticated/
│   │       └── app/
│   └── styles.css
├── public/
├── supabase/
├── drizzle/
├── package.json
├── bun.lock
├── vite.config.ts
├── vitest.config.ts
├── tsconfig.json
└── README.md
```

## 🚀 Installation & Setup

### Prerequisites
- Node.js
- Bun
- Git

### Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd EduAgent
```

### Install dependencies

```bash
bun install
```

### Configure environment variables

Create a `.env` file and configure the required database and AI API credentials.

**Important:** Never upload API keys, passwords, or secret environment variables to GitHub.

### Run the application

Check the scripts in `package.json` and run the appropriate development command.

## 🧪 Testing

The project uses:
- Vitest
- Testing Library
- ESLint
- Prettier

## 📊 Project Goals

EduAgent aims to simplify academic life by combining intelligent task management, AI-assisted learning, project planning, and productivity tracking into one platform.

## 📄 License

This project is licensed under the MIT License.
