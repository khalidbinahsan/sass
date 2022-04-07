# How to install sass
First of all install node js on your machine then run the command
```bash
npm install -g sass
```
## Compile folder
This is very important to compile folder. Run this command by mentioning your input.scss and output.css folder.
The watch flag tells Sass to watch your source files for changes, and re-compile CSS each time you save your Sass.
```bash
sass --watch input.scss output.css
```
After end of cookies start again sass compile run this command
```bash
sass --watch app/sass:public/stylesheets
```
