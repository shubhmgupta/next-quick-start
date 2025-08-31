# Next.js Fullstack Quick Start

This repository provides a ready-to-use Next.js fullstack project template with TypeScript, Tailwind CSS, NextAuth authentication, and Prisma, Drizzle ORM integration. Clone this repo to quickly start building your own fullstack application.

**Tailwind CSS is already installed and configured, so you can start building your UI immediately without worrying about setup or common installation errors.**

**You can easily implement theme switching using [next-theme](https://github.com/pacocoursey/next-themes) for dark/light mode support.**

---

## 💡 Features
- Pre-configured Tailwind CSS (no setup errors, ready to use)
- NextAuth authentication
- Prisma & Drizzle ORM integration
- TypeScript support
- Easily add theme switching with [next-theme](https://github.com/pacocoursey/next-themes)

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shubhmgupta/next-quick-start.git
   cd next-quick-start
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Set up environment variables:**
   - Copy `.env.example` to `.env.local` and update values as needed (e.g., database URL, NextAuth secrets).

4. **Set up the database (if using Prisma):**
   ```bash
   npx prisma migrate dev
   npx prisma generate
   ```

5. **Run the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

6. **Open [http://localhost:3000](http://localhost:3000) in your browser.**

---

## 📚 Learn More
- [Next.js Documentation](https://nextjs.org/docs)
- [Learn Next.js](https://nextjs.org/learn)
- [Next.js GitHub](https://github.com/vercel/next.js)

## ☁️ Deploy on Vercel

Deploy your Next.js app instantly using [Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

See [Next.js deployment docs](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
