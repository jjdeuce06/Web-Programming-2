# Web-Programming-2

## Program Functionality
This program is meant to be a calculator. Two input fields will receive numbers, and the two numbers will be added, subtracted, multiplied, and divided whenever those numbers are changed. The numbers can be reset with the Initialize button

Skills learned in this program:
- First use of JavaScript functions and first use of the language in general
- Use of events, with the onchange and onclick events being used

## Program Implmentation
### HTML
- Title set to HTML calculator
- reset() function is called immediately as the program is loaded
- X and Y input fields initialized, with onchange calling the performfunctions() method
- Result fields of the various operations are initialized
- Initialize button is initialized, with onclick calling the reset() method
### JavaScript
- Global variables X and Y set to 20 and 4 to start (Instructed by the professor to do this)
- performfunctions() method
  - converts X and Y to integers
  - sets elements to the various operations based on the name of the HTML element
  - Checks if y is 0 to prevent an error before setting the division value
-  reset()
    - reset X and Y to 20 and 4 respectively and set the X and Y field to those values
    - call performfunctions() to reset result fields     
