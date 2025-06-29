# Welth Finance Platform 💰

A modern finance platform that helps users manage wealth, track transactions, and engage with intelligent financial tools. Built with **Next.js**, **Prisma**, **Clerk**, and integrated AI + email services.

🌐 **Live Demo**: [welth-finance-platform-nine.vercel.app](https://welth-finance-platform-nine.vercel.app)

<img src="https://github.com/MayurRajRajput/welth_finance_platform/blob/main/public/home_page.png" alt="Homepage Screenshot" width="800" />

---

## 🧩 Tech Stack

- **Frontend**: Next.js 14 (App Router), TypeScript, Tailwind CSS
- **Backend**: Prisma ORM, PostgreSQL (or any SQL DB)
- **Authentication**: Clerk
- **AI Integration**: Google Gemini API
- **Email Service**: Resend
- **Payments/Finance**: Arcjet
- **Deployment**: Vercel

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/MayurRajRajput/welth_finance_platform.git
cd welth_finance_platform
```

### 2. Install dependencies
npm install

### 3. Set up environment variables
Create a .env file in the root directory and add:

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
🛠 You need valid API keys from Clerk, Gemini, Resend, and Arcjet

### 4. Run the development server
npm run dev
Navigate to http://localhost:3000

## 📁 Project Structure

├── app/              # App Router pages
├── components/       # Reusable UI components
├── data/             # Static/sample data
├── emails/           # Resend email templates
├── hooks/            # Custom React hooks
├── lib/              # Utility modules and helpers
├── prisma/           # Prisma schema and seed
└── public/           # Static assets

## 🔐 Authentication Flow
```
Sign Up & Sign In using Clerk
Onboarding after auth
Clerk session persists across components
```

## ✨ Features
```
🔐 Secure, role-based authentication with Clerk
📬 Transactional emails via Resend
🤖 AI-enhanced assistance via Gemini API
💳 Finance APIs via Arcjet
📊 Financial dashboard (live demo available)
🌈 Clean and responsive UI (Tailwind CSS)
```

## 🧑‍💻 Contributing
```
Fork the repository
Create your feature branch (git checkout -b feature/your-feature)
Commit your changes (git commit -m 'Add your feature')
Push to the branch (git push origin feature/your-feature)
Open a Pull Request
```

## 🙌 Acknowledgements
```
Clerk.dev
Prisma ORM
Vercel
Google Gemini
Resend
Arcjet
vbnet
```

## Let me know if you'd like to add badges, screenshots, or deployment instructions!
