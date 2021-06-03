# October - JavaScript Review

## Javascript Exercises 

- https://developer.mozilla.org/es/docs/Web/API/Console/log

### Integer Numbers Range

Write a function in Javascript that having two integers `x1` and `x2` returns all the integers between them. If `x2` es lower than `x1` it should return -1

### Multiplications table

Write a function that writes in the console the multiplication table (from 1 to 10)

![multiplication](./multiplication-table.png?raw=true)


### Multiplications table on demand

Write a function that writes in the console the multiplication table (in one column) of any number passed as parameter

### Calculation

Write a program that writes in the console all the multiples of 23 less than 500 and at the end writes the sum of all of them

    Elements : 0 23 46 69 92 115 138 161 184 207 230 253 276 299 322 345 368
    391 414 437 460 483
    Sum : 5313

### `max()` function

Define a function max() that takes two numbers as arguments and returns the largest of them. Use the if-then-else construct available in Javascript.

### `maxOfThree()` function

Define a function maxOfThree() that takes three numbers as arguments and returns the largest of them.

### `isVowel()` function

Write a function that takes a character (i.e. a string of length 1) and returns true if it is a vowel, false otherwise.

### Hexadecimal 

Writes a function that convert a hexadecimal color, "blue" for example "#0000FF" in its RGB representation rgb(0,0,255)". Give the function the name getRGB() and test it with this code

_Hint: https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String/split_


    >>> var a = getRGB ('#00FF00');
    >>> a;
    “rgb(0,255,0)”;


### Hexadecimal enhanced

Improves the previous function so besides the conversion also identifies some basic colors:
- Black: #000000
- White: #FFFFFF
- Red: #FF0000
- Green: #00FF00
- Blue: #0000FF

So the result can be (for these cases):

    >>> var a = getRGB ('#00FF00'); 
    >>> a;
    “rgb(0,255,0)   verde”;

## Create a user feedback form using prompt
You can use an HTML form or console prompts to collect the 3 pieces of required information. 
Name, issue, and steps to reproduce the error.

- Prompt for the User's name
- Prompt for the description of the issue they are experiencing
- Prompt for the steps that can be used to re-produce the user's issue
- If the user enters a blank string *for any property*, display an alert to let them know all fields must be populated, and then restart the iteration of the loop so they can reenter all 3 fields again.
- Keep prompting the user *until all 3 fields are provided* otherwise make user start over and enter all 3 fields again.

Once all 3 values collected, use a template literal that displays the entered information using a `confirm` dialog box.
The confirm box should display the information entered.

![Example Confirm Output](./confirm.png)
