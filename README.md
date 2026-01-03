# Lion & Tiger Athletics (V1)

This is a safety-first, static website (no database, no comments, no logins).
You can publish it for **free** and get a live link in minutes.

## What’s inside
- `index.html` (Home)
- `golf.html`, `bjj.html`, `training.html`, `media.html`
- `support.html` (Supporting the Journey)
- `contact.html` (Secure contact form - optional)
- `privacy.html` (Privacy & Safety commitment)
- `styles.css` and `/assets`

## Quick preview on your computer (Mac)
1. Unzip the folder
2. Double-click `index.html`  
   (It will open in your browser)

## Publish for FREE (Option 1: Cloudflare Pages — recommended)
Cloudflare Pages can deploy static sites for free.
High level steps:
1. Create a free GitHub account (if you don’t have one)
2. Create a new GitHub repository (e.g., `lion-tiger-athletics`)
3. Upload these files to the repo (drag & drop on GitHub)
4. Create a free Cloudflare account
5. Cloudflare Pages → “Create a project” → connect GitHub repo → Deploy
6. You’ll receive a live URL like: `https://<project>.pages.dev`

## Publish for FREE (Option 2: GitHub Pages — easiest)
1. Create a GitHub repo named `lion-tiger-athletics`
2. Upload all files (keep them in the repo root)
3. Settings → Pages → Deploy from branch → `main` / root
4. You’ll receive a link like: `https://<username>.github.io/lion-tiger-athletics/`

## Add a custom domain later (paid domain, optional)
When you’re ready, buy a domain (~$10–$15/year) and point it to Cloudflare Pages or GitHub Pages.
You can set redirects so the old free link still works.

## Replace the hero image
Current placeholder: `/assets/hero-placeholder.svg`
- Replace it with your photo (recommended: cropped swing close-up, no face, no background signs)
- Update `styles.css` line referencing `hero-placeholder.svg` to your new file name.

## Enable the contact form (optional)
This site uses Formspree (free) as a safe contact form.
1. Go to Formspree and create a new form
2. Copy your form endpoint like: `https://formspree.io/f/abcdwxyz`
3. Replace `https://formspree.io/f/YOUR_FORM_ID` in `contact.html`

## Safety reminder
- No real names, birthdays, school details, or real-time locations
- Post tournament reflections only after events are finished
- Remove photo/video location metadata before uploading
