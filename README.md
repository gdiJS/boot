# GDI.js initilization scripts

## Glossary
prototype: extension functions to built-in v8 objects (referred as basics, prototype.string.js, prototype.number.js ...)

constants: static globals like setTimeout(), setInterval()  (constants.js)

natives: functions that processed at application layer  (native.xx.js)

objects: functions that processed at v8 layer (obj.xx.js)

modules: built-in modules that utilizes the native functions (mod.xx.js)

## Execution Hierarchy
Filename prefixes are matter, execution follows that line

constants -> prototypes -> objects -> natives -> modules

## Deployment
After the revision launch merge.bat and copy "engine.js" to gdi.js source folder
