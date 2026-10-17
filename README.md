# Python Full-Stack Developer Portfolio

A responsive, single-page portfolio built with Jekyll and the GitHub Pages-supported Minima theme.

## Run locally

Requirements: Ruby and Bundler.

```sh
bundle install
bundle exec jekyll serve
```

Open the local URL printed by Jekyll (usually <http://127.0.0.1:4000/portfolio-website/>).

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Update `url` in `_config.yml` to your GitHub Pages domain. Keep `baseurl: "/portfolio-website"` for this repository's project site; set it to `""` for a username site or a custom domain.
4. Personalize the name, bio, project cards, skills, email, and profile links in `index.md`.

The starter project cards and contact details are placeholders; replace them before publishing. If you rename the repository, update `baseurl` to match.
