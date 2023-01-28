# build-react-app

Replacement for CRA

1. In a terminal pointing to the base folder of your project, run the following command:

npm init -y

2. Use the following commands to install required dependencies:

npm i --save-dev webpack webpack-cli webpack-dev-server babel-loader @babel/preset-env @babel/core @babel/plugin-transform-runtime @babel/preset-react @babel/eslint-parser @babel/runtime html-webpack-plugin

npm i react react-dom

3. Add the following to "package.json":

"scripts": {
"start": "webpack-dev-server .",
"build": "webpack ."
}

4. Run npm start. It should be all ready to go!
