# Basic project template

A barebones, project template with all the initial files for any HTML/CSS and JS project.
Geared towards the Frontend developer using
- sass via nodesass preprocessor (sassy scss)
- node.js for the development toolkit

## Pre-requisites
1. For mac HomeBrew should be installed
2. Node.js and npm
3. Liveserver could be installed globally

## Initializing the Project

The development commands are:
0. 'npm init' : to initialize package.json file
1. 'npm install' : to install all dev dependencies. Should you have issues installing from package.json. e.g. the versions are outdated, then install manually
    - % npm install autoprefixer --save-dev
    - % npm install concat --save-dev
    - % npm install node-sass --save-dev
    - % npm install npm-run-all --save-dev
    - % npm install postcss-cli --save-dev

2. 'npm run start' or 'npm start' : watches for any changes in the sass files and recompiles the main css file. Also reloads browser on all html/css/js file changes. Use in development
3. 'npm run build:css' : compiles the main css file, adds prefixes and returns a minified compressed file, to be used in production. (Rename style.comp.css to style.css or main.css)


### Helpful Terminal Commands
% 'npm list -all'  -> Lists all installed packages in current project, dependencies and sub-dependencies
% 'npm list --depth 1' -> List installed packages and their installed dependencies to 1 level, 0 to list only top level dependencies
% 'npm list -g' -> List all packages installed globally