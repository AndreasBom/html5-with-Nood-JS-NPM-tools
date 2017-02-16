# Importand tools needed for modern website

1. We used Bower for this startup template. According to bower official website "Web sites are made of lots of things — frameworks, libraries, assets, and utilities. Bower manages all these things for you."
Here we have used bower_components and inluced all the dependencies in bower.json file.
{
  "dependencies": {
    "angular": "angularjs#^1.6.2",
    "bootstrap": "^3.3.7"
  }
}

as you can see we have Angular JS, Bootstrap and with bower component you will also get JQuery.

2. We used nood module which you can esily use via npm with is given in package.json

"devDependencies": {
    "grunt-contrib-concat": "^1.0.1",
    "grunt-contrib-uglify": "^2.1.0",
    "grunt-contrib-watch": "^1.0.0"
  }
  
  Here you can see uglify contact and watch
  
 3. You will see GruntFile.js where we configured contact, uglify, watch and sass etc
 Note: for sass you need to install Ruby on you computer, and run Sass from Ruby terminal 
 
 #How to run this template?
 
 In order to run this template you need to install nood, npm and bower on your computer.
 Just clone the repo and open your repo in command line.
 
 1. npm init
 2. npm install
 2. bower install