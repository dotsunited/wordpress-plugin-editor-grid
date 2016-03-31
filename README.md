WordPress Editor Grid Plugin
===

A lightweight WordPress Plugin to create and manage grids via the WordPress Post Editor.

Installation
---

Install with

```bash
composer require dotsunited/wordpress-plugin-editor-grid
```

Note: This plugin does not automatically add the required styles to the frontend pages (only to the Admin Editor), in order to prevent multiple css files from multiple plugins in the site header (which would ruin the pagespeed).

The incorporation into a [Webpack](https://github.com/webpack/webpack) workflow with LESS is encouraged.

You can find an example boilerplate for possible frontend styles [here](https://github.com/dotsunited/wordpress-boilerplate/blob/master/assets/main/grid/style.less), and for a possible WordPress-Webpack setup [here](https://github.com/dotsunited/wordpress-boilerplate/blob/master/webpack.config.js).

License
---

Copyright (c) 2015-2016 Dots United GmbH.
Released under the [MIT](LICENSE?raw=1) license.
