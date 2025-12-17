# WelthVyn — AI-Powered Financial Intelligence Platform

WelthVyn is a sophisticated, full-stack personal finance management platform built with **Next.js 15**. It combines modern UI/UX, AI-driven insights, and automated backend workflows to help users gain complete control over their financial health.

---

## 🚀 Key Features

### 🧠 AI-Powered Insights
- **Smart Receipt Scanning**  
  Upload receipt images to automatically extract total amount, date, description, merchant name, and suggested category using **Google Gemini 1.5 Flash**.

- **Automated Financial Advisory**  
  Monthly AI-generated reports with actionable insights based on spending behavior and income-to-expense ratios.

---

### 📊 Comprehensive Financial Management
- **Multi-Account Tracking**  
  Manage multiple *Savings* and *Current* accounts with real-time balance updates.

- **Advanced Transaction Logging**  
  Detailed tracking of income and expenses with support for bulk deletion and custom categories.

- **Interactive Dashboard**  
  Dynamic charts, summaries, and budget progress indicators for real-time financial visibility.

---

### 🤖 Automation & Background Jobs
- **Recurring Transactions**  
  Supports Daily, Weekly, Monthly, and Yearly automated transactions with scheduled balance updates.

- **Smart Budget Alerts**  
  Spending is monitored every 6 hours. Automated email alerts are sent when users exceed 80% of their monthly budget.

- **Monthly Financial Reports**  
  Automatically generates and emails a detailed financial summary on the 1st of every month.

---

### 🛡️ Security & Performance
- **ArcJet Protection**  
  Implements advanced rate limiting and bot protection using token bucket algorithms.

- **Server Actions**  
  Secure and high-performance data mutations using Next.js Server Actions.

- **Optimistic UI**  
  Instant UI updates with background revalidation to ensure database consistency.

---

## 🛠️ Tech Stack
- **Framework:** Next.js 15 (App Router)
- **Database:** PostgreSQL
- **ORM:** Prisma
- **Authentication:** Clerk
- **AI Engine:** Google Generative AI (Gemini SDK)
- **Workflow Orchestration:** Inngest
- **Security:** ArcJet
- **Email Service:** Resend
- **Styling:** Tailwind CSS, Shadcn UI

---

## ⚙️ Environment Setup

Create a `.env` file in the root directory and add the following variables:

```env
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
