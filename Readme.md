# Day 1: Variables and Data Types

This repository contains solutions for the tasks and activities related to variable declarations, constant declarations, data types, and variable reassignment in JavaScript.

## Tasks/Activities

### Activity 1: Variable Declaration

1. Declare a variable using var, assign it a number, and log the value to the console.
    javascript
    var a = 5;
    console.log(a);
    

2. Declare a variable using let, assign it a string, and log the value to the console.
    javascript
    let str = "Hello";
    console.log(str);
    

### Activity 2: Constant Declaration

3. Declare a variable using const, assign it a boolean value, and log the value to the console.
    javascript
    const b = true;
    console.log(b);
    

### Activity 3: Data Types

4. Create variables of different data types (number, string, boolean, object, array) and log each variable's type using the typeof operator.
    javascript
    let c = 4;
    let d = "hello";
    let e = true;
    let f = {1: 2};
    let g = ["siddhant"];
    console.log(typeof(c));  // number
    console.log(typeof(d));  // string
    console.log(typeof(e));  // boolean
    console.log(typeof(f));  // object
    console.log(typeof(g));  // object
    

### Activity 4: Reassigning Variables

5. Declare a variable using let, assign it an initial value, reassign a new value, and log both values to the console.
    javascript
    let n1 = 5;
    console.log(n1);
    n1 = 6;
    console.log(n1);
    

### Activity 5: Understanding const

6. Try reassigning a variable declared with const and observe the error.
    javascript
    const n2 = 75;
    console.log(n2);
    n2 = 74;  // This will cause an error
    console.log(n2);  // Uncaught TypeError: Assignment to constant variable.
