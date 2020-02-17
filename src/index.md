---
title: Tiny Tiger CSS | A Mini CSS Library
layout: "base.njk"
---

# Tiny Tiger CSS 😼

> A work-in-progress SCSS library for bootstrapping projects.

[View the Demo](https://laura-is-here.github.io/tiny-tiger-css/test/)

## Getting Started 😸

Clone the repository or download and extract the files then `cd` intor the new directory.

    git clone https://github.com/laura-is-here/tiny-tiger-css.git && cd tiny-tiger-css

Install the dependencies.

    npm install

Tell node-sass to watch any files in `src/scss` and rebuild on any changes:

    npm run sass

Edit any of the files in `src/scss`, open the `dist/index.html` to see the changes take effect.

To use in production, use the generated file in `dist/css/main.min.css`

    <link href="dist/css/main.min.css" rel="stylesheet" type="text/css">

Or incorporate the files in `src/scss` into your own asset pipeline.

## Acknowledgements 😻

- Inspired by [Tania Rascia's Primitive CSS](https://taniarascia.github.io/primitive)
- Includes [normalize.css](https://necolas.github.io/normalize.css/)
- SCSS directory structure from [Sass Guidelines](https://sass-guidelin.es/)

---

## TODO 🙀

- Clean up SCSS variable/CSS custom property use
- Add mixins to streamline utilities
- Add comments and documentation
- Integrate PostCSS/Autoprefixer
