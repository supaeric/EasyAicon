# EasyAircon — easyaircon.co.za

Lead-generation site for aircon supply, installation, repairs and regas. Durban first, South Africa on request.

## Stack
Single static HTML page. No build step, no dependencies, nothing to maintain.

## Files
- `index.html` — the entire site (HTML + CSS + JS in one file)
- `logo.png` — brand logo, transparent background (used in nav + footer)
- `favicon.png` / `apple-touch-icon.png` — browser tab + iPhone icons
- `og-image.jpg` — preview image when the link is shared on WhatsApp/social
- `robots.txt` / `sitemap.xml` — SEO

## Before going live (one thing left)
Open `index.html`, search for `YOUR_WEB3FORMS_KEY` and replace it with the
free access key from https://web3forms.com. Quote form submissions then
arrive as emails.

The WhatsApp number (+27 82 794 7084) is already wired in.

## Deploy on Vercel
1. Push this folder to a GitHub repository
2. In Vercel: Add New Project → Import the repo
3. Framework preset: **Other**. No build command, no output directory. Deploy.
4. Project → Settings → Domains → add `easyaircon.co.za` and follow the DNS steps

## After launch
- Add the site to Google Search Console and submit `sitemap.xml`
- Run the homepage through Google's Rich Results Test (FAQ + business schema)
- Create a free Google Business Profile for Durban — this wins the local map pack
