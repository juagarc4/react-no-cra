## Introduction

This is only a small PoC to see how you can install and configure a react application and webpack without using Create React App.

**Important**: This is not intended to go to production since the configuration of webpack can become really copmplex if one wants to fine tuning the wohle configuration.
The damages in terms of security or performance of a wrong configuration can have a huge impact in your application.

If you don't need to configure Webpack, we recomend the use of **create-react-app** (aka CRA).
If want to configure webpack and use CRA too, we recoment the use of **craco** (Create React App Configuration) => https://github.com/dilanx/craco

## Init project and install dependencies

1. Create project structure
   project_name
   |-- src
   |-- public
2. Go into "project_struture" and execute:

- **npm init -y** to create packajes.json
- **npm i --save-dev webpack webpack-cli webpack-dev-server** to install webpack
- **npm i --save-dev babel-loader @babel/preset-env @babel/core @babel/plugin-transform-runtime @babel/preset-react @babel/eslint-parser @babel/runtime @babel/cli** to install babel
- **npm i --save-dev eslint eslint-config-airbnb-base eslint-plugin-jest eslint-config-prettier path** to install linters and path
- **npm i react react-dom** to install react

6. Create .babelrc

## Configure Basic React App

1. Create files src/index.js and src/App.js

## Configure webpack

1. Create file webpack.config.js

## Build the project

1. Run pnpm build

## Start the app

1. Run pnpm start
