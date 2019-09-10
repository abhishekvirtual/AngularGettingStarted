# Modules

In javaScript moduls are the way to manage code and prevent the to declary the functions and varibale in glabal name space. This approch in javaScript is known as the modular pattern which is a prt of creational design pattren

### Example

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

module.exports = taskRepo();

This is an example of ES2015 modules featurs where we are exporting somthing as a module.

# Angular modules

Angular module are have much more then a simple Js module it raps the application in cohensive blocks of space for managing application in a better way there are three types of module by this way

## Main Module (App module).

## Feature Modules.

## Shared Modules.
