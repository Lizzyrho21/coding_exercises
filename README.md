# concept-roundup-javascript-python

This challenge review covers core programming concepts that apply to all programming languages. Here we will solve them in BOTH JavaScript and Python.

## Directions
* Create `index.html`,`style.css`, and `main.js` files in your project for JavaScript solution(s)
* Create a Python program that implements each solution as a separate function
* Code your answers to each of the 5 questions using the Standard Template described below
* All sample code below is in JavaScript but you will duplicate the same behavior in Python
* We will cover all solutions and concepts in class

> NOTE: Start with a separate JavaScript/Python file with a function called *main()*. This should be the first function called and point of entry for execution. All other code to accomplish whatever challenge should be in it's own function called from the main() function. No JavaScript/Python code should execute outside of a function. This pattern should be considered our 'Standard Template' for all of these exercises. Duplicate a similar pattern for Python solutions.
```
main() {
    // call exercise1(someParameter)
    // call excercise2(someParameter1, someParameter2)
    // etc.
}
```
Before you type ANY CODE, write out your steps to solve each exercise in each file. Use single line comments to pseudocode what you need to do to solve the problem *then* fill in the blanks.
```
// JUST AN EXAMPLE!
// Create an array
// Load objects into the array
// Iterate through each element in the array and print the element
```

### 1. Integer Numbers Range

Write a function in Javascript that takes two integer parameters `x1` and `x2` returns all the integers between them. If `x2` is lower than `x1` it should return -1. Provide appropriate User feedback.

### 2. Multiplications table

Write a function that writes in the console or browser the multiplication table (from 1 to 10).

![multiplication](./multiplication-table.png?raw=true)


### 3. Multiplications table on demand

Write a function that writes in the console or browser a multiplication table (in one column) of any number passed as parameter. Only go from 1 to 10 times the number passed in.

### 4. Calculations and Operators

Write a program that writes in the console or browser all the multiples of 23 less than 500 and at the end writes the sum of all of them. 

    Elements : 0 23 46 69 92 115 138 161 184 207 230 253 276 299 322 345 368
    391 414 437 460 483
    Sum : 5313

### 5. Write Your Own `max()` function

Define a function max() that takes two numbers as arguments and returns the largest of them. Use the if-then-else construct available in Javascript. Provide appropriate User feedback.

### 6: Text Manipulation and Arrays
Write a function that accepts a sentence of words all in lowercase, and returns every other word in all caps.  

ex. ```in a galaxy far far away``` -> ```in A galaxy FAR far AWAY```

### 7: Text Manipulation and Arrays
Write a JavaScript function that accepts a word in all lowercase or in all uppercase, and returns the word in the opposite case. Hint: see toLowercase()

ex. ```hello``` -> ```HELLO``` or ```HOWDY``` -> ```howdy```

### 8: Functions and Arrays

#### Return first n number of elements

Write a JavaScript function called `first()` to get the first n element(s) of an array. Passing a parameter 'n' will return the first 'n' elements of the array.

ex: 
```
console.log(first([7, 9, 0, -2],3));
console.log(first([7, 9, 0, -2],1));
```
Expected Output : 
```
[7, 9, 0] 
[7] 
```
### 9: Return last n number of elements

Write a JavaScript function called `last` to get the last n number of element(s) of an array. Passing a parameter 'n' will return the last 'n' elements of the array.

ex:
```
console.log(last([7, 9, 0, -2],3)); 
console.log(last([7, 9, 0, -2],6));
```
Expected Output : 
```
[9, 0, -2] 
[7, 9, 0, -2]
```
### 10: Array Manipulation
Write a JavaScript function to remove an element with a specific value from an array.

ex:
```
console.log(remove_array_element([2, 5, 9, 6], 5));
```
Expected Output:
```
[2, 9, 6]
```

### 11: Object Literals/Dictionaries and Arrays
Create a new empty array called ```pet_list```. Add 3 pet objects (via object literals) to the ```pet_list``` array (each pet should have a type, age and a color property) You can choose the pets.

Iterate the list of pets and print the properties for each pet

### 12 FIZZBUZZ
FIZZBUZZ is the classic Programmer's challenge often used as part of job interviews. 

User inputs the ending value (e.g. 100)

#### Your code should start at 1 and then iterate each number up to the maximum value based on what the user entered
* If the current number is evenly divisible by 3 you should print "FIZZ" *and* the number
* If the current number is evenly divisible by 5 you should print "BUZZ" *and* the number
* If the current number is evenly divisible by both 3 *and* 5 you should print "FIZZBUZZ" *and* the number 
* Otherwise, just print the number

### 13 Input with Conditionals

Ask the user to enter 1 for 'count down' and 2 for 'count up'. If they enter 1, ask them what they want to count down from and print out each number from the starting number to zero. If they enter 2, ask them what they want to count up to. Start from 0 and count up to the number by ones.

### 14 More Input with Conditionals

Ask the user to enter their name. If they enter *Kevin* say 'What's up Kevin'. If they enter *Danielle* say 'Hi Danielle!'. If they enter *Erin* say 'Good morning Erin!'. If they don't enter any of those names just say 'Hello [NAME]'.

### 15 Dog Class
Create a class called *Dog* with the properties name, breed, color, gender. Write the code to ask the user to add Dogs by prompting for each property. Create a new instance of the Dog class and add to an array/list. Keep asking the user to enter more dogs until the user enters *quit*. When the user enters *quit* iterate the array and print the details for each dog.
