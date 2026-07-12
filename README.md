# homoscribens.github.io

Personal academic website for Daichi Haraguchi, published with GitHub Pages and Jekyll.

## Content updates

The site intentionally contains only three public sections:

- Profile: edit `_pages/about.md` and the `author` block in `_config.yml`.
- Publications: edit `_data/publications.yml`.
- CV: edit `_data/cv.yml`.

Add paper PDFs and posters to `files/`. The profile image is `images/profile.jpg`.

## Local preview

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` in a browser.
