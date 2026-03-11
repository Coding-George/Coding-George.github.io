# Coding-George.github.io

Simple portfolio page for GitHub Pages. It showcases projects with a demo GIF and a short description side-by-side.

## Files

- `index.html`: page structure and project content.
- `styles.css`: visual design, responsive layout, and animations.
- `assets/`: place your project GIF files here.

## Customize Content

1. Open `index.html`.
2. Replace `jorge@example.com` with your real email.
3. For each project card:
	- Update title, description, and tech stack.
	- Replace repo link (`href="#"`) with your real GitHub link.
	- Replace GIF path (for example `assets/project-1.gif`) with your real file.

## Add More Projects

Duplicate any `<article class="project-card reveal">...</article>` block in `index.html` and update the content.

## Publish On GitHub Pages

1. Push this repository to GitHub.
2. Go to repository `Settings` -> `Pages`.
3. Under `Build and deployment`, choose:
	- `Source`: `Deploy from a branch`
	- `Branch`: `main` (or your default branch) and folder `/ (root)`
4. Save and wait for deployment.

Your site will be available at:

`https://<your-github-username>.github.io/`