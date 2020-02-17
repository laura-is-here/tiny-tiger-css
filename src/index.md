---
title: Tiny Tiger CSS | A Mini CSS Library
layout: "base.njk"
---

# Tiny Tiger CSS 😼

> A work-in-progress CSS library for bootstrapping projects.

[View the Demo](https://laura-is-here.github.io/tiny-tiger-css/test/)

## Getting Started 😸

### Using in a project

1. [Download the minified CSS file](https://github.com/laura-is-here/tiny-tiger-css/blob/master/dist/css/main.min.css)

2. Paste the following into the `<head>` of your HTML file:

```html
<meta charset="utf-8" />
<meta http-equiv="x-ua-compatible" content="ie=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1" />

<!--Change "your-path-to/main.min.css" to the location of the CSS file in your project-->
<link rel="stylesheet" href="your-path-to/main.min.css" />
```

Or, for more local development:

1. Clone the repository or download and extract the files then `cd` intor the new directory.

   ```shell
   git clone https://github.com/laura-is-here/tiny-tiger-css.git && cd tiny-tiger-css
   ```

2. Install the dependencies.

   ```shell
   npm install
   ```

3. Tell node-sass to watch any files in `src/scss` and rebuild on any changes:

   ```shell
   npm run sass
   ```

4. Edit any of the files in `src/scss`, open the `dist/index.html` to see the changes take effect.

5. To use in production, use the generated file in `dist/css/main.min.css`

   ```html
   <link href="dist/css/main.min.css" rel="stylesheet" type="text/css" />
   ```

6. Or incorporate the files in `src/scss` into your own asset pipeline.

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
