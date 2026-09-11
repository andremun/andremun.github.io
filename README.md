# andremun.github.io

Personal academic website of Mario Andrés Muñoz Acosta, Senior Research Fellow at the School of Computing and Information Systems, The University of Melbourne. Published at [andremun.github.io](https://andremun.github.io).

Built with [Jekyll](https://jekyllrb.com/) on the [academicpages](https://github.com/academicpages/academicpages.github.io) fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme, and served by GitHub Pages.

## Updating content

| To update...         | Edit...                                    |
|-----------------------|---------------------------------------------|
| About page             | [`_pages/about.md`](_pages/about.md)         |
| CV (education, employment, funding, teaching, supervision, service) | [`_pages/cv.md`](_pages/cv.md) |
| Publications            | [`_pages/publications.md`](_pages/publications.md) — paste a new `1. ...` entry at the top of the relevant list; Markdown renumbers automatically, no manual renumbering needed |
| Talks                   | add a new file to [`_talks/`](_talks/), following the front matter of an existing entry |
| Teaching subjects        | add a new file to [`_teaching/`](_teaching/) |
| Projects/grants          | add a new file to [`_portfolio/`](_portfolio/) |
| Top navigation bar        | [`_data/navigation.yml`](_data/navigation.yml) |
| Site-wide settings (title, author bio, social links) | [`_config.yml`](_config.yml) |

## Running locally

Requires Ruby, Bundler, and Node.js.

```
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Licensing

The theme code is © Michael Rose and contributors, released under the MIT License (see [LICENSE](LICENSE)). The written content of this site (CV, publication list, project descriptions, etc.) is © Mario Andrés Muñoz Acosta unless otherwise noted.
