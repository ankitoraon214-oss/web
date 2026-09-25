# Auraflow AI

Premium one-page marketing site for an AI receptionist agency serving HVAC, med-spa, and dental businesses.

## Run locally

```bash
npm install
npm run dev
```

Then open http://localhost:3000

## Deploy on Vercel

Import this project into Vercel and deploy with the default Next.js settings. No environment variables are required for the current browser-based receptionist demo.

## Important

The Gemini API key supplied during setup was intentionally not written into the client code. Rotate/revoke that key because API keys shared in chat should be treated as exposed. If Gemini is added later, keep the key server-side in a Vercel environment variable.

## Retell

If you connect Retell for the live phone receptionist, add your production website domain to Retell's allowed domains/CORS configuration as required by your Retell setup. Keep localhost allowed during development if the Retell widget needs it.
