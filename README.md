Startup project for trip planing and sightseeing stuff

Todo's

I needed somethign simple to keep track of my web searcher and to quicly add link's maps, plan my trip plus there has to be a way to save the places of intetrest add google maps widget add also the way to make quick notes and todo's. create page for view 

Adding build system using bower for require, backbone, jquery

## Setup

First, of course, download this repo. Then, from the Terminal (assuming Node.js installed), install RequireJS.

    npm install requirejs

Next, we need an easy way to deal with dependency management. We'll use Bower, from the guys at Twitter.

    npm install bower

Let's now install the dependencies for this project. I'm assuming that we're building a Backbone project, so I've listed RequireJS, jQuery, Underscore, and Backbone as dependencies.

    bower install

> Please note that we're using the AMD versions of both Backbone and Underscore to make the setup process as easy as possible.

When ready to build the project, run:

    build/build.sh

this will create a new `dist` directory, copy the files over, run the r.js optimizer on assets, and clean it the file structure a bit for production. Refer to `app.build.js`for configuration options.

### CSS Imports

If you're not using a preprocessor, feel free to modularize your stylesheets, and `@import` them into a master stylesheet. During the build process, r.js will merge these files together, so that you don't have to deal with any performance hits from using `@import`.

Add composer for building laravel using mysql or postgres or sql lite 