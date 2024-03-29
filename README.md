# Angular Boilerplate - item search/selection


### Setup
The base setup is always the same and based on a mix of the yeoman generator-angular(LINK) and generator-angular-fullstack(LINK).

**Angular** dependencies with **HTML**, **SASS** with **Bourbon**, **ui-bootstrap**, **bootstrap css**, **font-awesome css**, and **normalise.css** ( no jquery ).

The different branches each contain another example.


### fruit selection example
The master branch contains a fruit selection/shopping example with a angular-bootstrap typeahead and panels.

The logic is stored in a Fruit model and FruitManager (factories).

The search and selection view are capsulated in separate components as directives with their respective controllers, views and styles.


### Installing

##### Install npm (the node package manager)

[http://nodejs.org/
](http://nodejs.org)

(tested with npm 1.4.24)

##### Install bower and grunt globally


`$ npm install -g grunt-cli bower`

If you have installed Grunt globally in the past, you will need to remove it first: npm uninstall -g grunt

##### Load the npm modules
(mostly for the grunt tasks and sass compiling)

`$ npm update`

##### Load the bower modules

(angular,bootstrap,...)

`$ bower update`

##### Optional: Sass
Depending on the grunt sass task, installing ruby's sass compiler might be neccessary

`gem install sass`