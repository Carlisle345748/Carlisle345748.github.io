# Zikun Cui Academic Homepage

This site is built directly from the official [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and customized with Zikun Cui's academic profile, publications, experience, education, and service.

## Deploy to GitHub Pages

1. Create a repository named `Carlisle345748.github.io`.
2. Copy this folder's contents into that repository.
3. Update `_config.yml`:
   - `author.googlescholar` once the exact Google Scholar profile URL is available
4. Commit and push to GitHub.
5. Enable GitHub Pages in the repository settings if it is not already enabled.

## Main Content Files

- `_config.yml` - site title, author profile, sidebar links
- `_data/navigation.yml` - top navigation
- `_pages/about.md` - homepage
- `_pages/cv.md` - CV page
- `_pages/experience.md` - experience page
- `_pages/service.md` - service page
- `_publications/` - publication records
- `images/zikun-cui-profile.svg` - profile placeholder image

## Local Preview

Academic Pages is a Jekyll site. This workspace has been tested with Homebrew Ruby:

```bash
/opt/homebrew/opt/ruby/bin/ruby -v
/opt/homebrew/opt/ruby/bin/bundle config set path vendor/bundle
/opt/homebrew/opt/ruby/bin/bundle install
/opt/homebrew/opt/ruby/bin/bundle exec jekyll serve
```

Then open `http://localhost:4000`.
