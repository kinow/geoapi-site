Based on https://www.tailwindtoolbox.com/templates/help-article, Tailwind docs, and minima Jekyll theme.

This repository will be used for experiments with Tailwind, to look similar to the [old site](https://www.geoapi.org/),
while also using the Jekyll theming.

Once work here is done, it will be reported to their issue tracker, assessed by maintainers, and once done, this repository
will be archived.

## Stylesheets

This project utilizes [tailwindcss](https://tailwindcss.com/). The base stylesheet of tailwindcss is customized
for this project with [postcss](https://postcss.org/). This way, instead of writing `<a href="#" class="underfline">`
we can use just `<a href="#">` and use.

```js
a {
  @apply underfline
}
```
## Build

- `npm run postcss`: runs postcss on `base.scss`, customizing tailwindcss to this project, generating a file imported by
Jekyll. Run this command anytime you change `base.css`.
- `jekyll serve` (or `bundle exec jekyll serve`): starts Jekyll running a development server to serve the site locally.
