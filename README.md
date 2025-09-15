# 💸 Full-Stack AI Finance Platform

A modern **AI-powered finance platform** built with:

* **Next.js 14 (App Router)**
* **Supabase** (database + auth)
* **Prisma** (ORM)
* **Inngest** (event-driven workflows)
* **ArcJet** (security & rate limiting)
* **Shadcn/UI + TailwindCSS** (UI & styling)

This project integrates **AI features** using Google **Gemini API**, while handling **auth, transactions, and automation** seamlessly. 🚀

---

## ⚡ Features

✅ Authentication with **Clerk**
✅ AI-powered finance insights (Gemini)
✅ Secure API & workflows with **ArcJet + Inngest**
✅ Scalable DB layer using **Supabase + Prisma**
✅ Beautiful UI with **Shadcn/UI + Tailwind**
✅ Email support with **Resend**

---

## 🛠️ Tech Stack

* **Frontend**: Next.js 14, React, TailwindCSS, Shadcn UI
* **Backend**: Supabase, Prisma, Inngest
* **Auth**: Clerk
* **AI**: Gemini API
* **Email**: Resend
* **Security**: ArcJet

---

## 📂 Getting Started

### 1️⃣ Clone the repo

```bash
git clone https://github.com/Tanay-Shah/ai-finance-platform.git
cd ai-finance-platform
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup environment variables

Create a `.env` file in the root directory and add:

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```

### 4️⃣ Run the app

```bash
npm run dev
```

App will be live at **[http://localhost:3000](http://localhost:3000)** 🎉

---

## 🚀 Roadmap

* [ ] Add budgeting & expense tracking
* [ ] Multi-user dashboards
* [ ] AI financial advisor with Gemini Pro
* [ ] Mobile-friendly responsive UI

---

## 📸 Screenshot

![Screenshot](https://github.com/user-attachments/assets/1bc50b85-b421-4122-8ba4-ae68b2b61432)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to add.

---

## 📜 License

MIT License – feel free to use and build upon this project.

---
