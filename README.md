# Service Spectrum — Website Design & Management

Official website for **Service Spectrum**, a website design and management company.

**Live site:** deployed on [Render](https://render.com) as a static site.

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/serviceq8/service-spectrum-website)

## Structure

```
index.html      Home page (services, process, about, insights, contact)
privacy.html    Privacy Policy (required for Facebook Business verification)
terms.html      Terms of Service
css/style.css   All styles
js/main.js      Navigation, scroll animations, contact form
assets/         Logo and images
render.yaml     Render static-site configuration
```

## Deploying on Render

1. Push this repository to GitHub.
2. In the [Render dashboard](https://dashboard.render.com), click **New → Static Site**.
3. Connect the GitHub repository — Render auto-detects `render.yaml`.
4. Click **Create Static Site**. Every push to `main` redeploys automatically.

## Facebook Business verification

1. In **Meta Business Suite → Settings → Business verification**, choose to verify with your website domain.
2. Copy the verification meta tag code Meta gives you.
3. In `index.html`, find the commented `facebook-domain-verification` meta tag near the top, paste your code, uncomment it, and push — Render redeploys automatically.
4. The site already includes the business name, contact details, Privacy Policy, and Terms of Service pages Meta looks for.

## Contact details

- Email: abdullah@service-spectrum.com
- Phone / WhatsApp: +965 6560 5879

## Domain

The site's canonical domain is **https://service-spectrum.com** (set in canonical tags, Open Graph tags, structured data, robots.txt, and sitemap.xml). After deploying on Render, add `service-spectrum.com` as a custom domain in the Render dashboard (Settings → Custom Domains) and point the DNS records Render shows you at your registrar.
