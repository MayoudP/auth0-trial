# auth0-trial

Trial app using Okta and the Auth0 solution
Quick PoC using auth0 Login

## Running Locally

Use the included setup script to create your `.env` file:

```bash
pnpm db:setup
```

Then, run the database migrations and seed the database with emails and folders:

```bash
pnpm db:migrate
pnpm db:seed
```

Finally, run the Next.js development server:

```bash
pnpm dev
```
