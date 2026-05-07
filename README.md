# Luis Montesinos — Jekyll Professional Website

This repository contains a Jekyll-based professional website designed for deployment with GitHub Pages.

## 1. Rename the repository

For a personal GitHub Pages website, name the repository:

```text
yourusername.github.io
```

For example:

```text
luismontesinos.github.io
```

## 2. Edit `_config.yml`

Update the following fields:

```yaml
url: "https://yourusername.github.io"

author:
  email: "your.email@example.com"

social:
  github: "https://github.com/yourusername"
  linkedin: "https://www.linkedin.com/in/yourprofile"
  orcid: "https://orcid.org/0000-0000-0000-0000"
  scholar: "https://scholar.google.com/citations?user=YOUR_ID"
```

## 3. Add your profile photo

Place your photo in:

```text
assets/images/profile.jpg
```

The current homepage uses an initials placeholder. You can later replace it with an image.

## 4. Run locally

Install Ruby and Bundler. Then run:

```bash
bundle install
bundle exec jekyll serve
```

Open:

```text
http://localhost:4000
```

## 5. Deploy with GitHub Pages

Push the files to GitHub.

Then go to:

```text
Settings > Pages
```

Choose the branch you want to deploy, usually:

```text
main
```

and the root folder:

```text
/
```

GitHub will publish the website at:

```text
https://yourusername.github.io
```

## 6. Edit content

Most content is in Markdown files:

```text
index.md
about.md
research.md
projects.md
publications.md
teaching.md
contact.md
```

Selected projects are in:

```text
_projects/
```

Each project has front matter at the top and Markdown content below.
