# frontendphil.com-2015

**The website for Phil Lennon**

* Author: [Phil Lennon](https://frontendphil.com)
* Source: [github.com/fephil/frontendphil.com-2015](https://github.com/fephil/frontendphil.com-2015)
* Issues and Suggestions: [github.com/fephil/frontendphil.com-2015/issues](https://github.com/fephil/frontendphil.com-2015/issues)
* Twitter: [@frontendphil](https://twitter.com/frontendphil)
* Email: [enquiry@frontendphil.com](mailto:enquiry@frontendphil.com)
* Trello Life List [http://bit.ly/life-list](http://bit.ly/life-list)

***

## About

This is the source code for the website of Phil Lennon.

This website has been made with my frontend workflow [Garrus v0.7.0](https://github.com/fephil/garrus).

## Install

* Install Node V4 LTS or Node V6,
* Run in Terminal: `npm i gulp-cli -g` (Gulp does not need to be installed globally),
* Navigate to the workflow folder in command line Terminal,
* Run: `npm i`.

Please note that there are a large amount of development dependencies to install, due to the 'all in one' nature of the workflow. It could possibly take a long time to install all the required modules.

### Optional Installs

In your code editor of choice, the following plugins are recommended but not required. Note the plugin names might be slightly different depending on your editor.

* editorconfig,
* linter,
* linter-handlebars,
* linter-js-standard,
* linter-stylelint.

## Usage

Run these tasks in your command line Terminal:

`gulp [--production] [--debug]`

`gulp deploy [--production] [--debug]`

`gulp auditcode`

`gulp audita11y`

* The `gulp` task builds the website, watches for changes and starts up a sever,
* The `gulp deploy` task builds the website without watching for changes or running the server,
* The `gulp auditcode` task runs various linting checks on the project source files,
* The `gulp audita11y` task builds the website and adds tota11y for accessibility checking,
* The `--production` flag builds minified assets with no sourcemaps,
* The `--debug` flag shows the files being created in each task (if the task has a pipe).
