# AngularJS / SailsJS / Restangular generator
[![Build Status](https://secure.travis-ci.org/chiefy/generator-sails-angular.png?branch=master)](https://travis-ci.org/chiefy/generator-sails-angular)

## Discontinued! ##
Looks like the SailsJS team is [starting a tooling project for AngularJS](https://github.com/balderdashy/angularSails), so I might try to help out there instead of updating this out-of-date project.

## Requires Sails 0.8.x
I am aware that the project isn't compatible with the latest versions of SailsJS, I am planning on fixing this ASMKLM (As Soon As My Kids Let Me)

Generates a scaffold of a project based off of the latest generator-angular:app and includes: SailsJS for creating a simple RESTful API backend, Restangular for consuming it inside of AngularJS & Twitter Bootstrap. 

## Getting started
- Make sure you have [yo](https://github.com/yeoman/yo) installed:
    `npm install -g yo`
- Install the generators: `npm install -g generator-sails-angular generator-angular`
- Create project directory and `cd` into it: `mkdir my-new-project && cd $_`
- Run: `yo sails-angular [app-name]`
- To run project: `sails lift`
- To test: `grunt test`

## Known Issues
 * Grunt live-reload, server do not work.
 * Since I'm using Restangular the generator-angular questions re: ng-resource are redundant since it's never used.
 * Not sure if anything CoffeeScript or SASS works (sorry!)
 
## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License)
