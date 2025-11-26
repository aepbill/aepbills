# AEP Bill Pay by Phone Site

A professional, SEO-optimized, phone-first site for American Electric Power (AEP) customers in Ohio, Texas, Indiana, Kentucky, Oklahoma, West Virginia, Virginia, Tennessee, Arkansas, Louisiana, and Michigan. Instantly pay your AEP electric bill, start or stop service, request arrangements, get account lookup, and more — all through the dedicated phone number **877-218-4132**. No web forms, no redirections.

---

## 🚀 Project Features

- Modern, accessible UI (blue/gold glass theme, responsive, mobile-first)
- Zero external links or redirects — all CTAs are click-to-call with `tel:8772184132`
- Premium floating "CALL" button on all layouts
- >2500 words of content, packed with local/state/intent keywords for leading Google rankings
- Mega-FAQs, how-tos, state guides, blogs, and step-by-step service flows
- JSON-LD FAQPage, Organization, and WebSite schema for Google rich results
- Fully responsive for desktop, tablet, and mobile devices

---

## 📁 Repository Structure

```plaintext
/
├── index.html        # Main landing page (all content, UI, schema, CTA float)
├── README.md         # Project description and publishing guide
├── snippets.html     # (Optional) Sample HTML/SEO snippets and reusable FAQ Schema blocks
├── sitemap.xml       # SEO: Sitemap for Google/Bing
├── robots.txt        # SEO: Allow all bots, list sitemap
├── .github/
│   └── workflows/
│       └── pages.yml  # Optional: GitHub Pages Actions workflow
```

---

## 🛠 Publishing on GitHub Pages

1. **Clone or Fork** this repository to your own GitHub account.

2. **Go to Repository Settings**  
   - Scroll to the "Pages" section.
   - Set the source branch to `main` (or your default branch), directory to `/root`.
   - Save.

3. **Visit your published site:**  
   `https://YOUR-USERNAME.github.io/aep-bill-pay/`

4. Updates to `index.html` (and any other root files) will auto-publish to your GitHub Pages site within 1–2 minutes.

---

## 🤩 Snippets and Embeddables

**Meta/SEO block:**
```html
<title>AEP Bill Pay by Phone | Pay Instantly | Start/Stop Service | 24/7 Support 877-218-4132</title>
<meta name="description" content="Pay your AEP electric bill by phone, arrange payment help, start/stop electric service and get support — all via 877-218-4132 covering Ohio, Texas, Indiana, and more." />
```

**Call to Action button:**
```html
<a href="tel:8772184132" class="cta-glow">Call 877-218-4132 – Pay, Start/Stop, Arrangement</a>
```

**FAQ Schema JSON-LD:**
```html
<script type="application/ld+json">
{
  "@context":"https://schema.org",
  "@type":"FAQPage",
  "mainEntity": [
    {
      "@type":"Question",
      "name":"How do I pay my AEP electric bill by phone?",
      "acceptedAnswer": {
        "@type":"Answer",
        "text":"Call 877-218-4132 and pay instantly via card, e-check, or arrangement. 24/7. No web forms."
      }
    }
    // ...more Question/Answer pairs
  ]
}
</script>
```

**Floating call button:**
```html
<a href="tel:8772184132" class="call-float-cta">☎ Call 877-218-4132</a>
```

---

## 🤖 robots.txt

```ini name=robots.txt
User-agent: *
Allow: /
Sitemap: https://YOUR-USERNAME.github.io/aep-bill-pay/sitemap.xml
```

---

## 🗺 sitemap.xml

```xml name=sitemap.xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://YOUR-USERNAME.github.io/aep-bill-pay/</loc>
    <priority>1.0</priority>
  </url>
</urlset>
```

---

## 🏷️ License & Disclaimer

This project is an independent resource for AEP customers.  
Not affiliated with or endorsed by American Electric Power (AEP) or its subsidiaries.  
All custom content copyright 2025.

---

## ✨ Pro Tips

- **For more Google impressions, tweak headlines and `<h2>` content with local/state/city intent phrases.**
- **Further split out pages if your user base grows, but always ensure every CTA points to `tel:877-218-4132` for maximum click-to-call conversions.**
- **Use provided JSON-LD and meta blocks for SEO best results.**

---

**Need a CSS split-out, favicon, or image asset guidance? Ask at any time!**