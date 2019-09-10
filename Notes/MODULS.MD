# What is angular

Angular is modular , it is collection of libarary each libaray is a module made up with various relared featured modules when we need some thing with angular we import it from related module

https: //www.npmjs.com/~angular this link has the all angular libabry packages and modules.

# Modules

In javaScript moduls are the way to manage code and prevent the to declary the functions and varibale in glabal name space. This approch in javaScript is known as the modular pattern which is a prt of creational design pattren

### Example

```
var taskRepo = function(){
var db = {};
var get = function(id){
console.log('getting data for id :'+id);
return{
name:"my task name"
}
};
var save = function(task){
console.log('Saving '+ task.name +" to db");
}
//reveling pattern in module pattern
return {
get:get,
save:save
}
}
```

module.exports = taskRepo();

This is an example of ES2015 modules featurs where we are exporting somthing as a module.

# Angular modules

Angular module are have much more then a simple Js module it raps the application in cohisive blocks of functinality for managing application in a better way there are three types of module by this way. for each angular module we declare number of component and dependencies needed by thoes component . each component we declayer is belongs to only one angular module

## diffrence in ES2016 and Angular Module

ES module are the code file which is import and export somthing

NG modules Code files that organize the application in cohesive blocks block of functinality.

ES moudule organize the code files

NG module organize the application

ES module modularize our code

NG module modularize our application

ES Promots code reuse

NG Promotes boundry in our application

## Main Module (App module).

## Feature Modules.

## Shared Modules.

# Angular Component

Angular Component = Template (HTML , Data Bindings) + Class(Mathods and properties) + metadata (Decorators);

# Angular Decorators

are the function which adds matadata to the class, it's members, or its method arguments

prifixed with an @

Angular provieds a build in @Component()
