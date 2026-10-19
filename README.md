### Finova — AI-Powered Financial Management Platform

> **Smart tracking. Intelligent insights. Total financial control.**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlebard&logoColor=white)
![Inngest](https://img.shields.io/badge/Inngest-000000?style=for-the-badge&logo=inngest&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white)
![Arcjet](https://img.shields.io/badge/Arcjet-F43F5E?style=for-the-badge&logo=security&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

Finova is a modern, full-stack **AI-powered financial management platform** designed to track expenses, manage budgets, and analyze spending habits seamlessly.

It translates complex financial logs and categorization data into clear, actionable advice for users asking one core question:

> **How can I optimize my spending and secure my financial future?**

---

## 💡 Overview & The Solution

Managing personal finances effectively requires more than just static spreadsheets. **Finova** bridges the gap by combining relational database storage with real-time AI insights, automated background event queues, and robust enterprise-grade security to deliver a complete financial workspace.

---

## 🛠️ Tech Stack & Architecture

- **Framework:** Next.js 15 (App Router), React, TypeScript
- **Styling & UI:** Tailwind CSS, Shadcn UI
- **Database & ORM:** Supabase PostgreSQL, Prisma ORM
- **Authentication & Security:** Clerk, Arcjet (Bot protection & rate limiting)
- **AI & Automation:** Google Gemini API, Inngest (Background workflows)
- **Communications:** Resend (Transactional emails)
- **Deployment:** Vercel

---

## 🔄 Complete System Workflow

The complete Finova workflow, from user authentication to AI-powered financial insights and database persistence:

```mermaid
flowchart TD

    A["👤 User / Client"] --> B["🛡️ Arcjet Security & Rate Limiting"]

    B --> C["🔐 Clerk Authentication"]

    C --> D["⚡ Next.js 15 App Router"]

    D --> E["📥 Transaction & Budget API Routes"]

    E --> F["⚡ Inngest Background Workflows"]

    F --> G["🤖 Google Gemini AI Engine"]

    G --> H["📊 Financial & Spending Analysis"]

    H --> I["🗄️ Prisma ORM"]

    I --> J["🌐 Supabase PostgreSQL Database"]

    J --> K["📧 Resend Email Alerts"]

    K --> L["🚀 Vercel Production Deployment"]

    L --> M["📈 Finova User Dashboard"]

```

```mermaid
flowchart TD
    A[User Inputs Transactions & Budgets] --> B[Finova Platform Processing]

    B --> C[Real-Time Visibility]
    B --> D[AI-Powered Insights]
    B --> E[Automated Notifications]
    B --> F[Secure Data & Rate Limiting]

    C --> G[Instant clarity on cash flow and categories]
    D --> H[Tailored financial advice and smart choices]
    E --> F1[Timely reports and alerts delivered to inbox]
    F --> I[Total peace of mind with enterprise security]

    G --> J[Ultimate Result: Complete Financial Freedom & Control]
    H --> J
    F1 --> J
    I --> J
```
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
