# Tochukwu Dominic Eze — Academic Website

This is a lightweight, responsive academic portfolio designed for free hosting on GitHub Pages.

## What is already populated

- Research profile and current dissertation focus
- Research interests
- Research and professional experience
- Education
- Teaching experience
- Awards, honors, leadership, and service
- Technical skills and professional memberships
- 2026 peer-reviewed publications with verified DOI/publisher links
- Local PDF and DOCX copies of the October 2026 CV

## Publication links used

1. CLAF — https://doi.org/10.1007/s11412-026-09475-w
2. Visual privacy / cartoonification — https://doi.org/10.1016/j.caeo.2026.100393
3. Unmasking Suppressed Emotion — https://doi.org/10.1145/3776574.3831132
4. CLARA — https://doi.org/10.1007/978-3-032-29755-6_23
5. CLARA arXiv — https://arxiv.org/abs/2605.17259

## Professional links used

- tiilt Lab profile — https://tiilt.northwestern.edu/people/tochukwu-eze/
- LinkedIn — https://www.linkedin.com/in/tochukwudominiceze
- ORCID — https://orcid.org/0000-0001-9710-8306

## Privacy choice

The CV contains a telephone number and street address. These were intentionally not placed on the public website. The site shows the Northwestern email and Evanston, Illinois affiliation only.

## Add a professional headshot

The current site uses a `TE` monogram. To use a headshot:

1. Put the image at `assets/profile.jpg`.
2. Replace this block in `index.html`:

```html
<div class="profile-portrait" aria-label="Tochukwu Eze initials">
  <span>TE</span>
</div>
```

with:

```html
<div class="profile-portrait">
  <img src="assets/profile.jpg" alt="Portrait of Tochukwu Dominic Eze">
</div>
```

3. Add to `styles.css`:

```css
.profile-portrait img { width: 100%; height: 100%; object-fit: cover; }
```

## Publish on GitHub Pages

1. Create a public repository named `YOURUSERNAME.github.io`.
2. Upload the **contents** of this folder to the repository root.
3. Commit to the `main` branch.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose `main` and `/ (root)`, then save.
7. Your site will appear at `https://YOURUSERNAME.github.io`.

## File structure

```text
index.html
styles.css
script.js
README.md
assets/
  favicon.svg
cv/
  Tochukwu-Dominic-Eze-CV.pdf
  Tochukwu-Dominic-Eze-CV.docx
```
