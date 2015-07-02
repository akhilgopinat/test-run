## Wipro Digital UI  Exercise

*To use sourcemaps, Sass 3.3.0 alpha must be installed: sudo gem install sass --pre

Getting Started

Make sure you have Node.js and Grunt installed:

Install Node.js from http://nodejs.org, or if you use Homebrew: brew install node
Install Grunt by running npm install -g grunt-cli
Install project dependancies with npm install. Make sure you're in the project root.
You may need to run the install commands as admin, so for Mac, use sudo npm install.

For more information on Grunt, see the Getting Started guide.

## Directory Overview
```
ProjectRoot/
│
├── css/
│   ├── sass/
│   │   └── global.scss
│   └── <package-name>.css
│
├── img/
│   └── src/
│
├── js/
│   ├── src/
│   ├── vendor/
│   ├── <package-name>.js
│   └── <package-name>.min.js
│
├── node_modules/
│
├── Gruntfile.js
├── package.json
├──.jshintrc
├──.gitignore
├── index.html
└── README.md
```

### File Structure

**`css/`** —

`sass/global.scss` will be compiled too `css/<package-name>.css`. Import all project Sass files in this file.

**`img/`** —

Any `.png`, `.jpg`, `.jpeg` .

**`js/`** —

JavaScript files placed in `src/` will be tested with JShint, concatenated and minified to the root `js/` dir. `vendor/` should be used for vendor scripts, such as jQuery. Vendor scripts will not be tested with JShinted, concatenated or minified by default.

**`node_modules/`** —

Required dependancies are installed here, do not add to version control.

**`Gruntfile.js`** —

This file contains all the tasks to be run. It's heavily commented so check it out.

**`package.json`** —

Define project settings in this file. All dependancies are listed here too.

**`.jshintrc`** —

This file contains options for JShint.

**`.gitignore`** —

A standard `.gitignore` file for ignoring files/folders from being added the repo.

**`index.html`** — Responsive HTML 
