# es6-web-app-seed

This is a simple ES6 web app skeleton 

## Running the app 

To run the app, follow the steps. 

1. Ensure that [NodeJS](http://nodejs.org/) is installed. This provides the platform on which the build tooling runs.
2. From the project folder, execute the following command:

  ```shell
  npm install
  ```
  
3. Ensure that [Gulp](http://gulpjs.com/) is installed. If you need to install it, use the following command:

  ```shell
  npm install -g gulp
  ```
  
4. Ensure that [jspm](http://jspm.io/) is installed. If you need to install it, use the following command:

  ```shell
  npm install -g jspm
  ```
  
5. Install the client-side dependencies with jspm:

  ```shell
  jspm install -y
  ```
  
6. To run the app, execute the following command:

  ```shell
  gulp watch
  ```
  
7. Browse to [http://localhost:9000](http://localhost:9000) to see the app. You can make changes in the code found under `src` and the browser should auto-refresh itself as you save files.

  
## TODO
1. Add unit tests.
2. Add E2E test. 
3. Add lint 
4. Build to production gulp task.
5. Create a [yeoman generators](http://yeoman.io/generators/)

## Inspired by references: 
1. [Creating a Next Gen JavaScript Application with Aurelia](http://www.sitepoint.com/creating-next-generation-javascript-application-aurelia)
2. [Aurelia Skeleton Navigator](https://github.com/aurelia/skeleton-navigation)
