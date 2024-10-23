# Code Challenge: Diagnostic

## Instructions

1. Clone down this assignment to your local environment.
2. Code your solutions to the problems in this `README.md` file using JavaScript in `index.js`.
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Problems

1. Write a function named `sum` that takes in a string of digits, the function should return the sum of each digit in the string. You can assume there will be no spaces in the given string, you should return an integer. 
    
    ```jsx
    sum("123") // returns 6, because 1+2+3 = 6
    sum("2501") //returns 8, because 2+5+0+1 = 8
    ```
    
2. Write a function `isNumWithinRange` that takes in three integer arguments, a number, a min number, and a max number. The function should return a boolean based on if the first argument is between the range of the min and max number. 
    
    ```jsx
    isNumWithinRange(3, 1, 5) //returns true, because 3 is between 1 and 5 
    isNumWithinRange(5, 1, 5) //returns true, because 5 is between 1 and 5 
    isNumWithinRange(11, 5, 10) //returns false, because 11 is not between 5 and 10 
    ```
    
3. Write a function named `countFromOne` that takes in an integer argument, and returns an array of integers, where the elements are the numbers between 1 and the given argument, ordered from least to greatest. 
    
    ```jsx
    countFromOne(5) //returns [1,2,3,4,5]
    countFromOne(0) //returns []
    countFromOne(10) //returns [1,2,3,4,5,6,7,8,9,10]
    ```
    
4. Declare a function named `findShortestWord`, that takes an array of strings as an argument, and returns the shortest string in the array. If there is more than one shortest string, the function should return the **first** shortest string that appears in the array. 
    
    ```jsx
    findShortestWord(["The","quick","brown", "fox", "jumped", "over", "the", "lazy", "dog"]) //returns "The"
    
    findShortestWord(["jazzy", "jumpy", "quaky"]) //returns "jazzy"
    ```
    
5. Write a function named `vowelCount` that takes in a string and returns an object where the keys are letters in the given string that are vowels and the value of each vowel key is a count of how many times the character appears in the string. For this problem, vowels are `a`,`e`,`i`,`o`,`u`.
    
    ```jsx
    vowelCount("aaa") // returns {"a": 3}
    vowelCount("code challenge") // returns {"o": 1, "e":3, "a":1,}
    ```
