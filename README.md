# frontend-starter-kit

Lightweight starter kit for frontend/website projects.

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
