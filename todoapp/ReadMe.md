#Real-Time Polymer Todo App
######Built using [*Polymer 1.0*](https://www.polymer-project.org/1.0/docs/)

####Prerequisites
  * [Node.js/npm](https://nodejs.org/en/download/)
  * [Bower](http://blog.teamtreehouse.com/getting-started-bower) - installed using npm
  * [Polymer v^1.0.0](https://github.com/Polymer/polymer/releases) - installed using bower

####Polymer element general template
```
<!DOCTYPE html>
<html>
<head>
    <link href="../bower_components/polymer/polymer.html" rel="import">
    <!-- Element Imports -->
</head>

<dom-module id="element-name">
  <!-- 
  dom-module - it is the root of the custom element -->
  <style>
    /* CSS rules for your element */
  </style>
  <template>
    <!-- local DOM for your element -->
    ...
  </template>
</dom-module>
<script>
  Polymer({
    is: "element-name", //registers the custom element as a Polymer element.
    properties: {
        ... //attributes of the custom element (if any) are declared here
        },
    ready: function(e){
        ...
    }
  });
</script>
```
####References
  * https://scotch.io/tutorials/build-a-real-time-polymer-to-do-app
  * https://elements.polymer-project.org/
