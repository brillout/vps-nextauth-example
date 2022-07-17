# vps-nextauth-example
An advanced example of Vite Plugin SSR and NextAuth.js working together!

## Features & Specs
- Custom credentials.
- Custom register/login pages.
- Email verification.
- Front-end made with React and Material UI.
- JWT.
- MongoDB as a database for users.
- User status stored as binary flags to save space.
- 100% TypeScript.

## Missing
- Logout functionality (with temporary JWT blacklisting).
- OTP verification (email code, link).

## Get Started

1. Start the MongoDB deamon. See [mongodb.com > Install MongoDB Community Edition](https://www.mongodb.com/docs/manual/administration/install-community/).
2. Set the environment variables for your SMTP email server at `.env.example`.
3. Rename `.env.example` to `.env`.
   ```bash
   mv .env.example .env
   ```
4. Install npm dependencies and start the server.
   ```bash
   npm install
   npm run dev
   ```
