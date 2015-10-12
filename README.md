# SPA Browserify Boilerplate ⚡
Basic structure to building classic SPAs with browserify.
# Why?
It makes no sense having to recreate the basics everytime I start a new project, a prototype or a simple experiment.

#How?
Just clone the repo, run `npm start` and watch the magic happen. The command relies on the scripts inside the package.json file to build all the basic files for you.

#What?
A simple tool built to automate the repetitive process of creating those very basic files I need on every new project.

#What else?
Inside the package.json file you can find some useful scripts. Besides `npm start`. the two other commands you may want to use often are:

 * `npm run watch` – starts watching for changes on your javascript and stylus files, keeping the output javascript and css files always up to date
 * `npm run sync` – it's like watch but for the browser, firing a browser refresh every time a change is made in the output javascript and css files
 * `npm run watch-sync` – a shortcut to call both watch and sync commands
 * `npm run build:deploy` – builds the all files for production, making the public folder ready for deploy

#References?
Here https://goo.gl/dV0Pke is a brief summary (PT-BR only) of the studies that I did to learn how to build this tool.