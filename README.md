# frontend-starter-kit

![dev-dep](https://david-dm.org/themihel/frontend-starter-kit/dev-status.svg)

Lightweight starter kit for frontend/website projects.

## Features

- [x] Lightweight / no boilerplate code
- [x] SASS support
- [x] Minified / concatenated Javascript and CSS
- [x] Linted Javascript with [ESLint](http://eslint.org/)
- [x] [Bower](http://bower.io/) support (see gulp tasks)
- [x] Up to date dev-dependencies thanks to @greenkeeperio
- [x] Synchronised browser testing by [BrowserSync](synchronised browser testing)

## Get started

### Download
```bash
git clone https://github.com/themihel/frontend-starter-kit.git
cd frontend-starter-kit
npm install
```

### Usage

#### Gulp-tasks
* `gulp styles` : Compile/concat sass files (minify for *dist*)
* `gulp scripts` : Concat js files ((minify for *dist*))
* `gulp lint` : Lint js files with ESLint
* `gulp images` : Optimize images from *images* folder
* `gulp html` : Copy and minify html files into *dist* folder
* `gulp bower` : Copy bower files into *dist* folder
* `gulp clean` : Remove *tmp* and *dist* folder
* `gulp dist` : Compiles/concats/lint/minifies code for production/upload
* `serve` : Serve files for local testing (code unminified)
* `gulp serve:dist` : Serve files from *dist* folder for final testing
* `gulp watch` : Compiles sass / Lint and concat js files (see: **styles**, **lint**, **scripts**)

**Note:** `gulp watch`, `gulp serve` and `gulp serve:dist` automatically run on code changes

#### Recommended file structure
```
frontend-starter-kit
│   .editorconfig
│   .eslintrc
│   .gitignore
│   .jscsrc
│   gulpfile.js
│   LICENSE
│   package.json
│   README.md
│
└───app
    │   index.html
    │   ...
    │
    ├───scripts
    │   │   app.js
    │   │   ...
    │
    ├───images
    │   ...
    │
    └───styles
        │
        │   app.scss
        │
        ├───core
        │   │   _core.scss
        │   │   _vars.scss
        │   │   ...
        │
        ├───mixins
        │   │   _normalizeBoxSize.scss
        │   │   ...
        │
        ├───modules
        │   │   ...
        │
        └───views
            │   ...


```
