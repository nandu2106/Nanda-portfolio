# Nanda Karri — Executive Portfolio Website

Personal portfolio website for **Nanda Karri**, Senior Director – IT Infrastructure & Digital Transformation.

## Live Site
Hosted at: `https://[your-github-username].github.io/nanda-portfolio`

## Contents
- `index.html` — Full portfolio website (single file, no dependencies)
- `Nanda_karri_-_Head_of_IT_GCC.pdf` — Resume PDF (place in this folder for the download button to work)

## Features
- Animated scroll-reveal sections
- Photo upload (click the portrait frame — saves to browser localStorage)
- CV download button linked to your PDF
- Fully responsive (mobile + desktop)
- No build step, no frameworks — pure HTML/CSS/JS

## How to Deploy on GitHub Pages

1. Create a new GitHub repository named `nanda-portfolio` (or any name you prefer)
2. Upload `index.html` and your resume PDF (`Nanda_karri_-_Head_of_IT_GCC.pdf`) to the repository
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch, `/ (root)` folder → click **Save**
6. Your site will be live at `https://[your-username].github.io/nanda-portfolio` within 1–2 minutes

## Adding Your Photo (Permanent)
The photo upload button saves to browser localStorage (works for visitors on their own device).
For a permanent photo that everyone sees:
1. Save your photo as `photo.jpg` in the same folder
2. In `index.html`, find `<img id="profile-photo"` and change to:
   ```html
   <img id="profile-photo" src="photo.jpg" alt="Nanda Karri" style="display:block;">
   ```
3. Also remove `style="display:none"` from that same img tag
4. Remove or hide the placeholder div

## Customization
- Update your LinkedIn URL: search for `linkedin.com/in/nandakarri` and replace with your actual URL
- All content is in `index.html` — edit directly

## URL to add in your Resume
`https://[your-github-username].github.io/nanda-portfolio`
