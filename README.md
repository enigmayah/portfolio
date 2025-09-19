# Portfolio

Static, responsive portfolio site for GitHub Pages. Highlights Android (Kotlin) + Firebase experience and an IoT project.

## Local preview

Open `index.html` directly in your browser, or serve locally:

```bash
# Python 3
python -m http.server 8080
# then open http://localhost:8080/portfolio/
```

## Customize

- Update your name, email, GitHub and LinkedIn links in `index.html` (Contact section and footer).
- Replace `assets/og-card.svg` with a PNG if preferred, and update the `og:image` meta in `index.html` accordingly.
- Adjust content in sections: About, Experience, Projects, Skills.

## Deploy to GitHub Pages

1. Create a new repo named `yourusername.github.io` (replace with your GitHub username).
2. Copy the files in this `portfolio/` folder to the repository root.
3. Commit and push.
4. In the repo Settings → Pages, ensure Source is set to `Deploy from a branch` → `main` → `/ (root)`.
5. Visit `https://yourusername.github.io/` after it builds (usually under a minute).

Alternatively, if this portfolio will live as a project site within another repo, push to that repo and enable Pages from `main` → `/ (root)`, then your site will be at `https://yourusername.github.io/<repo-name>/`.

## License

MIT
