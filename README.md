# 🌌 NovaAI – Your Personal AI Task Assistant

NovaAI is your intelligent productivity sidekick. Seamlessly integrated with your Google Calendar, Email, and Task Manager, NovaAI automates your daily routines using natural language and AI intelligence. Whether it's scheduling meetings, replying to emails, or prioritizing your tasks, NovaAI has you covered.

---

## ⚡ Features

- 🧠 **AI-Powered Task Suggestions** – Understands your tasks and recommends smart actions.
- 🗓️ **Calendar Sync** – Automatically schedules meetings and avoids conflicts.
- 📧 **Smart Email Replies** – Summarizes and drafts context-aware replies using GPT-4.
- 📊 **Productivity Dashboard** – Visualize and optimize your daily focus and workload.
- 🔔 **Reminders & Notifications** – Never miss a deadline again.
- 🎯 **Focus Mode** – Pomodoro timers + auto task locking for deep work.

---

## 🧰 Tech Stack

| Layer        | Tech Used                           |
|--------------|-------------------------------------|
| Frontend     | React, TypeScript, Tailwind CSS     |
| Backend      | Node.js, Express, TypeScript        |
| Database     | MongoDB + Mongoose                  |
| AI Integration | OpenAI GPT-4                      |
| Auth         | Google OAuth2                       |
| DevOps       | Vite, Prettier, ESLint              |

---

## 📦 Project Structure

```bash
novaai/
├── src/
│   ├── backend/              # Express.js backend (API routes, services)
│   ├── frontend/             # React UI (pages, components, hooks)
│   └── common/               # Shared TypeScript types and constants
├── public/                   # Static files
├── .github/ISSUE_TEMPLATE/   # Community issue templates
├── .env.example              # Environment variable sample
├── README.md                 # This file
├── LICENSE                   # MIT License
└── package.json
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Praison-Labs/novaai.git
cd novaai
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create your `.env` file

```bash
cp .env.example .env
```

Fill in your OpenAI API Key, Google credentials, and MongoDB URI.

### 4. Start the app

```bash
npm run dev
```

---

## 📸 Screenshots

| 📋 Task Assistant                  | 📊 Dashboard                              |
| ---------------------------------- | ----------------------------------------- |
| ![task](./assets/task-ai-demo.gif) | ![dashboard](./assets/dashboard-demo.png) |

---

## 🔮 Planned Features

* 🗣️ Voice Command Support (via Whisper)
* 🤖 Slack Integration
* 📚 Notion Sync
* 🧑‍🤝‍🧑 Team Collaboration
* 📱 Mobile Version

---

## 🧪 Tests

```bash
npm run test
```

> Unit tests use Jest and React Testing Library.

---

## 🙋 FAQ

**Q: Is NovaAI free to use?**
A: NovaAI is currently in a private beta phase. Stay tuned for early access.

**Q: Does this work with Outlook?**
A: Outlook and iCal support are planned in v2.0.

---

## 📄 License

This project is licensed under the **MIT License**. See [`LICENSE`](./LICENSE) for more information.

---

## 💬 Connect

* 🔗 [LinkedIn](https://linkedin.com/in/yourusername)
* 🐦 [Twitter](https://twitter.com/yourhandle)
* 🌐 [Portfolio](https://yourwebsite.com)

---

> Made with 🧠 + ☕ by [@yourusername](https://github.com/yourusername)
