This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.


# 🧠 DeepSeek AI App

DeepSeek is an AI-powered web application built with **Next.js**, **React**, **Tailwind CSS**, and **Clerk Authentication**.  
It allows users to interact with AI models in a clean and modern UI.

2. Install Dependencies
npm install

3. Setup Environment Variables

Create a .env.local file in the root of your project and add the following:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
CLERK_SECRET_KEY=your-clerk-secret-key
MONGODB_URI=your-mongodb-connection-string


(Make sure to replace with your actual keys.)

4. Run Development Server
npm run dev


Now open http://localhost:3000
 in your browser.

📦 Deployment

This project is deployed using Vercel
.

Push your code to GitHub.

Go to Vercel Dashboard
 → New Project.

Import your GitHub repository.

Add the same environment variables from .env.local to Vercel → Project Settings → Environment Variables.

Deploy 🚀

🛠️ Tech Stack

Next.js
 – React Framework

Tailwind CSS
 – Styling

Clerk
 – Authentication

MongoDB
 – Database

Vercel
 – Hosting
Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
