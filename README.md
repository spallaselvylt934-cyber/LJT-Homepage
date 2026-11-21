# LJT-Homepage

Personal academic homepage of **Junteng Liu**, first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology.

Forked from the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and built with Jekyll for GitHub Pages.

## Site structure

- **About / home page** (`_pages/about.md`): personal details, academic background, research interests, research experience, publications, skills, honors and awards, and contact information.
- **Publications** (`_publications/`): one Markdown file per publication, listed on the Publications page (`_pages/publications.html`).
- **CV** (`_pages/cv.md`): education, research experience, skills, honors and awards, and publications.

Site-wide settings (name, bio, and contact links) live in `_config.yml`; the header navigation is defined in `_data/navigation.yml`.

## Deployment

The site is built and deployed to GitHub Pages by the workflow in `.github/workflows/jekyll.yml` on every push to `master` (it can also be run manually from the Actions tab).

To publish the site, enable GitHub Pages once:

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Run the **Deploy Academic Pages template site to Pages** workflow from the **Actions** tab (or push a new commit).

The site will then be available at `https://spallaselvylt934-cyber.github.io/LJT-Homepage/`.