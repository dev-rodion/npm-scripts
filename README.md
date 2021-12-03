# npm-scripts
Learning NPM Scripts


### npm run scss
Compiles .scss files from src/scss folder, compresses and sends to src/css folder. <br />
Using the node-sass plugin. Command Line docs: https://github.com/sass/node-sass#command-line-interface

### npm run autoprefixer
Adds prefixes for .css files from the src/css folder. <br />
Using the postcss, postcss-cli and autoprefixer plugins. Command Line docs: https://github.com/postcss/postcss-cli#usage

### npm run lint-scss
Checks .scss files for correct spelling. In case of an error, it will output information about the error to the console. <br />
Using the stylelint plugin. Style lint rules are written in the .stylelintrc.json file.  <br />
More inforamtion about rules: https://github.com/stylelint/stylelint/blob/main/docs/user-guide/rules/list.md