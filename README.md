# 🔥 HabitForge — Habit Tracking & Progress Dashboard

**Build habits. Forge consistency**

HabitForge is a web-based habit tracker designed to help users build consistent routines, monitor daily progress, and review their personal growth. It combines habit management, progress analytics, streak tracking, and cloud synchronization in a single interface.

## 🌟 Overview

HabitForge makes it easier to turn daily goals into consistent habits. Users can manage their routines, track completion, monitor streaks, and review their progress over time.

## ✨ Features

- **🔐 User Authentication** — Sign up and log in using Supabase Authentication.
- **☁️ Cloud Synchronization** — Store and synchronize tracker data through Supabase.
- **✅ Daily Habit Tracking** — Mark habits as completed and track daily consistency.
- **🔥 Streak Tracking** — Monitor current and longest habit streaks.
- **📊 Progress Analytics** — View completion scores and habit progress.
- **📅 Monthly History** — Review historical check-ins by date.
- **🗓️ Weekly Planner** — Organize routines and plan the week.
- **📝 Weekly Review** — Reflect on progress and consistency.
- **⚙️ Habit Management** — Add, edit, reorder, and delete habits.
- **💾 Persistent Data** — Keep user data available across sessions through the configured storage system.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS / Tailwind CSS | Styling and responsive interface |
| JavaScript | Application logic and interactions |
| Supabase | Authentication, database, and cloud synchronization |
| Chart.js | Progress visualization |

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- A configured Supabase project for authentication and cloud synchronization

### Supabase Configuration

HabitForge uses Supabase for authentication and cloud data storage.

To configure your own instance:

1. Create a project in [Supabase](https://supabase.com/).
2. Configure the required database table and authentication settings.
3. Set up appropriate Row Level Security (RLS) policies.
4. Configure the project URL and publishable key in the application.
5. Test signup, login, data persistence, and account isolation.

**Security:** Only use a Supabase publishable key in browser code. Never expose a `service_role` key, database password, or other privileged secret in a public repository. Ensure database policies restrict users to their own data.

## 🌐 Live Demo

**Live Website:** Add your deployed Vercel or GitHub Pages URL here.

**GitHub Repository:** `https://github.com/webpiyush156/HabitForge.git`


## 📁 Project Structure

```text
HabitForge/
├── index.html
└── README.md
```

The application is maintained as a single HTML file.

## 🔒 Data & Privacy

- Authentication is handled through Supabase.
- Cloud synchronization depends on the configured Supabase project.
- Database access should be protected using Row Level Security.
- Browser-side storage may be used for locally persisted tracker information.
- Do not commit private credentials or privileged API keys.

## 💡 What This Project Demonstrates

HabitForge provides practical experience with:

- Frontend web development
- JavaScript application logic
- Authentication integration
- Database connectivity and cloud synchronization
- Persistent user data
- Interactive dashboards and data visualization
- State management and user interface design

## 🔮 Future Improvements

Potential enhancements include:

- Habit reminders and notifications
- Custom habit categories and goals
- Exportable progress reports
- More detailed analytics
- Progressive Web App (PWA) support
- Accessibility and usability improvements

## 👨‍💻 Author

**Piyush Singh**

B.Tech Computer Science Engineering Student

Interested in software development, full-stack web technologies, and building practical web applications.



