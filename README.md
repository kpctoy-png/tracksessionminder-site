# tracksessionminder.com

The Track Session Minder website (made by Redline Techniques LLC). Plain HTML and CSS, served by GitHub Pages from `main`.

- Pages: `index.html`, `features.html`, `plans.html`, `faq.html`, `about.html`, `support.html`, `privacy.html`
- Styles: `style.css` (Gulf livery: light blue #9DC9EC, orange #F26A21, navy #16325C)
- `privacy.html` mirrors the app's privacy policy (`src/components/PrivacyPolicy.tsx` in the app repo). Update both together.
- `CNAME` sets the custom domain.
- SEO: each page's `<head>` has its own title, description, canonical URL, Open Graph/Twitter tags (share image `img/og-image.png`) and JSON-LD structured data (`faq.html` carries `FAQPage` data built from its questions, so update it when the FAQ changes). Add any new page to `sitemap.xml`. `404.html` is the not-found page.
