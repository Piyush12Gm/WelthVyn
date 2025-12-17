# WelthVyn - AI-Powered Personal Finance Platform

WelthVyn is a modern, full-stack financial management application built with Next.js 15. It leverages AI to simplify expense tracking and provides robust tools for budgeting, account management, and automated transaction processing.

## 🚀 Features

-   **AI Receipt Scanning**: Automatically extract transaction details (amount, date, merchant, and category) from receipt images using Google Gemini AI.
-   **Comprehensive Dashboard**: Visualize your financial health with interactive charts and transaction overviews.
-   **Multi-Account Management**: Track balances across different account types like Savings and Current accounts.
-   **Smart Budgeting**: Set monthly budgets and receive alerts when you approach your spending limits.
-   **Recurring Transactions**: Automate your finances with support for daily, weekly, monthly, and yearly recurring transactions.
-   **Advanced Security**: Protected by ArcJet for rate limiting and bot protection, specifically for sensitive actions like transaction creation.
-   **Responsive Design**: Built with Tailwind CSS and Shadcn UI for a seamless experience across desktop and mobile.

## 🛠️ Tech Stack

-   **Framework**: [Next.js 15 (App Router)](https://nextjs.org/)
-   **Database**: [PostgreSQL](https://www.postgresql.org/) with [Prisma ORM](https://www.prisma.io/)
-   **Authentication**: [Clerk](https://clerk.com/)
-   **AI Engine**: [Google Gemini AI](https://ai.google.dev/)
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/) & [Shadcn UI](https://ui.shadcn.com/)
-   **Security**: [ArcJet](https://arcjet.com/)
-   **Workflow Automation**: [Inngest](https://www.inngest.com/)

## 📋 Prerequisites

Before you begin, ensure you have accounts and API keys for:
- Clerk (Authentication)
- Supabase or Neon (PostgreSQL Database)
- Google AI Studio (Gemini API)
- ArcJet (Security)
- Resend (Email Notifications)

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Piyush12Gm/welthvyn.git](https://github.com/Piyush12Gm/welthvyn.git)
   cd welthvyn
