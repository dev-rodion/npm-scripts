# npm-scripts
Learning NPM Scripts


### npm run scss
Compiles .scss files from app/scss folder, compresses and sends to app/css folder. <br />
Using the node-sass plugin. Command Line docs: https://github.com/sass/node-sass#command-line-interface

### npm run autoprefixer
Adds prefixes for .css files from the app/css folder. <br />
Using the postcss, postcss-cli and autoprefixer plugins. Command Line docs: https://github.com/postcss/postcss-cli#usage

### npm run lint-scss
Checks .scss files for correct spelling. In case of an error, it will output information about the error to the console. <br />
Using the stylelint plugin. Style lint rules are written in the .stylelintrc.json file.  <br />
More inforamtion about rules: https://github.com/stylelint/stylelint/blob/main/docs/user-guide/rules/list.md

### npm run lint-js 
Checks .js files from the app/js folder for correct spelling and fixes errors. <br />
Using the eslint plugin. Script lint rules are written in the .eslintrc.json file.  <br />
Command Line docs: https://eslint.org/docs/user-guide/command-line-interface <br />
Rules docs: https://eslint.org/docs/rules/

### npm run uglify
Minifies, compresses and improves app/js/script.js <br />
Using the uglifyjs plugin. Command Line docs: https://github.com/mishoo/UglifyJS#command-line-options

### npm run imagemin
Optimizes images from app/images/ folder and sends them to dist/images/ folder.  <br />
Using the imagemin plugin. Command Line docs: https://github.com/imagemin/imagemin-cli#readme

### npm run server
Starts a server from the app/ directory, watching app/\*.html, app/css/\*.css and app/js/script.min.js. <br />
Using the browser-sync plugin. Command Line docs: https://browsersync.io/docs/command-line