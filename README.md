# FinSmart.ai

AI-powered personal finance platform for modern users. Track expenses, manage budgets, scan receipts, and gain actionable insights with advanced analytics and automation.

---

## 🚀 Features

- **Advanced Analytics**: AI-powered insights into your spending patterns.
- **Smart Receipt Scanner**: Extracts data from receipts using Google Gemini AI.
- **Budget Planning**: Create/manage budgets with intelligent recommendations.
- **Multi-Account Support**: Manage multiple accounts and credit cards.
- **Multi-Currency**: Real-time conversion and support for various currencies.
- **Automated Insights**: Automated financial recommendations.
- **Recurring Transactions**: Automated handling and reminders for recurring expenses/income.
- **Email Alerts**: Budget alerts and monthly reports via email.
- **Secure Authentication**: Powered by Clerk.
- **Modern UI**: Built with Tailwind CSS, shadcn/ui, and Radix UI.

---

## 🛠️ Tech Stack

- **Framework**: Next.js 15 (App Router, Server Actions)
- **Database**: PostgreSQL (via Prisma ORM)
- **Authentication**: Clerk
- **AI**: Google Generative AI (Gemini)
- **Background Jobs**: Inngest
- **Security/Rate Limiting**: Arcjet
- **Email**: Resend
- **UI**: Tailwind CSS, shadcn/ui, Radix UI, Lucide Icons

---


## ⚡ Getting Started

### 1. Clone & Install

```bash
git clone <repo-url>
cd FinSmart.ai
npm install
```

### 2. Environment Variables

Create a `.env` file in the root with:

```env
DATABASE_URL=
DIRECT_URL=
CLERK_SECRET_KEY=
CLERK_PUBLISHABLE_KEY=
ARCJET_KEY=
GEMINI_API_KEY=
RESEND_API_KEY=
```

### 3. Database Setup

```bash
npx prisma migrate deploy # or npx prisma migrate dev
npx prisma generate
```


### 4. Run the App

```bash
npm run dev
```

App runs at [http://localhost:3000](http://localhost:3000)

---
