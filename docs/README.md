# Landing page for Open Source Covid-19

Built with Jekyll and serverd over Github pages.
We are framework agnostic and simple opted for the fastest setup.
Contributions are encouraged.

## Getting started

This project requires Ruby and Bundler ~ 2.7.1
Once the project is cloned you can

```
bundle install
bundle exec jekyll serve --watch
```

## Misc

- We use the `jekyll-redirect-from` plugin to set base url to '/fr'.
  You can change it by moving the front matter `redirect_from: /` command to a different page.
- When you update any information make sure to do it for both `en.md` and `fr.md`.

This repository is licensed under [MIT](../LICENSE) (c) 2019 GitHub, Inc.
