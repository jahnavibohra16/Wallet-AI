# 💰 Wallet AI – Smart Finance Management Platform

A modern full-stack AI-powered finance management platform that helps users securely track, manage, and visualize their financial data with real-time insights, budget alerts, and AI-assisted analytics.

## 🔧 Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS, ShadCN UI
- **Backend**: Node.js, Prisma, Supabase (PostgreSQL)
- **Authentication**: Clerk
- **AI Integration**: Gemini API (Google Generative AI)
- **Email Services**: Resend
- **Background Jobs & Cron**: Inngest
- **Rate Limiting & Bot Protection**: Arcjet

## 🚀 Features

- 🔐 User Authentication & Onboarding (Clerk)
- 🧠 AI-Powered Receipt Analysis
- 📊 Visualized Transactions Dashboard (Charts & Graphs)
- 🔁 Recurring Transaction Tracking
- 📅 Monthly Budget Alerts & Email Reports (via Inngest & Resend)
- 🛡️ Arcjet Shield for Rate Limiting & Bot Protection
- 📤 Deployed on **Vercel**

## 🛠️ Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/jahnavibohra16/Wallet-AI.git
   cd Wallet-AI
2. **Install dependencies**
   ```bash
   npm install --legacy-peer-deps
3. **Set up your .env file**
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

4. **Generate Prisma Client**
   ```bash
   npx prisma generate
5. **Apply Migrations**
   ```bash
   npx prisma migrate dev
6. **Run Development Server**
   ```bash
   npm run dev

## 👥 Collaborators
- Jahnavi Bohra

- Khushi Khada

- Manshi Kumawat

##💡 Wallet AI is a minor project built with a focus on modern web development practices and real-time finance solutions.
