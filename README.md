# Full Stack AI Fianace Platform with Next JS, Supabase, Tailwind, Prisma, Inngest, ArcJet, Shadcn UI Tutorial 🔥🔥

# Finova 🚀 — AI-Powered Financial Management Platform

Finova is a modern, full-stack AI financial platform built with **Next.js 15**, **Prisma**, **Supabase**, **Clerk**, **Google Gemini AI**, **Resend**, and **Arcjet**. It helps users track transactions, manage budgets, analyze spending behavior, and receive personalized AI insights in real time.

---

## ✨ Features

- 🔐 **Authentication & Management:** Seamless sign-in, sign-up, and session security powered by **Clerk**.
- 📊 **Smart Dashboard:** Real-time summary of user finances, balance tracking, and expense categories.
- 🤖 **AI Insights:** Financial advisory and automated spending analysis powered by **Google Gemini API**.
- ⚡ **Background Processing:** Asynchronous event workflows and scheduled jobs managed through **Inngest**.
- 📧 **Transactional Emails:** Instant notifications and financial reports delivered via **Resend**.
- 🛡️ **Enterprise Security & Rate Limiting:** Application protection and bot mitigation using **Arcjet**.
- 🗄️ **Relational Database & ORM:** PostgreSQL database hosted on **Supabase** with **Prisma ORM**.

---

## 🛠️ Tech Stack

- **Framework:** [Next.js 15 (App Router)](https://nextjs.org/)
- **Language:** TypeScript
- **Styling:** Tailwind CSS, Shadcn UI
- **Database:** [Supabase PostgreSQL](https://supabase.com/)
- **ORM:** [Prisma](https://www.prisma.io/)
- **Authentication:** [Clerk](https://clerk.com/)
- **AI Engine:** [Google Gemini API](https://ai.google.dev/)
- **Background Jobs:** [Inngest](https://www.inngest.com/)
- **Email Service:** [Resend](https://resend.com/)
- **Security:** [Arcjet](https://arcjet.com/)
- **Hosting:** [Vercel](https://vercel.com/)

---

## 🚀 Quick Start & Local Setup

### Prerequisites

Ensure you have the following installed on your system:
- **Node.js** (v18 or higher)
- **npm**, **pnpm**, or **yarn**
- **Git**

---

### 1. Clone the Repository

```bash
git clone [https://github.com/Zishan-125/Finova.git](https://github.com/Zishan-125/Finova.git)
cd Finova
```
### Make sure to create a `.env` file with following variables -

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
