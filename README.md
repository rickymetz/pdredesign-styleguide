#pdredesign-styleguide
=====================
##Changing the style guide

###Variables

Changes to existing variables and new variables are declared in app/styles/_variables.scss file.
###New Sass declarations

Adding new css declarations goes in the app/styles/_custom.scss file. Do not change exisiting bootstrap compenents.
=====================
##Technology
###Yeoman
This project is built on top of the Yeoman webapp generator.
###Bower
This project uses Bower for packagemangement.
###Grunt
This project uses Grunt for task running.
Use ````grunt serve```` to build a dev version and watch for changes (includes SASS, AutoPrefixer, and LiveReload).
Use ```grunt build```` to create a production version of the project.
