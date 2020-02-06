### Notes about java learning

### [Main Page](https://pale-crusader.github.io/learning-journal)

```var today = new Date();  ```
// I had a colon instead of a semi colon here and that prevented it from running after I moved the html to the master branch of Starter code.  
// var is variable today is what we define, equal is for assigning, new is another function parentheses is a call  
var hourNow =today.getHours();  
// creating another variable and the function references previously defined variable. The period is another function   
var greeting;  
// just making another variable so we can use it

```if (hourNow > 18) {  
    greeting = 'Good Evening!';```

// defining a logic function to extract information from hourNow variable which will define gthe variable greeting 'if something is rapped in a quote it is a string'.  If condition is true the code runs. The section of code between the curly braces is a block of code.  

```} else if (hourNow > 12) {  
    greeting = 'Good Afternoon!';  ```

// if not the variable is yet Assigned by the above blocks of code it proceeds to the next. If it is satified it stops there.

```} else if (hourNow  > 0) {
   greeting = 'Good Morning!'; 
} else {  
    greeting = 'Welcome!';
}```

```document.write('<h3>' + greeting + '</h3>'); ``` 

// above is a function which concatenating the previously assigned variable

// Numbers and strings are different types of variables. a number can be a string if it is surrounded by ''


I was hard pressed during this portion. I think when I asked about the pathing of whether the add-content.html should be within the C01 directory I wasn't clear and that with the addition of mistyping a color in line 1 instead of a semi colon road blocked me, but I learned a lot during the lab, and the vocabulary from reviewing the reading above helps. Also don't copy paste this code it has extra spaces which will break it.  lol