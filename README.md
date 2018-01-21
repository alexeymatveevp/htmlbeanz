HTMLBeanz is an HTML java objects runtime editor.

It's designed to be integrated into any java **web** application and provide an embeddable view to edit any java runtime objects configured as input to this view.

## Features
### Type-specific edit widgets
Several types are supported to be presented in the view

* All primitives - numbers, booleans and other
* Strings
* Lists, Sets and Maps
* Any complex object fields (according to javabeans convention)

The properties which are not recognised will simply not be presented

### Modify collection contents
It's possible to add / remove item from the list. If the list contains object which can be of
different types then the choice of object type will be suggested when adding item.

(item type choices are scanned in application classpath)

## Examples
#### view example
<img src="https://github.com/davidluckystar/htmlbeanz/blob/master/screenshots/1.png" width="40%" style="display: inline-block">

#### edit single property
<img src="https://github.com/davidluckystar/htmlbeanz/blob/master/screenshots/2.png" width="40%" style="display: inline-block">

#### search properties
<img src="https://github.com/davidluckystar/htmlbeanz/blob/master/screenshots/3.png" width="40%" style="display: inline-block">

#### add item to list
<img src="https://github.com/davidluckystar/htmlbeanz/blob/master/screenshots/4.png" width="40%" style="display: inline-block">
