start.css
=========

A collection of best practice CSS to be placed in a 'start with' css file for any of your project.

Why ?
-------
Why start.css and not 'normalise.css'? Because 'normalise.css' may not be sufficient. Your project may require other css files tha you may require in almost all of your projects that gives a quick start - right start. 

This may include, having a normalise.css as a dependency, so why not! Let start with that and check if that is the case and is that sufficient.

This is going to be an evolving idea.

CSS structure could be 
start.css
 @import url('normalise.css');
 @import url('project.common.css');
 
 
