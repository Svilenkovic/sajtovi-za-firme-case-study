<a href="https://sajtovizafirme.com/"><img src="media/cover.jpg" alt="Sajtovi za firme, home page on a laptop and a phone" width="100%"></a>

# Sajtovi za firme

A guide to what a business website must include, industry by industry, with every legal obligation linked to the article that sets it.

**[sajtovizafirme.com](https://sajtovizafirme.com/)** · [Case study (in Serbian)](https://svilenkovic.rs/radovi/sajtovi-za-firme) · [Srpski](README.sr.md)

> [!NOTE]
> My own project, not client work. The source code is private. This page describes what the site does and how it is built.

<table>
  <tr><td><b>Client</b></td><td>Own project</td></tr>
  <tr><td><b>Industry</b></td><td>Guide to business websites by industry</td></tr>
  <tr><td><b>Location</b></td><td>Serbia</td></tr>
  <tr><td><b>Type</b></td><td>Multi-page website</td></tr>
  <tr><td><b>My role</b></td><td>Research, design, development, SEO and hosting</td></tr>
  <tr><td><b>Stack</b></td><td>Astro 7, GSAP ScrollTrigger, Lenis, PHP 8.3, SQLite, nginx</td></tr>
</table>

## About the project

When I build a site for a business, the same questions come up every time: what a restaurant must say about allergens, whether a clinic may publish treatment results, which number an estate agency puts in a listing. The answers exist, but they are spread across laws, rulebooks and chamber codes. I collected them on one site, set out as twelve issues, from restaurants and accommodation to lawyers and manufacturers.

Every obligation names the regulation, the Official Gazette issue, the article and a link to the text. Anything the law does not require is labelled as practice, so a reader sees at once what is mandatory and what is simply a good idea. Each issue opens with the anatomy of that kind of site: on a computer a phone sketch assembles block by block while the list scrolls past, and on a phone it appears complete.

## What I built

- Twelve industry issues, each with a site sketch, the relevant rules, common mistakes and a site I built as an example
- A table of obligations across all industries, with a filter and a link to the regulation on every row
- A scroll-driven sketch made with GSAP ScrollTrigger; Lenis smooths scrolling only for a mouse or touchpad
- All text in the HTML, readable without JavaScript and complete with reduced motion
- No cookies, no analytics and no requests to other servers

## Results

| | Performance | Accessibility | Best practices | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Mobile | 92 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, lab test of the live site, October 2026. Security headers: 6 of 6. axe accessibility check: no violations. Structured data: `FAQPage`, `Person`.

## Screenshots

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Sajtovi za firme, home page on a 1440 px screen"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Sajtovi za firme, home page on a phone"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Table of obligations, each row with the regulation and article">
<sub>Table of obligations, each row with the regulation and article</sub>

---

<sub>Built by [D. Svilenković](https://svilenkovic.com).</sub>
