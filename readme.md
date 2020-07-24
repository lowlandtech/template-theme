# Description
contains the lowlandtech theme template

## Import template

```bash
   npm i -g degit
   degit github:lowlandtech/theme#master src
```

## Install packages

```bash
   npm i bootstrap ngx-bootstrap simple-line-icons font-awesome flag-icon-css rxjs-compat node-sass --save-dev
```

## Configure styles and scripts



```json
// angular.json
"styles": [
  "node_modules/flag-icon-css/css/flag-icon.css",
  "node_modules/font-awesome/css/font-awesome.css",
  "node_modules/simple-line-icons/css/simple-line-icons.css",
  "src/styles/style.scss"
],
```
now run ng build

if you get warnings related to rxjs add the following:

```json
// angular.json
...
"architect": {
  "build": {
    "builder": "@angular-devkit/build-angular:browser",
    "options": {
      "allowedCommonJsDependencies": [
        "rxjs",
        "rxjs-compat"
      ],
...
```
