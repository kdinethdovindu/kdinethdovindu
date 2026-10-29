# How to publish your GitHub Profile README

This is the **GitHub profile README**, not the README for your `Portfolio` application.

## Create the special profile repository

1. Sign in to GitHub as `kdinethdovindu`.
2. Open https://github.com/new
3. Set **Repository name** to `kdinethdovindu` (exactly your GitHub username).
4. Select **Public** and create the repository.
5. Upload `README.md` to the repository root.
6. Upload the entire `assets` directory alongside `README.md` (preserve its filenames and folder path).
7. Commit the files. Visit https://github.com/kdinethdovindu to view your new profile README.

### Folder structure

```
kdinethdovindu/
├── README.md
└── assets/
    ├── animated-header.gif
    ├── careertrack.svg
    ├── moveone.svg
    ├── portfolio.svg
    ├── primecore.svg
    ├── tech-stack.svg
    └── tech-logos/
        ├── react.svg, nextjs.svg, typescript.svg, javascript.svg
        ├── java.svg, spring-boot.svg, postgresql.svg, tailwind.svg
        └── git.svg, github.svg, postman.svg, vercel.svg, docker.svg
```

`header-preview.png` is optional and does not need to be uploaded.

## Design notes

- Header animation is a **local GIF** (not dependent on any third-party service).
- Project cards and technology icons are **local SVG images** (sharp at any screen size).
- Social badges use `img.shields.io`; the text links in the footer remain available if those images are blocked.
- All project/source/demo/contact destinations come from your public portfolio content or linked source repositories.
- No GitHub statistics service is required; no secret tokens or GitHub Actions are needed.
- You can edit `README.md` to adjust your current availability, projects, or learning focus at any time.
- Keep the `assets/` relative image paths unchanged unless you move the files.

## Preview

Open `README.md` on GitHub after committing. Local Markdown renderers may differ from GitHub's rendering of HTML tables.
