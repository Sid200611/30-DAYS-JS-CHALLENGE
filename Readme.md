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

# Day 2: 30 Days of JavaScript Challenge with Chai and Code

I'm excited to share that I've completed Day 2 of the "30 Days of JavaScript Challenge" from Chai and Code! 🎉 Today, I worked on various fundamental JavaScript concepts including arithmetic operations, assignment operators, comparison operators, logical operators, and the ternary operator. Here’s a breakdown of the tasks and activities I tackled today:

## Tasks/Activities

### Activity 1: Arithmetic Operations

1. **Add two numbers and log the result to the console.**

    ```javascript
    let a = 5;
    let b = 6;
    let c = a + b;
    console.log(c);  // Output: 11
    ```

2. **Subtract two numbers and log the result to the console.**

    ```javascript
    let d = 5;
    let e = 6;
    let f = d - e;
    console.log(f);  // Output: -1
    ```

3. **Multiply two numbers and log the result to the console.**

    ```javascript
    let g = 5;
    let h = 6;
    let i = g * h;
    console.log(i);  // Output: 30
    ```

4. **Divide two numbers and log the result to the console.**

    ```javascript
    let j = 5;
    let k = 6;
    let l = j / k;
    console.log(l);  // Output: 0.8333333333333334
    ```

5. **Find the remainder when one number is divided by another and log the result to the console.**

    ```javascript
    let m = 5;
    let n = 6;
    let o = m % n;
    console.log(o);  // Output: 5
    ```

### Activity 2: Assignment Operators

6. **Use the `+=` operator to add a number to a variable and log the result to the console.**

    ```javascript
    let p = 5;
    let q = 6;
    p += q;
    console.log(p);  // Output: 11
    ```

7. **Use the `-=` operator to subtract a number from a variable and log the result to the console.**

    ```javascript
    let r = 5;
    let s = 6;
    r -= s;
    console.log(r);  // Output: -1
    ```

### Activity 3: Comparison Operators

8. **Compare two numbers using `>` and `<` and log the result to the console.**

    ```javascript
    let t = 5;
    let u = 6;
    console.log(t > u);  // Output: false
    console.log(t < u);  // Output: true
    ```

9. **Compare two numbers using `>=` and `<=` and log the result to the console.**

    ```javascript
    let v = 5;
    let w = 6;
    console.log(v >= w);  // Output: false
    console.log(v <= w);  // Output: true
    ```

10. **Compare two numbers using `==` and `===` and log the result to the console.**

    ```javascript
    let x = 5;
    let y = 6;
    console.log(x == y);  // Output: false
    console.log(x === y);  // Output: false
    ```

### Activity 4: Logical Operators

11. **Use the `&&` operator to combine two conditions and log the result to the console.**

    ```javascript
    let z = 5;
    let a1 = 6;
    console.log(z == 5 && a1 == 6);  // Output: true
    ```

12. **Use the `||` operator to combine two conditions and log the result to the console.**

    ```javascript
    let b1 = 5;
    let c1 = 34;
    console.log(b1 == 5 || c1 == 6);  // Output: true
    ```

13. **Use the `!` operator to negate a condition and log the result to the console.**

    ```javascript
    let d1 = true;
    console.log(!d1);  // Output: false
    ```


# Day 3: Control Structures

I'm excited to share that I've completed Day 3 of the "30 Days of JavaScript Challenge" from Chai and Code! 🎉 Today, I focused on various fundamental JavaScript concepts related to control structures. Here’s a breakdown of the tasks and activities I tackled today:

## Tasks/Activities

### Activity 1: If-Else Statements

1. **Check if a Number is Positive, Negative, or Zero**:
   - **Answer**: Wrote a program to determine if a given number is positive, negative, or zero, and logged the result to the console.

     ```javascript
     let a = 3;
     if (a > 0) {
         console.log("Positive");
     } else if (a < 0) {
         console.log("Negative");
     } else {
         console.log("Zero");
     }
     ```

2. **Check Voter Eligibility**:
   - **Answer**: Wrote a program to check if a person is eligible to vote (age >= 18) and logged the result to the console.

     ```javascript
     let b = 20;
     if (b >= 18) {
         console.log("Eligible");
     } else {
         console.log("Not Eligible");
     }
     ```

### Activity 2: Nested If-Else Statements

3. **Find the Largest of Three Numbers**:
   - **Answer**: Wrote a program to find the largest of three numbers using nested if-else statements.

     ```javascript
     let c = 5;
     let d = 6;
     let e = 7;
     if (c > d) {
         if (c > e) {
             console.log(c);
         } else {
             console.log(e);
         }
     } else {
         if (d > e) {
             console.log(d);
         } else {
             console.log(e);
         }
     }
     ```

### Activity 3: Switch Case

4. **Determine the Day of the Week**:
   - **Answer**: Used a switch case to determine the day of the week based on a number (1-7) and logged the day name to the console.

     ```javascript
     let f = 5;
     switch (f) {
         case 1:
             console.log("Monday");
             break;
         case 2:
             console.log("Tuesday");
             break;
         case 3:
             console.log("Wednesday");
             break;
         case 4:
             console.log("Thursday");
             break;
         case 5:
             console.log("Friday");
             break;
         case 6:
             console.log("Saturday");
             break;
         case 7:
             console.log("Sunday");
             break;
         default:
             console.log("Invalid day number");
     }
     ```

5. **Assign a Grade Based on a Score**:
   - **Answer**: Used a switch case to assign a grade ('A', 'B', 'C', 'D', 'F') based on a score and logged the grade to the console.

     ```javascript
     let g = 5;
     switch (g) {
         case 1:
             console.log("A");
             break;
         case 2:
             console.log("B");
             break;
         case 3:
             console.log("C");
             break;
         case 4:
             console.log("D");
             break;
         case 5:
             console.log("F");
             break;
         default:
             console.log("Invalid score");
     }
     ```

### Activity 4: Conditional (Ternary) Operator

6. **Check if a Number is Even or Odd**:
   - **Answer**: Used the ternary operator to check if a number is even or odd and logged the result to the console.

     ```javascript
     let h = 5;
     (h % 2 == 0) ? console.log("Even") : console.log("Odd");
     ```

### Activity 5: Combining Conditions

7. **Check if a Year is a Leap Year**:
   - **Answer**: Wrote a program to check if a year is a leap year using multiple conditions (divisible by 4, but not 100 unless also divisible by 400) and logged the result to the console.

     ```javascript
     let i = 2024;
     if ((i % 4 == 0 && i % 100 != 0) || i % 400 == 0) {
         console.log("Leap Year");
     } else {
         console.log("Not Leap Year");
     }
     ```

# Day 4: Loops and Control Structures

I'm excited to share that I've completed Day 4 of the "30 Days of JavaScript Challenge" from Chai and Code! 🎉 Today, I focused on various fundamental JavaScript concepts related to loops and control structures. Here’s a breakdown of the tasks and activities I tackled today:

## Tasks/Activities

### 1. for Loops

1. **Print numbers from 1 to 10:**

   Used a `for` loop to print numbers from 1 to 10.

2. **Print the multiplication table of 5:**

   Used a `for` loop to print the multiplication table of 5.

### 2. while Loops

1. **Calculate the sum of numbers from 1 to 10:**

   Used a `while` loop to calculate the sum of numbers from 1 to 10 and logged the result to the console.

2. **Print numbers from 10 to 1:**

   Used a `while` loop to print numbers from 10 to 1.

### 3. do-while Loops

1. **Print numbers from 1 to 5:**

   Used a `do-while` loop to print numbers from 1 to 5.

2. **Calculate the factorial of a number:**

   Wrote a function to calculate the factorial of a given number using a `do-while` loop.

### 4. Nested Loops

1. **Printing the pattern:**

   Used nested `for` loops to print a pattern of stars (`*`) in increasing order, from one star to five stars.

### 5. Loop Control Statements

1. **Print numbers from 1 to 10, skipping 5:**

   Used a `for` loop to print numbers from 1 to 10, but skipped the number 5 using a `continue` statement.

2. **Print numbers from 1 to 10, stopping at 7:**

   Used a `for` loop to print numbers from 1 to 10, but stopped the loop when it reached the number 7 using a `break` statement.


    