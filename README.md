---
toc: true
---

# OverheidNL Jekyll Theme

A jekyll theme for the set up of quick generic static sites and for use with GitHub pages and/or Jekyll in the [Koop Overheid.nl style](https://componenten-koop.overheid.nl).

## Building locally

This theme is built to run predictably on GitHub pages, therefore the [`github-pages`](https://github.com/github/pages-gem) gem is required. Run `bundle install` before building with Jekyll.

To serve locally with Jekyll, use `bundle exec jekyll serve`.

## Configuring and customising

The configuration of this theme can be done mostly in [Jekyll's `_config.yml`](https://jekyllrb.com/docs/configuration/). To replace sections of the site you can overwrite [the `_includes`](https://jekyllrb.com/docs/includes/) and add [new `_layouts`](https://jekyllrb.com/docs/themes/#overriding-theme-defaults).

### Header

You can replace the header by putting a `header.liquid` file in the folder `_includes`.

#### The site title

You can hide the site title in the top by adding the following to your `_config.yml`.

```yaml
headerHideTitle: true
```

### Footer

To place your own content in the footer create a file called `footer.liquid` in the folder `_includes`. The footer expects up to 4 `article` tags as columns. These can feature `h3`s as headers, `ul`/`li` lists of links or any other content.

## Licence

© The contributors to this project 2018. Licenced MPL 2.0, see the [`LICENSE`](LICENSE) file for more information.
