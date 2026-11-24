# Crypto Consultation Lead Generation Website

A lightweight, sub-second loading, high-converting single-page landing site and Thank You confirmation page designed for crypto advisory and beginner consultation campaigns.

## Key Features

- **Blazing Fast (<1s):** Semantic HTML5 + pure CSS with native system fonts and inline SVGs. Zero external framework overhead.
- **High-Trust Aesthetic:** Dark navy (`#0F172A`), white cards, gold (`#F59E0B`), and emerald green (`#16A34A`).
- **Direct Lead Capture:** FormSubmit integration delivering leads straight to `devienstatus@gmail.com` with zero backend server required.
- **Ad Network Ready:** Pre-configured compliance disclosures, risk notices, and non-leaking interactive modal dialogs for Bitmedia, Coinzilla, Google Ads, and Bing Ads.
- **Conversion Tracking:** Dedicated comment placeholder in `thank-you.html` for Bitmedia/Coinzilla conversion pixels.
- **Vercel Optimized:** Includes `vercel.json` for clean URLs (`/thank-you`), instant global CDN edge caching, and security headers.

## Project Structure

```
crypto-lead-gen/
├── index.html       # Main landing page with lead capture form
├── thank-you.html   # Post-submission confirmation & immediate call CTA
├── style.css        # Unified responsive stylesheet
├── vercel.json      # Vercel configuration (clean URLs & caching)
└── .gitignore       # Git ignore rules
```

## Deploying to Vercel

1. Push this repository to GitHub under your account or organization (e.g., `vibematez/<repo-name>`).
2. Log in to [Vercel](https://vercel.com).
3. Click **"Add New..."** -> **"Project"**.
4. Import your newly created GitHub repository.
5. Keep default settings (Framework Preset: **Other**) and click **Deploy**.
6. Your site will be live instantly on a secure `.vercel.app` domain with free SSL.
