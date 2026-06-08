# WRF Training 2026 Landing Page

Public landing and preparation page for the 2026 virtual WRF/HPC training workshop.

Live page:

```text
https://conggian.github.io/WRF_Training_2026/
```

Repository:

```text
https://github.com/CongGian/WRF_Training_2026
```

## Current Deployment

This site is hosted with GitHub Pages from the `main` branch at the repository root.

GitHub Pages settings:

```text
Build and deployment: Deploy from a branch
Branch: main
Folder: /root
```

Because this is a plain static site, no build step, package manager, or server runtime is required.

## Published Files

The public site is made from these files:

```text
index.html
styles.css
.nojekyll
assets/hpc-weather-workshop-hero.jpg
```

`HPC_Training_Announcement.docx` is the local draft source document and should not be published. The larger PNG hero source is also ignored to keep the public repository smaller.

## Update Workflow

1. Edit `index.html` for content changes.
2. Edit `styles.css` for layout or visual changes.
3. Open `index.html` locally in a browser to preview.
4. Commit the changed public files.
5. Push to `main`.
6. GitHub Pages will update the live site automatically, usually within a few minutes.

Useful commands:

```bash
git status
git add index.html styles.css README.md .nojekyll assets/hpc-weather-workshop-hero.jpg
git commit -m "Update workshop landing page"
git push
```

After pushing, check:

```text
https://conggian.github.io/WRF_Training_2026/
```

## Relationship to Workshop Materials

This repository is only for the early public-facing workshop page. Code, notebooks, datasets, and participant exercises can remain in a separate workshop materials repository until they are ready to share.
