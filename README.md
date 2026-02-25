# README
This is the repo of a github page, served [.

View the Site here:

[Link]](https://iammodding.github.io/Modding-Stuffs/)


## 🚀 Deployment

This site is built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

### Automatic Deployment

1. Push to the `main` branch
2. GitHub Actions will automatically build and deploy the site

### Manual Setup

If you need to set up GitHub Pages manually:

1. Go to repository **Settings** → **Pages**
2. Under "Build and deployment":
   - Source: **GitHub Actions**
3. The site will be available at `https://yourusername.github.io/repository-name/`

## 🛠️ Local Development

### Prerequisites
- Ruby 2.7+
- Bundler (`gem install bundler`)

### Running Locally

```bash
cd docs
bundle install
bundle exec jekyll serve --livereload
```

Then open `http://localhost:4000` in your browser.