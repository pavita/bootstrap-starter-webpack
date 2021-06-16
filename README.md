# Bootstrap 5 + WebPack 5 Starter Pack

Basic front-end project setup for front-end project using [Bootstrap Framework](http://getbootstrap.com/) in version 5 and uses [Webpack](https://webpack.js.org/) in version 5

## 1. Requirements

[Node.js](https://nodejs.org/en/) or [Yarn](https://yarnpkg.com/) to be installed on your system. 

## 2. Quick Start

1. Clone the repository into a new folder for your new project.

    ```bash
    git clone git@github.com:pavita/bootstrap-starter-webpack.git my-project
    ```

2. Remove the .git directory to add your own CVS later.

    ```bash
    rm -rf .git
    ```

3. Update the package.json.

    ```JSON
       {
         "name": "my-project",
         "description": "A description of my new project",
         "author": "Your Name",
         "license": "MIT"
       }
    ```

4. Install needed dependencies

    ```bash
    yarn install
    ```
    ```bash
    npm install
    ```

5. Run webpack

    Start Webpack with localhost. it will watch for changes in JS and SCSS files, to recompile the needed assets.

    ```bash
    yarn start
    ```
    ```bash
    npm run start
    ```

    Start Webpack and only tell it to watch for changes in JS and SCSS files, to recompile the needed assets.

    ```bash
    yarn dev
    ```
    ```bash
    npm run dev
    ```

    If you want to compile all assets for production usage, run the following command. production mode will compiles all of the assets in a minified version, to deliver smaller files for your users.

    ```bash
    yarn build
    ```
      ```bash
    yarn run build
    ```
