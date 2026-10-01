# jingyitong.github.io

Personal academic website of Jingyi Tong, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

## Where to edit

| What | File |
| --- | --- |
| Bio, photo, office address | `_pages/about.md`, `assets/img/prof_pic.jpg` |
| Papers and presentations (Research page) | `_pages/publications.md` |
| Recent projects (home page) | bottom of `_pages/about.md` |
| Fonts, colors, buttons | `_sass/_custom.scss` |
| Extension and outreach | `_pages/extension.md` |
| Teaching | `_pages/teaching.md` |
| CV files | `assets/pdf/CV_Jingyi_Tong.pdf`, `assets/pdf/中文简历-童敬宜.pdf` |
| CV buttons and contact icons under the photo | `more_info` in `_pages/about.md` |
| Site title, description, theme settings | `_config.yml` |

Every push to `main` rebuilds the site with GitHub Actions (`.github/workflows/deploy.yml`) and publishes it to the `gh-pages` branch.
