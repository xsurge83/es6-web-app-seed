# es6-web-app-seed

This is a simple ES6 web app skeleton. 

## How it works 
  Uses [jspm][jspm] as a universal package manager to download (see `config.js`):
  
   1. [systemjs][systemjs] - universal module system. See `config.js`
   
   2. [ES6 module loader](es6-module-loader) - ES6 module loader 
   
   3. [traceur](https://github.com/google/traceur-compiler/) and traceur runtime  -  compiles ES6 features within browser 
   
  During `gulp build` step uses [babeljs](https://github.com/babel/babel) to compile from ES6 to ES5 system module to the
  `dist` directory. You can create other build steps for commonjs and amd compilations.  
   
  
## Running the app 

To run the app, follow the steps. 

1. Ensure that [NodeJS](http://nodejs.org/) is installed.
2. From the project folder, execute the following command:

  ```shell
  npm install
  ```
  
3. Ensure that [Gulp](http://gulpjs.com/) is installed. If you need to install it, use the following command:

  ```shell
  npm install -g gulp
  ```
  
4. Ensure that [jspm][jspm] is installed. If you need to install it, use the following command:

  ```shell
  npm install -g jspm
  ```
  
  jspm is a universal package manager used with [systemjs][systemjs]
  
  
5. Install the client-side dependencies with jspm:

  ```shell
  jspm install -y
  ```
  
  
6. To run the app, execute the following command:

  ```shell
  gulp watch
  ```
  
7. Browse to [http://localhost:9000](http://localhost:9000) to see the app. 
   You can make changes in the code found under `src` and the browser should auto-refresh itself as you save files.

  
## TODO
1. Add unit tests.
2. Add E2E test. 
3. Add lint 
4. Build to production gulp task. See https://github.com/jspm/jspm-cli/wiki/Production-Workflows 
5. Create a [yeoman generator](http://yeoman.io/generators/)

## Inspired by references: 
1. [Creating a Next Gen JavaScript Application with Aurelia](http://www.sitepoint.com/creating-next-generation-javascript-application-aurelia)
2. [Aurelia Skeleton Navigator](https://github.com/aurelia/skeleton-navigation)

[systemjs]: https://github.com/systemjs/systemjs  
[jspm]: http://jspm.io
[es6-module-loader]: https://github.com/ModuleLoader/es6-module-loader
