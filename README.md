# Programming Foundations Lesson 2.1: String properties and methods, logic

## Exercise 1
a) Convert the string "Down the freeway rolls a wayward beer can" to UPPER CASE.

b) Convert the string "YOU SHOULDN'T HAVE TO SELL YOUR SOUL" to lower case.

Console log out the results.

## Exercise 2

Given the string "Blåbærsyltetøy": 

a) Extract the letters from start position 3 to potition 5 (including the 5), into a new variable.

b) Extract the last 8 letters, into a new variable.

c) Extract the first three letters, into a new variable.

Console log out the results.

## Exercise 3

Given the string "Blåbærsyltetøy": 

a) Extract the letter at position 2 into a new variable.

b) What is the unicode number for 'æ', 'ø', and 'å', respectivly?

Console log out the results.

## Exercise 4

Given the strings "Shout, shout!" and "Let it all out.", merge the two with a space between them, *without* using the string concatinator operator (`+`):

a) Using a string method.

b) Using a template literal.

Console log out the results.

## Exercise 5

Given the string (template): 

`London calling to the faraway towns 
Now war is declared and battle come down 
London calling to the underworld 
Come out of the cupboard, you boys and girls 
London calling now don't look to us 
Phony Beatlemania has bitten the dust 
London calling see we ain't got no swing 
'Cept for the ring of that truncheon thing.`

a) What is the index of the first occurance of "London calling"?

a) What is the index of the last occurance of "London calling"?

## Exercise 6

Given the following code, what is logged out (try first without coding it):

```js
let sum = 35;
if (sum % 10 == 0){
    console.log("a");
} else if (sum % 2 == 1){
    if (sum % 5 == 0 && sum % 2 == 0){
        console.log("b");
    } else if (sum % 5 == 0){
        console.log("c")
    } else {
        console.log("d")
    }
} else {
    console.log("e")
}
```
<!-- This exercise is taken from https://exlskills.com/learn-en/courses/javascript-fundamentals-basics_javascript/conditional-statements-zgrXFcSqdfIF/the-if-statements-YcHrGQKxvTOI/nested-if-statements-nSAoxbDFvMOq -->

Level 2: Is it possible to get output 'b'? Explain.
