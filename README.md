This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).


## Key Features

- **Authentication:** 💼 Support for Credential and OAuth authentication.
- **Authorization:** 🔒 Easily manage public and protected routes within the `app directory`.
- **Email Verification:** 📧 Verify user identities through email.
- **Password Reset:** 🔑 Streamline password resets by sending email password reset links.
- **Lucia + tRPC:** 🔄 Similar to NextAuth with tRPC, granting access to sessions and user information through tRPC procedures.
- **Stripe Payment:** 💳 Setup user subscriptions seamlessly with stripe.
- **Email template with react-email:** ✉️ Craft your email templates using React.
- **MySQL Database:** 🛢️ Utilize a MySQL database (Planetscale) set up using Drizzle for enhanced performance and type safety.
- **Database Migration:** 🚀 Included migration script to extend the database schema according to your project needs.

## Tech Stack

- [Next.js](https://nextjs.org)
- [Lucia](https://lucia-auth.com/)
- [tRPC](https://trpc.io)
- [Drizzle ORM](https://orm.drizzle.team/)
- [Planetscale](https://planetscale.com/)
- [Stripe](https://stripe.com/)
- [Tailwind CSS](https://tailwindcss.com)
- [Shadcn UI](https://ui.shadcn.com/)
- [React Hook Form](https://www.react-hook-form.com/)
- [React Email](https://react.email/)

## Getting Started

1. Clone this repository to your local machine.
2. Copy `.env.example` to `.env` and fill in the required environment variables.
3. Run `pnpm install` to install dependencies.
4. `(for node v18 or lower):` Uncomment polyfills for `webCrypto` in `src/lib/auth/index.ts`
5. Update app title, database prefix, and other parameters in the `src/lib/constants.ts` file.
6. Run `pnpm db:push` to push your schema to the database.
7. Execute `pnpm dev` to start the development server and enjoy!

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
