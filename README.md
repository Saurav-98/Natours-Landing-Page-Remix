# SASS Project

## Steps to Install and Setup SASS Project

1 - install node js
2 - run "npm init"
3 - Install "node-sass" { npm install node-sass --save-dev }

4 - make sass folder in root and create a main.scss file in sass folder and move all the css code on that main.scss file
5 - create a new Script in package.json "compile:sass": "node-sass sass/main.scss css/style.css"
6 - run the command - npm run compile:sass

7 - adding a watch flag to check for changes automatically - "compile:sass": "node-sass sass/main.scss css/style.css -w"

8 - install live-server - "npm i live-server -g"
9- create a script in package.json for automatic reload after every change

### SASS 7 in 1 Architecture

create 7 folders inside sass folder namely
1 - base - \_animations.scss , \_base.scss, \_typography.scss, \_utilities.scss
2 - abstract - \_functions.scss, \_mixins.scss, \_variables.scss
3 - layout - \_header.scss
4 - component - \_button.scss
5 - pages - \_home.scss
6 - theme
7 - vendor

split the entire code in these files as code structure and definition.

import all the partial \_scss files into main.scss

## SASS Concepts

1- Use of Variables , for Colors
2 - Use Scss Nesting
