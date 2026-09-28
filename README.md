# jingyitong.github.io

Personal academic website of Jingyi Tong, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

## Where to edit

| What | File |
| --- | --- |
| Bio, photo, office address | `_pages/about.md`, `assets/img/prof_pic.jpg` |
| Papers (working papers, publications, WIP, other) | `_bibliography/papers.bib` (set `status` and, for the home page, `selected = {true}`) |
| Presentations | bottom of `_pages/publications.md` |
| Extension and outreach | `_pages/extension.md` |
| Teaching | `_pages/teaching.md` |
| CV files | `assets/pdf/CV_Jingyi_Tong.pdf`, `assets/pdf/CV_Jingyi_Tong_Chinese.pdf` |
| Contact icons (email, Google Scholar, ORCID, etc.) | `_data/socials.yml` |
| Site title, description, theme settings | `_config.yml` |

Every push to `main` rebuilds the site with GitHub Actions (`.github/workflows/deploy.yml`) and publishes it to the `gh-pages` branch.
