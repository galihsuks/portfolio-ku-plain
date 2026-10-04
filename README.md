# Galih Sukmamukti Hidayatullah Portfolio

Static portfolio website for Galih Sukmamukti Hidayatullah, built with plain HTML and Tailwind CSS CDN.

This version is a lightweight clone of the original Next.js portfolio, focused on fast loading, clear recruiter-friendly content, and SEO readiness. The mini chat feature and multilingual setup were removed to keep the site simple and easy to deploy anywhere.

## Features

- Plain HTML single-page portfolio
- Tailwind CSS via CDN
- Responsive layout for desktop and mobile
- English-only content
- Recruiter-focused hero, skills, experience, projects, and contact sections
- SEO meta tags, Open Graph, Twitter card, canonical URL, and JSON-LD schema
- `robots.txt` and `sitemap.xml` included for search engine indexing
- No build step required

## Project Structure

```text
.
├── assets/
│   ├── fonts/
│   ├── img/
│   ├── LOGO.png
│   ├── my_photo.png
│   └── my_photo_meta.jpg
├── index.html
├── robots.txt
├── sitemap.xml
└── README.md
```

## Getting Started

Open `index.html` directly in a browser.

Because Tailwind is loaded from CDN, an internet connection is required for the styling to load correctly during local preview.

## Deployment

This project can be deployed to any static hosting service, such as:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Shared hosting with public HTML upload

After deployment, update these URLs if the production domain changes:

- Canonical URL in `index.html`
- Open Graph URL and image URL in `index.html`
- Twitter image URL in `index.html`
- `Sitemap` URL in `robots.txt`
- `<loc>` URL in `sitemap.xml`

## SEO Checklist

- Submit the production URL to Google Search Console
- Submit `https://your-domain.com/sitemap.xml`
- Make sure `robots.txt` is reachable at `https://your-domain.com/robots.txt`
- Test the page with Google Rich Results Test
- Test the preview card with social sharing debuggers
- Replace temporary/local URLs before indexing

## Contact

- Email: [galih8.4.2001@gmail.com](mailto:galih8.4.2001@gmail.com)
- GitHub: [galihsuks](https://github.com/galihsuks)
- Instagram: [galihsuks_](https://www.instagram.com/galihsuks_)
