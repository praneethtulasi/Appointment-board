**Appointment Board**

A simple, clean scheduling dashboard for keeping a team's appointments organized in one place. Built with Next.js, React, and Tailwind CSS.

**Features**
📅 View appointments grouped by date
➕ Add, edit, and cancel appointments
✅ Mark appointments as completed
🔍 Filter by date and status (scheduled / completed / cancelled)
⚠️ Prevents overlapping appointments on the same day
📊 Quick summary counts (total, scheduled, completed, cancelled)


**Tech Stack**
Next.js 16 (App Router, Turbopack)
React 19
TypeScript
Tailwind CSS 4
lucide-react for icons
Getting Started
Prerequisites
Node.js 18.18 or later
pnpm (recommended, since the project uses pnpm-lock.yaml)

Install pnpm if you don't have it:

bash
npm install -g pnpm
Installation
bash
pnpm install
Run the development server
bash
pnpm dev

Open http://localhost:3000 in your browser to view the app.

Build for production
bash
pnpm build
pnpm start
Project Structure
appointment-board/
├── app/
│   ├── page.tsx        # Main appointment board UI
│   ├── layout.tsx      # Root layout
│   └── globals.css     # Global styles
├── components/
│   └── ui/              # Reusable UI components
├── lib/
│   └── utils.ts         # Utility functions
└── public/               # Static assets
Notes

Appointments are currently stored in-memory for the session (no database yet), so data resets on page refresh.

License

This project is for personal/educational use.
