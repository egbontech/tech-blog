# 📝 Production-Ready Blog Platform

<img width="1280" height="720" alt="blog-website (1)" src="https://github.com/user-attachments/assets/f26ec8bf-8915-4ed9-8264-922c42b6771c" />


A modern, **production-ready blog platform** built with **Next.js** using real-world patterns — not demo shortcuts.  
This project focuses on scalability, performance, and clean architecture.

---

## 🚀 Features

- ⚡ Next.js App Router
- 🧠 Prisma + PostgreSQL (production database setup)
- 🔐 Authentication (Google & GitHub)
- ✍️ Rich text editor for writing posts
- 🖼 Image uploads with Cloudinary
- 🔎 Search with debouncing
- 📄 Cursor-based pagination
- 🧵 React Query for client-side data fetching & mutations
- 🚫 No stale data (manual cache control)
- 🎨 Modern UI with Tailwind CSS
- 🌙 Dark-mode friendly design
- 🧱 Clean folder structure & reusable components

---

## 🛠 Tech Stack

| Category | Tools |
|--------|------|
| Framework | Next.js (App Router) |
| Styling | Tailwind CSS |
| Database | PostgreSQL |
| ORM | Prisma |
| Auth | Better Auth (Google & GitHub) |
| Data Fetching | React Query |
| Image Storage | Cloudinary |
| Editor | Jodit |
| State Management | Zustand |
| Language | TypeScript |

---

## 📂 Project Structure

```txt
src/
├── app/
│   ├── api/            # API routes
│   ├── articles/       # Blog pages
│   └── write/          # Create & edit posts
├── components/
│   ├── modal/
│   ├── posts/
│   └── ui/
├── custom-hooks/
├── services/
├── store/
├── lib/
└── types/
