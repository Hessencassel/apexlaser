# Apex Laser Cleaning — Website

Professional marketing website for Apex Laser Cleaning, Fort Wayne's premier
laser surface restoration service. Built for Netlify + GitHub deployment.

---

## Files

```
/
├── index.html      Main single-page website
├── success.html    Form submission thank-you page
├── netlify.toml    Netlify build + redirect config
└── README.md       This file
```

---

## Deploy to Netlify via GitHub

1. Push this folder to a new GitHub repository
   ```
   git init
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

2. Log in to [netlify.com](https://netlify.com) → **Add new site** → **Import from Git**

3. Select your GitHub repo. Netlify will auto-detect `netlify.toml`.

4. Click **Deploy site**. Your site will be live in under a minute at a free
   `*.netlify.app` subdomain.

5. When you have a custom domain, go to **Domain management** in Netlify and
   add it there. Netlify provides free HTTPS automatically.

---

## Netlify Forms (Quote Requests)

The quote form uses Netlify Forms — no backend required. Submissions go
straight to your Netlify dashboard under **Forms → quote-request**.

To get email notifications for every submission:
- Netlify Dashboard → **Forms** → **quote-request** → **Form notifications**
- Add your email address

---

## Customizing the Site

Search for these placeholder values and replace them with your real info:

| Placeholder              | What to replace with                       |
|--------------------------|--------------------------------------------|
| `APEX<span>LASER</span>` | Your actual business name / brand          |
| `(260) 555-0100`         | Your real phone number                     |
| `info@apexlaserfw.com`   | Your real email address                    |
| `apexlaserfw.com`        | Your actual domain once purchased          |
| `© 2026 Apex Laser...`   | Your business name in the footer           |

---

## Recommended Domain Names

These are strong, brandable options to check availability on
[Namecheap](https://namecheap.com) or [Cloudflare Registrar](https://cloudflare.com/products/registrar/):

### Top Picks
| Domain                          | Why It Works                                |
|---------------------------------|---------------------------------------------|
| `apexlaserfw.com`               | Short, professional, Fort Wayne coded       |
| `apexlasercleaning.com`         | Descriptive, strong for SEO                 |
| `fwlasercleaning.com`           | Fort Wayne local — great for local SEO      |
| `fortwaynelasercleaning.com`    | Full city name — maximum local SEO value    |
| `lasercleanfw.com`              | Short and punchy                            |

### Alternative Brand Names (if you rename the business)
| Domain                          | Suggested Brand Name                        |
|---------------------------------|---------------------------------------------|
| `beamcleanfw.com`               | Beam Clean FW                               |
| `precisionlaserfw.com`          | Precision Laser FW                          |
| `forgelaserclean.com`           | Forge Laser Cleaning                        |
| `ironbeamcleaning.com`          | Iron Beam Cleaning                          |

**Tip:** If the `.com` is taken, `.co` is the next best option for a service
business. Avoid `.net` or `.org` for commercial services.

**SEO tip:** A domain containing "fort wayne laser cleaning" will rank faster
for local Google searches because it matches what people type.

---

## Local SEO Checklist (Do These After Launch)

- [ ] Create a **Google Business Profile** at google.com/business (free, critical)
- [ ] Submit to **Bing Places** (free, reaches a large audience)
- [ ] List on **Angi** and **Thumbtack** for lead generation
- [ ] Ask early customers to leave **Google Reviews** — this is the #1 local ranking factor
- [ ] Add your site to **Yelp** business listings
- [ ] Post before/after photos to Google Business Profile regularly

---

## Competitive Landscape (Research Summary)

Based on a search of the Fort Wayne area:

- **No dedicated laser cleaning businesses were found in Fort Wayne.**
  This is a first-mover opportunity in the market.

- **Competitors using traditional methods (not laser):**
  - Westfall Power Washing — chemical rust removal, power washing
  - Mid America Service Solutions — dry ice / sandblasting (not laser)
  - American Quality Body and Paint — traditional auto rust repair

- **Nearest laser competitors are outside Fort Wayne:**
  - Laser Blasting Pros — Indiana, 500W laser
  - Indy Laser Cleaning — Indianapolis-based, mobile service

**The positioning statement on the site ("Fort Wayne's only dedicated laser
cleaning service") is accurate based on current search results. Lead with this.**

---

## Tech Stack

- Pure HTML / CSS / vanilla JS — no frameworks, no build step
- Google Fonts (Bebas Neue, Inter, Space Mono)
- Netlify Forms for lead capture
- Fully responsive (mobile, tablet, desktop)
- Respects `prefers-reduced-motion` for accessibility
