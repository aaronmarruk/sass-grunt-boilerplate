Sass Grunt Boilerplate
======================

This is an example boilerplate for getting started with Sass, JS and Grunt. If you don't have Grunt installed, you will need to install the Grunt CLI

    npm install -g grunt-cli
    
Once that has been installed, you will be able to use Grunt. To find out more about Grunt, please see the [Grunt Website](http://gruntjs.com/getting-started)

## Getting started

To get started, clone or download this into your cwd. Inside Gruntfile.js, you will see a minimal setup for working with sass / compass, and a basic setup for js minification – edit this file to reflect your current setup.

## Tasks

There are 2 tasks set up – a default task for developmemt, and a production task for taking care of production code.

### Default

The default Grunt task watches for SASS changes and compiles into main.css when changes to css are saved.

    grunt

### Production

Running the production task minifies SASS / JS into production-ready main.min.css and main.min.js files respctively.

    grunt prod

