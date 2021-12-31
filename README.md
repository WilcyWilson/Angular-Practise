# What is Angular.
- JavaScript Framwork to develop single page web application.

# Angular Versions.
- AngularJS(Angular 1) version is the different one. From Angular2 6 months with small increment

# Project Setup.
- ng new project-name.

# Editing the First App.
- Editing app.component.html and using data binding editing app.component.ts.
- Editing app.module.ts and importing new package property through modules: 

# Basic Project Setup using Bootstrap
- Install Bootstrap with npm using --save to install bootstrap locally in the project.
- Then go to angular.json to configure the style.css and point it to node_module/bootstrap/bootstap_min.js

# Adding Component
- We create new folder in app folder and inside that we create componentname.component.ts and here we import Component decorator feature to enhance features of our class and use metadata.

# Registering Component in Module
- We need to register our new Component in module in the declaration property. 
- We need to import the component to make since we are using typescript.

# Adding styles, templates to component.ts to add inline css and template
- Can use templateUrl or template
- Notice style is an array
- Use back tick ` to write multi line.

# Different ways to use selector
- Class Selector
- Attribute Selector
- Default Element Selector

# Data Binding
- Communication between TypeScript and html template
- TypeScript to template commmunication through string interpolation, property binding.
- Template to TypeScript communication through event binding.
- Two way data binding where both communication can occur simulataneously