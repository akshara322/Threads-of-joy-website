# Threads of Joy website

Website for Threads of Joy, a student-led nonprofit that collects gently used traditional Indian clothing in Omaha and sends it to children in New Delhi.

It's a plain static site with no build step:

- `index.html`: every page (Home, About, Donate, Impact, Partners, Volunteer, Contact), switched by the link after `#`
- `hero.jpg`, `logo.png`, `ig-flyer.jpg`, `ig-embroidery.jpg`: images

## Quick edits

At the bottom of `index.html`:

- `LINKS`: paste the GoFundMe, volunteer form and contact form URLs. Buttons show "Soon" until these are filled in.
- `STATS`: impact numbers for the Impact page.

## Deploying

Hosted on Vercel (Framework Preset: Other, no build command). Every push to `main` updates the live site.
