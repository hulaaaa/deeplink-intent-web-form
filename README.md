# UPI Payment Page

Ready to deploy to [Vercel](https://vercel.com).

### Structure
- `index.html` — Payment page with the "Pay" button and your UPI deep link:
  `upi://pay?ver=01&mode=01&pa=boim-412814491325@boi&pn=MSWIPE&tr=&cu=INR`
- `vercel.json` — Vercel configuration

### Deploy to Vercel

#### Option 1: Via Vercel CLI
```bash
npx vercel
```
Follow the interactive prompts to link and deploy.

#### Option 2: Via GitHub / Vercel Dashboard
1. Push this folder to a GitHub repository.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository.
3. Click **Deploy**.
