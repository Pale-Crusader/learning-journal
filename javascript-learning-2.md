### Pragamming

#### Producing a process with a series of steps with purpose in order

Expectations Teach Robot

lift jacket with hands
orientate jacket to position so left arm and hand may enter from the inside of the jacket enter the left sleeve while freely hanging
insert left arm into the inside of the left sleeve until wrist exits the cuff
use right arm to reach around your back to grab the free hanging portion of the jacket with inside orientated towards your back
orientate jacket to position so right arm and hand may enter
from the inside of the jacket enter the right sleeve while freely hanging
insert right arm into the inside of the right sleeve until wrist exits the cuff  
reach up to below back of neck and find fabric of the hood then grab hood
use hands to grab bottom portions of the zipper and extrand downward to straighten
use hands along lightly along zippers to locate zipper slider and pull tab
use the hand which located pull tab to pull it down the zipper to the bottom
use the hand which located slider to pull it down the zipper to the bottom
orientate pull tab and slider so they interconnect
use hand to pull the pull tab to top of zipper

The above did not work due to copy paste error and error in interpreting the hood comand

## Reading 07

### Purpose of reading

#### Understanding some programing basic concept
Javascript makes interactive.
* Allow content access
* Modifies Content
* Program rules
    1. could check versions
    2. could calulate
    3. could add animation
    4. could do a __LOT__ of things
* reate to events
    1. button presses
    2. link clicks
    3. cursor hovers over elements
    4. could react to a __LOT__ of things

#### Examples of Javascript
* slideshows
* forms
* reload part of page
* filtering data

Had an HTML refresher see [My previous reading](https://pale-crusader.github.io/learning-journal/html-reading-01)

Had an CSS refresher see [My previous reading](https://pale-crusader.github.io/learning-journal/css-reading-01)

A script is a set of instructions in order used to achieve an objective. like recipies handbooks or manual

the inatructions are step by step

Writing a script requires your goals to be set then a list of tasks to reach those goals

1. define the goal
2. design the script 
3. code each step

knowing the goal you can work out what you need to do to achieve it

they are then broken into steps in order

#### Learn the language itself

##### Syntax
The structure or gramar of the instructions


##### Vocabulary
Words thee computer understands

human vocabulary
Functions performs a task allows ease of reusing, stability (if tested, it does one thing and one thing well, control, security, debugging, named as specific for troubleshooting, easier to share
Expressions evaluate into results
Operators create a values from one or more vales
* a sub set of Operatios is Arithmetic Operations which is like it sounds
* a sub set of Operatios is string operationswhich is the + symbol

Scope  
When variables are siting outside of functions are globally use and can be accessed throughout the project and could be any where so tracking it down makes it hard

inside the fuctions they are within function scope
calling a function adding parethesies next to the function which may be filled with variables with arguments.L
var means variable
operators which allow the creation of a values from one or more values

#### Syntax
function name(parameters, which may be blank){
    code block

return statment;
};
#### Exmaple
function addNum (a, b){
    var a;
    var b;
    return a + b;
}
#### Calling Example Function
adNum (2, 5) //argument

Functions make building blocks of code, it is good to make and reuse them.

= asigns
== compares bolian

When you wraping a codeblock and return statement within a function is called encapulation, and protects the code from running unless the function is called upon

Defining the Goal and Designing the scriptand important and must be done.

Sketching a flow chart is an excellent way to visualize operations and the series of tasks towards the goal.


#### You can declare a variable as a function

var showOrder = Function



#### Become familar how it is applied

If you place access in the head within the html you can use the script tag within the body to call a Function.


Include for troubleshooting only in function
console.log("We are printing what our variable is holding are holding", Item + Item + Item);

== is equal to
!= is not equal to
=== strict equal to
> greater than
> less than
>= greater than or equal to
<+ less than or equal to

Structure of Comparison operations

example
(score>=pass)

create variable and then assign or assign at same time like this:

var pass = 50;
var score = 90;

how used
var hasPassed = score >= pass;

always is a boolean result.  true or false

what is being compared (operand) does not require single value or variable name

When comparing two comparison it is done like this

var comparison = (score1 + score2) > (highscore1 + high score2)

logical operators 

&& test more than one condition
|| test if at least on is true
! logical not

This are logic gates

if statements evaluate a condition for if it is true
else gives a second code block a chance to run if false
switch always has a value assigned too it with parenthesis then lists cases fore this value in the code block

switch (valuename) {
	
	

}



while loop are for when you don't know how many, like username and password

example 

while (Operation){

};


var quanity = function() {
	var answer = prompt("howmany do you want?");
	
	for(var i = 0; i < cart.length ; i++){
	console.log(i);
	}
}

i is for index positions with list aka array
i is a placeholder for index

lists are within []
indexes start counting at 0
list is named cart with a cart.length is 
i++ increaments after running block of code

defining a list 

var list = [1,2,3,4,5,6,7]


