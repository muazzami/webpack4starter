# Webpack 4 Starter
It is a starter project for simple HTML/CSS/JS project. When developing regular html sites or landing pages we can take advantage of these modern tools and speedup the development process. I really like to use SCSS to write CSS and if its post compiled with autoprefixer and minified as well, what else you need?


### This project starter includes: 
 1. Webpack configuration
 2. Convert SCSS to CSS
 3. Managing static resources

## Webpack Plugins used
 1. html-webpack-plugin
 2. mini-css-extract-plugin
 3. copy-webpack-plugin
 4. clean-webpack-plugin
 5. optimize-css-assets-webpack-plugin
 6. uglifyjs-webpack-plugin

## Webpack Modules used
 1. css-loader
 2. sass-loader
 3. postcss-loader
 4. file-loader
 5. style-loader

## NO ES6 Inlcuded
Babel compiler is not included, if your project requires modern javascript, I will suggest to [check this repo](https://github.com/thejsdeveloper/webpack4-setup).

## How to Get Started? 

### Clone Repository
> Run `git clone https://github.com/muazzami/webpack4starter.git`

### Change directory
> cd `webpack4starter`

### Install dependencies
> yarn 

### Run development server

> Run `yarn start` for a dev server and it will run at `http://localhost:8080/`. 
It will automatically reload when changes to files are made.

### Build

> Run `yarn build` to build the project in development mode. 
> Run `yarn build:production` to build the project in production mode. 

The build files will be stored in the `dist/` directory.