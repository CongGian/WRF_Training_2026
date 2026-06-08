# WRF/HPC Training Workshop Page

Static workshop page generated from `HPC_Training_Announcement.docx`.

## GitHub Pages

Recommended hosting path for this page:

1. Create a GitHub repository.
2. Push this folder to the repository.
3. In GitHub, open `Settings > Pages`.
4. Set source to `Deploy from a branch`.
5. Select the `main` branch and `/root`.

The page will be served from:

```text
https://<github-user-or-org>.github.io/<repository-name>/
```

## Jetstream2

Jetstream2 is also viable if you want to host from a VM with a public IP or custom domain. For a static page, install a web server such as Nginx or Caddy and copy these files into the web root.

Required files:

```text
index.html
styles.css
.nojekyll
assets/hpc-weather-workshop-hero.jpg
```

Do not publish `HPC_Training_Announcement.docx`; it is the draft source document and may contain metadata or comments.
