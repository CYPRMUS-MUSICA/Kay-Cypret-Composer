# Kay Cypret — Personal Website

Static website for Kay Cypret, modern classical composer.

🌐 **Live site:** _add your GitHub Pages URL here once deployed_

## About

A lightweight, hand-coded static site with no build step or dependencies — just HTML, CSS, and locally hosted images. Hosted free on GitHub Pages.

## Structure

```
.
├── index.html         # Home — bio and introduction
├── portfolio.html     # Featured recordings + full composition catalog
├── studio.html        # Cypress-Music Composition Studio info
├── pedagogy.html      # Pedagogical resources (drones, warm-ups, ear training)
├── gallery.html       # Photo gallery
├── contact.html       # Contact form and email
├── style.css          # Shared styling for all pages
└── images/            # Local copies of all site images
```

## Deployment

The site is deployed via **GitHub Pages**:

1. Go to repository **Settings → Pages**
2. Under "Source," select **Deploy from a branch**
3. Choose the `main` branch and `/ (root)` folder
4. Save — the site goes live at `https://<username>.github.io/<repo-name>/` within a minute or two

## Updating Content

### Adding a new composition to the portfolio
Open `portfolio.html` and add a new `<div class="comp-item">` inside the appropriate year group. For featured recordings with video, add a new `<div class="video-card">` block in the "Featured Recordings" section using a YouTube video ID.

### Adding a new pedagogical resource
Open `pedagogy.html` and add a new `<a class="drone-link" href="...">` button in the relevant section (Warm-Ups, Drones, Ear Training, etc.).

### Adding gallery photos
Drop new image files into the `images/` folder, then add a new `<div class="gallery-item">` block in `gallery.html` pointing to the filename.

### Updating text / bio
Edit the relevant HTML file directly — all content is in plain HTML, no templating.

## Contact Form

The contact form on `contact.html` currently points to a **Formspree placeholder**. To activate it:

1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form and copy the endpoint URL (e.g., `https://formspree.io/f/xxxxxxxx`)
3. Replace `https://formspree.io/f/placeholder` in `contact.html` with your real endpoint

## Technology

- Plain HTML5 + CSS3 (no frameworks, no JavaScript build tools)
- [Google Fonts](https://fonts.google.com) (Playfair Display + Inter)
- [YouTube](https://youtube.com) embeds for video playback
- Mobile-responsive with a hamburger menu under 768px

## License

All music, writing, and images © Kay Cypret. All rights reserved.
