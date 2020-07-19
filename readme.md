# Description
contains the lowlandtech theme template

## Import template

```bash
   npm i -g degit
   degit github:lowlandtech/theme#master app/src
```

## Install packages

```bash
   npm i bootstrap ng2-charts ngx-bootstrap simple-line-icons font-awesome flag-icon-css rxjs --save-dev
```

## Configure styles and scripts

```json
"styles": [
    "../node_modules/flag-icon-css/css/flag-icon.css",
    "../node_modules/font-awesome/css/font-awesome.css",
    "../node_modules/simple-line-icons/css/simple-line-icons.css",
    "styles/style.scss"
],
"scripts": [
    "../node_modules/chart.js/dist/Chart.bundle.min.js",
    "../node_modules/chart.js/dist/Chart.min.js"
],
```
