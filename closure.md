CLOSURE

DEFINITION- All functions defined inside another function's scope are called closures.
That means a closure doesn't only have access to its own variables but also to outer function's variables
and global function's variables. Moreover it has access to the outer function’s parameters as well.
The inner function cannot call the outer function’s arguments object, 
but it can call the outer function’s parameters directly.

EXAMPLE--
function dispName (firstName, lastName)
{
var name = "Your name is ";

function dispFullName () {
return name + firstName + " " + lastName;
    }return dispFullName ();

}
dispName ("Balkar", "Dhilon"); 


External Rerences---
1. http://eloquentjavascript.net/03_functions.html
2. https://www.sitepoint.com/javascript-closures-demystified/
3. https://www.bing.com/videos/search?q=javascript+closure+&&view=detail&mid=9C6E6530AC24B4A278FE9C6E6530AC24B4A278FE&FORM=VRDGAR
