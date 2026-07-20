# 📊 Acme Invoices Dashboard

A full-stack invoice management application built with Next.js, featuring database integration, secure authentication, and robust form validation.

🌐 **Live Demo on Vercel:** [dashboard-app-lilac-eight.vercel.app](https://vercel.app)

---

##  Tech Stack

- **Framework:** Next.js 15 (App Router)
- **Language:** TypeScript
- **Database:** PostgreSQL (Vercel Postgres)
- **Authentication:** NextAuth.js (Auth.js v5)
- **Validation:** Zod
- **Styling:** Tailwind CSS

---

##  Key Features

- **Secure Auth:** Login flow with server-side route protection and session management.
- **Full CRUD:** Create, read, update, and delete invoices directly in PostgreSQL.
- **Robust Validation:** Server and client-side form validation via Zod with accessible error states (`aria-live`).
- **Performance Optimizations:** On-demand cache revalidation (`revalidatePath`), optimized fonts/images, and client-side navigation.
- **Dynamic SEO:** Implemented global metadata layouts (`%s | Acme Dashboard`).

---

##  Demo Credentials

Use these public test credentials to explore the dashboard features:

- **Email:** `user@nextmail.com`
- **Password:** `123456`

---

##  Getting Started Locally

1. **Clone & Navigate:**
   ```bash
   git clone https://github.com
   cd dashboard-app/nextjs-dashboard
   ```

2. **Install Dependencies:**
   ```bash
   pnpm install
   ```

3. **Environment Variables:** Create a `.env.local` file at the root:
   ```env
   POSTGRES_URL=your_postgres_connection_string
   AUTH_SECRET=your_secret_generated_key
   ```

4. **Run Dev Server:**
   ```bash
   pnpm dev
   ```
   Open `http://localhost:3000` in your browser.
