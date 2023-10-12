# [Lucie](https://lucie.shahzoab.com/)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with `dist` directory. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

Clone the source files of the theme and navigate into the theme's root directory. Run `yarn` and then run `yarn start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `package.json` file to see which scripts are included.

#### Scripts

-   `yarn build` builds the project - this builds assets, HTML, JS, and CSS into `dist`
-   `yarn build:assets` copies the files in the `src/assets/` directory into `dist`
-   `yarn build:pug` compiles the Pug located in the `src/pug/` directory into `dist`
-   `yarn build:scss` compiles the SCSS files located in the `src/scss/` directory into `dist`
-   `yarn clean` deletes the `dist` directory to prepare for rebuilding the project
-   `yarn start:debug` runs the project in debug mode
-   `yarn start` runs the project, launches a live preview in your default browser, and watches for changes made to files in `src`
