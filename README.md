# komenci

Komenci is a **React** Starter Kit built with the mininum packages needed to build real world applications:
 - [ReactJS](https://facebook.github.io/react/)
 - [React-Router](https://github.com/reactjs/react-router)
 - [Redux](http://redux.js.org/)
 - [Redux-Saga](http://yelouafi.github.io/redux-saga/)

## Features

Bellow are some of the main features available on the kit:
- [auto transpilation](https://babeljs.io/) - Modern JS working on most modern browsers
- [auto compilation]() - Prepare your code for development and production automatically
- [hot reloading]() - See the changes at your browser as you edit your source files
- [sync browsers]() - Sync multiple browsers for visual test of your application look and behaviour
- [unit tests]() - Automatically run unit tests every time you save a file
- [code linting]() - Make sure your code is following a defined standard

## Sample Application

To help you get started with React, this kit brings you a working example application with two main features:
- Authentication - Login Form that will rely on a api call to log user in
- Internationalization - Support multiple languages on your application
 
Because of the sample example the following packages are also included in the production code:
- Promise (bluebird)
- Internalionalization / Localization (intl - react-intl)
- Cookies (js-cookie)

## Installation

```
npm install komenci -g
```

Komenci was designed to work as a command line interface, and as such the recommended way is to install it globally so that the command it generates is available globally on your system.

## Usage

```
komenci [app-name] [options]
```

#### Options

##### `--path`

By default **komenci** install the application inside the folder where the command was invoked, if you want to create the project in a different folder from where you invoke your command you can use the `path` option:
e.g:
```
komenci sample-app --path=/projects
```

##### `--remove`

By default **komenci** comes with a sample app built with some functionality that is probably important for most applications, but if you want to start with the kit, but don't want the sample application you can use the `remove` option to:

- remove the entire sample application (e.g `komenci sample-app --remove=sample`)
- remove the authetication part of the sample application (e.g: `komenci sample-app --remove=auth`)
- remove the internationalization part of the application (e.g: `komenci sample-app --remove=l18n`)




