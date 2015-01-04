# SocialHead


## Purpose
A social networking app built for internal networking built on MEAN stack.



## Stack
#### Platform, tools & Frameworks - Client Side
You need to install all these tool to get started with the development:
* [Git] (http://git-scm.com/downloads) for windows/Mac
* IDE WebStorm/Intellij
* Visual Studio 2013 Express (recommended for node debugging)
* NodeJS tools for Visual Studio (http://nodejstools.codeplex.com/)
* Node Package Manager [Node.js] (http://nodejs.org/download/)
* MongoDB (http://www.mongodb.org/downloads)

#### Libraries - Client Side
* [Angular UI Bootstrap] (http://angular-ui.github.io/bootstrap/)
* [ng-grid] (http://angular-ui.github.io/ng-grid/)
* [Angular-cache] (http://angular-data.pseudobry.com/documentation/api/angular-cache/angular-cache)




## Installation/Setup
### Open command prompt and install following things:
* Javascript Build Manager [Grunt.js] (http://gruntjs.com/)
```
npm install -g grunt-cli
```
* Nodemon (for node file monitoring and auto server refresh)
```
npm install -g nodemon
```
* [Bower] (http://bower.io/) Package Manager
```
npm install -g bower
```

### Get the Code
Either clone this repository or fork it on GitHub and clone your fork:
```
cd <dev directory>
git clone https://github.com/hiteshAneja/SocialHead.git
git remote add <remotename> https://github.com/hiteshAneja/SocialHead.git
git fetch <remotename>
cd SocialHead
```

Install all the node modules. Run following command
```
npm install
```

Install all the bower libraries. Run following command
```
bower install
```




## Build
To build the project, run the grunt command
```
grunt
```
it will create the distributable copy in dist folder.



## Run
If in Visual Studio, use f5 to run the app
For Manual run, run the following command
```
nodemon app
```
Open browser and go to http://localhost:1337/
