# townim-faisal.github.io

Personal academic website of Townim Faisal Chowdhury, built with [al-folio](https://github.com/alshedivat/al-folio) v1.2 and deployed to GitHub Pages.

The previous academicpages version of the site is kept in `old/` for reference; it is excluded from the build.

## Updating the site

| To change                         | Edit                                                                                       |
| --------------------------------- | ------------------------------------------------------------------------------------------ |
| Bio, research themes, home figure | `_pages/about.md`                                                                          |
| Publications                      | `_bibliography/papers.bib` (`selected = {true}` puts a paper on the home page)              |
| Venue badge colours               | `_data/venues.yml`                                                                         |
| News                              | add a file to `_news/` (copy an existing one; dates show as month and year)                |
| CV page                           | `_data/cv.yml`; the PDF link is `cv_pdf` in `_pages/cv.md` and `_data/socials.yml`         |
| Social links                      | `_data/socials.yml`                                                                        |
| Profile photo, figures            | `assets/img/` (paper thumbnails go in `assets/img/publication_preview/`, set via `preview`) |
| Name, URL, site-wide options      | `_config.yml`                                                                              |

## Deployment

Pushing to `master` runs `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch.
In the repository settings, **Pages → Build and deployment** must be set to _Deploy from a branch_, branch `gh-pages`, folder `/ (root)`.

## Local preview (optional)

Requires Ruby 3.3 and Bundler:

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```
