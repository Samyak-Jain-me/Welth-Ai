# Wealth – AI-Powered Finance Management Platform

A full-stack platform to track income, expenses, and budgets across multi-account, multi-currency setups.

### 🚀 Tech Stack
**Next.js**, **Tailwind CSS**, **Prisma**, **Gemini AI**, **Shadcn UI**, **Clerk**, **Inngest**, **Arcjet**, **Vercel**

---

### 💡 Key Features

- Built **AI-powered receipt scanner** with smart transaction categorization and filtering.  
- Automated **recurring transactions** and **monthly report generation** using Inngest cron jobs.  
- Developed a **dynamic budget system** with real-time email alerts and spend tracking.  
- Delivered **personalized, AI-generated financial insights** and reports via email.  
- Implemented **secure authentication** and **bot protection** with Clerk and Arcjet Shield.  
- Designed a fully **responsive, modern UI** using Shadcn UI and deployed on Vercel.

---

### 🛠️ Environment Variables

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
