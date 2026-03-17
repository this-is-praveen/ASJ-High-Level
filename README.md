# Agile, Scrum, Jira Presentation

Minimal HTML slide deck for interview/demo usage.

## Quick Review

- File: `index.html`
- Navigation:
  - Keyboard: `Left/Right`, `Up/Down`, `Space`
  - Buttons: First, Previous, dots, Next, Last, Fullscreen
  - Touch: swipe left/right
- Author: Praveenmuthukumar Gnanaraj

## Run Locally

Open `index.html` in a browser.

## GitLab Pages Deploy

This repo includes `.gitlab-ci.yml` for GitLab Pages.

- If `index.html` exists, it is deployed.
- Else if `presentation.html` exists, it is published as `index.html`.

After pushing to the default branch, GitLab Pages serves the site from the generated `public/` folder.
