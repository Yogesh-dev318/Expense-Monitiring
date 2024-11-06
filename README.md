# Expense Tracker (Next.js, TypeScript, Neon & Clerk)

Application for tracking income and expenses. It uses Next.js with [Neon](https://fyi.neon.tech/traversy) to persist data and [Clerk](https://go.clerk.com/BsG2XQJ) for authentication.

[Watch The Tutorial](https://www.youtube.com/watch?v=I6DCo5RwHBE)

[Try Demo](https://traversydemos.dev)

<img width="655" alt="Screenshot 2024-11-06 at 11 22 08 PM" src="https://github.com/user-attachments/assets/d3bf0b03-fda8-48af-aeee-28e302462584">

## Usage

### Install dependencies:

```bash
npm install
```

### Add Environment Variables:

Rename the `.env.example` file to `.env.local` and add the following values:

- `DATABASE_URL`: Your db string from https://neon.tech
- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`: Your Clerk public frontend API key from https://dashboard.clerk.dev/settings/api-keys
- `CLERK_SECRET_KEY`: Your Clerk secret key from https://dashboard.clerk.dev/settings/api-keys

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
# Expense-Monitiring
# Expense-Monitiring
