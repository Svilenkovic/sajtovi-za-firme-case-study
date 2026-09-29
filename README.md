# Sajtovi za firme

A Serbian and English guide to business websites, organised around what different industries actually need from a site.

**[sajtovizafirme.com](https://sajtovizafirme.com/)** · [Medica Centar case study](https://sajtovizafirme.com/en/medica-centar-case-study/) · [Srpski](README.sr.md)

> [!NOTE]
> This is an independent project by D. Svilenković. The production source stays in a private repository; this public repository documents the work.

<table>
  <tr><td><b>Type</b></td><td>Industry-led business website</td></tr>
  <tr><td><b>Languages</b></td><td>Serbian and English</td></tr>
  <tr><td><b>Public routes</b></td><td>36 canonical pages</td></tr>
  <tr><td><b>Role</b></td><td>Research, design, development, SEO, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>Astro, TypeScript, CSS, PHP 8.3, SQLite, nginx</td></tr>
</table>

## Purpose

A restaurant, clinic and B2B supplier do not need the same website. This project starts with the business model and the action a visitor should take, then maps the right pages, proof and contact path for that kind of company.

## Design direction

The interface is built as an anatomy lesson. Layers of a business site separate and reassemble while the reader scrolls, using a light surface with jade and coral accents.

## What I built

- Separate guidance for service firms, local businesses, shops and B2B companies
- Page architecture explained through visible content layers
- Serbian pages at the root and matching English pages under /en/
- An inquiry path tied to the visitor’s type of business
- Motion controls, a reduced-motion path and useful content without JavaScript

## Release checks

Every canonical route was checked at 390, 768, 1440 and 1920 px. The release was also tested without JavaScript and with reduced motion. Live checks covered HTTPS, redirects, response headers, structured data, sitemap files, protected paths and invalid contact requests without sending test mail.

These are engineering checks, not claims about search ranking or field performance.

---

<sub>Designed and built by [D. Svilenković](https://svilenkovic.com).</sub>
