# Tyler Chewning Portfolio

A modern, responsive personal portfolio website showcasing Tyler Chewning's background, selected projects, and contact information.

## Project Overview

This repository contains a static portfolio site originally started as a Coursera web development exercise and later refactored into a cleaner, more professional presentation. The site highlights an Information Security learning path while keeping the UI simple, accessible, and mobile-friendly.

## Features

- **Responsive landing page** with a hero section, clear calls to action, and adaptive layout.
- **Sticky top navigation** with quick links to About, Projects, Contact, and Resume.
- **Project showcase cards** for featured work and learning efforts.
- **Contact section** with direct email and GitHub profile links.
- **Accessibility-conscious structure**, including semantic HTML, skip link support, and readable color contrast.
- **Dedicated resume page** linked from the main portfolio.

## Technologies Used

- **HTML5** for semantic content structure
- **CSS3** for layout, theming, responsiveness, and visual styling
- **Git & GitHub** for version control and hosting workflow
- **GitHub Pages** for deployment

## Screenshots

> Replace these placeholders with screenshots from your deployed site as it evolves.

### Home / Hero Section
![Portfolio home hero](images/banner.jpg)

### Profile / Headshot Block
![Profile headshot](images/headshot.jpg)

### Suggested future screenshot paths
- `images/screenshots/home-desktop.png`
- `images/screenshots/home-mobile.png`
- `images/screenshots/projects-section.png`

## Deployment Instructions

This project is designed for GitHub Pages static hosting.

1. **Clone the repository**
   ```bash
   git clone https://github.com/thchewningcofc/thchewningcofc.coursera.github.io.git
   cd thchewningcofc.coursera.github.io
   ```
2. **Preview locally**
   - Open `index.html` directly in your browser, or
   - Use a local static server (recommended), for example:
     ```bash
     python3 -m http.server 8000
     ```
     Then visit `http://localhost:8000`.
3. **Deploy via GitHub Pages**
   - Push changes to the `main` branch.
   - In GitHub: **Settings → Pages**.
   - Set **Source** to deploy from `main` branch (root).
   - Save and wait for the Pages build to complete.
4. **Verify deployment**
   - Visit your published URL (for user/organization pages, this is usually `https://<username>.github.io/`).

## Future Improvements

- Add a downloadable PDF version of the resume.
- Introduce a dedicated projects detail page with screenshots and outcomes.
- Add a contact form with spam protection.
- Improve SEO metadata and Open Graph sharing cards.
- Add light/dark theme toggle.
- Expand accessibility testing (keyboard flows, ARIA landmarks, screen reader audit).
- Integrate CI checks (e.g., HTML/CSS linting) on pull requests.

---

If you'd like, you can also add a **Live Demo** link near the top of this README once GitHub Pages is fully configured.
