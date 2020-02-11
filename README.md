# Nest.js-Building-an-API
Nest.js Building an API from Scratch

Installation#
To get started, you can either scaffold the project with the Nest CLI, or clone a starter project (both will produce the same outcome).

To scaffold the project with the Nest CLI, run the following commands. This will create a new project directory, and populate the directory with the initial core Nest files and supporting modules, creating a conventional base structure for your project. Creating a new project with the Nest CLI is recommended for first-time users. We'll continue with this approach in First Steps.


$ npm i -g @nestjs/cli
$ nest new project-name
Alternatively, to install the TypeScript starter project with Git:


$ git clone https://github.com/nestjs/typescript-starter.git project
$ cd project
$ npm install
$ npm run start
Open your browser and navigate to http://localhost:3000/.

To install the JavaScript flavor of the starter project, use javascript-starter.git in the command sequence above.

You can also manually create a new project from scratch by installing the core and supporting files with npm (or yarn). In this case, of course, you'll be responsible for creating the project boilerplate files yourself.


$ npm i --save @nestjs/core @nestjs/common rxjs reflect-metadata
Stay in touch#
Website - https://nestjs.com
Twitter - @nestframework
