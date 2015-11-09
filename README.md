# Drupal 8 Subtheme Template of Bootstrap Theme

This template's purpose is aimed towards one region theming as we are accustomed to in Kalatheme.

This is still a work in progress, but this is usable in its current state.

Currently uses custom library bootstrap 3.3.5.

## Instructions
1. Download 8.x dev version of [Bootstrap Theme](https://www.drupal.org/project/bootstrap) into themes/contrib
2. Download this theme into themes/custom
3. Rename subtheme to whatever you want the name to be, use sublime for the quickest and easiest way to do this.
4. Go to admin/appearance/settings/your-subtheme-name
5. Click on advanced tab, set CDN Provider to None.
6. Profit.

## Options
- If you don't want to use the custom BS library included, delete the libraries folder then edit the subtheme.libraries.yml to use the CDN version as follow:
```
  bootstrap:
    version: 3.3.5
    css:
      component:
        //maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css: { type: external, minified: true }
    js:
      //maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js: { type: external, minified: true }
```

- Also comes with an optional layout.  You can layouts by following the same structure and adding them to the subtheme.layouts.yml.
