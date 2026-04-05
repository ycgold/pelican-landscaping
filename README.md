# Pelican Landscaping LLC - Website

A professional multi-page website built as a pitch demo for Pelican Landscaping LLC.

## Pages
- **index.html** — Home page (hero, services overview, reviews, CTA)
- **services.html** — Detailed service pages with process steps
- **about.html** — Company story, values, gallery, testimonials
- **contact.html** — Contact form, business info, FAQ

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g., `pelican-landscaping`)
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Pelican Landscaping website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/pelican-landscaping.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your GitHub repo
4. Set source to **Deploy from a branch** → **main** → **/ (root)**
5. Your site will be live at: `https://YOUR-USERNAME.github.io/pelican-landscaping/`

## Customization Notes
- Replace gradient placeholders with real project photos
- Add a Google Maps embed in the contact page map placeholder
- Connect the contact form to Formspree, Netlify Forms, or a backend
- Add Google Analytics tracking code for conversion tracking
