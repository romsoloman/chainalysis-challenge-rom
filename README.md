# 🧠 Crypto Threat Events Dashboard

A fullstack take-home assignment simulating a threat monitoring tool built with Next.js (Pages Router), React Query, and TypeScript.

---

## 🚀 Tech Stack

- [x] Next.js with Pages Router
- [x] TypeScript
- [x] React Query
- [x] API Routes (`/pages/api`)
- [x] Tailwind CSS (optional)
- [x] Zod + RHF (optional)
- [x] Cursor rules for consistent structure

---

## 📋 Features Checklist

### 🛠️ Project Setup

- [ ] Next.js scaffolded with TypeScript
- [ ] ESLint + Prettier configured
- [ ] Tailwind CSS installed
- [ ] Cursor Rules added (`.cursor/rules/`)

---

### 🧱 Backend – API Routes

- [ ] `GET /api/events` → Return list of events
- [ ] `GET /api/events/:id` → Return single event
- [ ] `POST /api/events/:id/resolve` → Mark event as resolved

---

### 💻 Frontend – Pages & Components

- [ ] `pages/dashboard.tsx` created
- [ ] EventCard component with title, description, status
- [ ] Loading & error states handled
- [ ] Click → opens Event Modal (or expands view)
- [ ] "Mark as resolved" button with optimistic update
- [ ] React Query hooks (`useEvents`, `useEvent`, `useResolveEvent`)

---

### 📦 Architecture & Logic

- [ ] Types (`TEvent`, `TEventResponse`, etc.)
- [ ] `src/services/` handles all fetch logic
- [ ] `src/hooks/` contains reusable logic
- [ ] `src/components/` has pure UI
- [ ] `src/types/` shared across app

---

### 🧪 Optional Bonus

- [ ] Add Event form using Zod + RHF
- [ ] Unit test one component using Jest + RTL
- [ ] Use optimistic update on mutation

---

## 📄 How to Run

```bash
npm install
npm run dev
```
