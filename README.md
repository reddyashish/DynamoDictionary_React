# DynamoDictionary

Dynamo Dictionary development repo

Live version here: http://dictionary.dynamobim.com

## Installation
- In root directory, type ```npm install``` into the command line.
- In public directory, ```run bower install mocha```, ```bower install requirejs``` and ```bower install blanket```. Make sure Bower package manager is already installed.
  These dependencies will be downloaded into a new folder 'bower_components'.

## Run in Development Mode
- In root directory, type ```npm run start``` into the command line.

## Deploy to Autodesk

- confirm that `homepage` in `package.json` is set to `http://dictionary.dynamobim.com/`. The developer may change this address depending on the staging environment.

- In root directory: ```npm run build```

- Copy files from `build` folder and place into the root directory of the [Autodesk Dynamo Dictionary repo](https://github.com/DynamoDS/DynamoDictionary), in the appropriate `branch`.
