# Daemonite Material Color Theme Template

This repository provides templates for easily changing the branding colors for your Daemonite Material project.

## Use as a node dependency

```json
  "dependencies": {
    "daemonite-colors": "git+https://github.com/KofiShango/custom-colors-daemonite-material.git"
  }
```

```html
    <link href="node_modules/daemonite-colors/theme/theme.danger.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.dark.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.info.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.light.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.primary.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.secondary.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.danger.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.success.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.warning.css" rel="stylesheet"/>
```

## Usage

With the templates linked to your document create a `brand.css` file with the following custom properties.

```css
:root {
  --primary: #9c27b0;
  --primary-dark: #7b1fa2;
  --primary-light: #e1bee7;
  --secondary: #ff4081;
  --secondary-dark: #f50057;
  --secondary-light: #ff80ab;
  --danger: #f44336;
  --danger-dark: #d32f2f;
  --danger-light: #ffcdd2;
  --info: #2196f3;
  --info-dark: #1976d2;
  --info-light: #bbdefb;
  --success: #4caf50;
  --success-dark: #388e3c;
  --success-light: #c8e6c9;
  --warning: #ff9800;
  --warning-dark: #f57c00;
  --warning-light: #ffe0b2;
  --dark: #424242;
  --dark-dark: #212121;
  --dark-light: #757575;
  --light: #f5f5f5;
  --light-dark: #e0e0e0;
  --light-light: #fafafa;
}
```

These are Daemonite's default branding colors.
Update these properties with values relevant to your brand.
Link this new file after the theme files.


```html
    <link href="node_modules/daemonite-colors/theme/theme.danger.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.dark.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.info.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.light.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.primary.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.secondary.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.danger.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.success.css" rel="stylesheet"/>
    <link href="node_modules/daemonite-colors/theme/theme.warning.css" rel="stylesheet"/>
    <!-- brand.css goes after these -->
    <link href="path/to/brand.css" rel="stylesheet"/>
```

## Resources

Some resources to help you with material design branding

* [Daemonite Material Theming](http://daemonite.github.io/material/docs/4.1/getting-started/theming/)
* [Material Design Color Tool](https://material.io/tools/color/#!/?view.left=0&view.right=0)
* [Material Design Color System](https://material.io/design/color/the-color-system.html)
