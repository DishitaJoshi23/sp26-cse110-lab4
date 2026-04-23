
## Question 1
Line 12 will print: 3
This is because the line prints the value of the variable `i` which is declared using `var`. Since, `var` is function-scoped, the value of `i` is still accessible even after the loop ends. The loop ends when the value is no longer less than the length of the input prices array. Since, the length of the array is 3 and the value of `i` increments by 1 every time, the loops stops when the value of `i` is 3 and that's the value that gets printed at line 12. 

---

## Question 2
Line 13 will print: 150 
This is because the line prints the value of the variable `discountedPrice` which is declared using `var`. Since, `var` is function-scoped, the value of `discountedPrice` is still accessible even after the loop ends. On the last iteration of the loop, `i = 2` so the value of `discountedPrice` is `price[2] *(1-0.5)` ,  which is equal to 300*0.5 = 150. So, 150 will be logged when line 13 is run.

---

## Question 3
Line 14 will print: 150 
This is because the line prints the value of the variable `finalPrice` which is declared using `var`. Since, `var` is function-scoped, the value of `finalPrice` is still accessible even after the loop ends. On the last iteration of the loop, `discountedPrice = 150` so the value of `finalPrice` becomes `(150*100)/100` ,  which is equal to 150. So, 150 will be logged when line 14 is run.

---

## Question 4
The function returns the array: [50, 100, 150]
This is because each price in the input array: [100, 200, 300] gets multiplied by (1 - 0.5) which is 1- discount, and gets rounded to 2 decimal places, and pushed into the discounted array, which is then returned.

---
## Question 5
Line 12 will throw an error. This is because it is trying to access `i` which is not in scope. Since, `i` is declared using `let`, it is block-scoped. So, `i` is only accessible inside the for loop and basically doesn't exist outside the scope of the for loop. 

---

## Question 6
Line 13 will throw an error. This is because it is trying to access `discountedPrice` which is not in scope. Since, `discountedPrice` is declared using `let`, it is block-scoped. So, `discountedPrice` is only accessible inside the for loop and basically doesn't exist outside the scope of the for loop. So, an error will be thrown at line 13 where it tries to access `discountedPrice`, which is not in scope.  

---

## Question 7
Line 14 will throw an error. This is because it is trying to access `finalPrice` which is not in scope. Since, `finalPrice` is declared using `let`, it is block-scoped. So, `finalPrice` is only accessible inside the for loop and basically doesn't exist outside the scope of the for loop. So, an error will be thrown at line 14 where it tries to access `finalPrice`, which is not in scope.  

---

## Question 8
The function returns [50, 100, 150]. This is because for each price, calculates the value for discounted price within the for loop and push the value into the array that is to be returned. This array is `discounted`, which is declared using `let` that makes its scope the entire function. There won't be any errors. 

---

## Question 9 
Line 11 will throw an error. This is because it is trying to access `i` which is not in scope. Since, `i` is declared using `let`, it is block-scoped. So, `i` is only accessible inside the for loop and basically doesn't exist outside the scope of the for loop. So, an error will be thrown at line 11 where it tries to access `i`, which is not in scope because it's outside the for loop. 

---

## Question 10
Line 12 will print: 3
This is because line 12 prints the value of the variable `length`, which is declared using `const`. This means that `length` has an unchangeable value and it's scope is the entire function. So, it will print `3` which is the length of the input array. This value is set to the variable `length` at the beginning of the function, and is never changed after that. 

---

## Question 11
The function returns [50, 100, 150]. This is because for each price, calculates the value for discounted price within the for loop and assigns it to discountedPrice variable. The value is then pushed into the `discounted` array that is to be returned. This array `discounted`, which is declared using `const` can be accessed and modified (just can't be reassigned) throughout this function. There won't be any errors.

---

## Question 12

A. student.name

B. student['Grad Year']

C. student.greeting()

D. student['Favorite Teacher'].name

E. student.courseLoad[0]

---

## Question 13

A.`'3' + 2`
Output: 32
This is because 3 is considered as a string and '+' with strings leads to string concatenation. So, even thoguh 2 is an integer type, it gets concatenated to '3', which is a string. 

B.`'3' - 2`
Output: 1
This is because even though '3' is a string, '-' forces the string to convert to an integer. So, '3' gets converted into an integer and 2 gets substracted from 3. So, the output is: 3-2=1

C. `3 + null`
Output: 3
Null gets converted to 0 for the mathematical operation to go through. So, output: 3+0 = 3

D.  `'3' + null`
Output: 3null
This is because since 3 is a string, '+' behaves as a concatenator. So, null is converted to a string and gets concatenated to 3.

E. `true + 3`
Output: 4
This is because true gets converted to 1. So, output: 1+3 = 4

F. `false + null`
Output: 0 
Both false and null get converted to 0. So, output: 0+0 = 0

G. `'3' + undefined`
Output: 3undefined
This is because undefined becomes a string and gets concatenated to 3. 

H. `'3' - undefined`
Output: NaN
Because of '-', undefined gets converted to NaN (for Js to do the math). And, 3 is also converted to an integer. So, 3-NaN = NaN.

---

## Question 14

A. `'2' > 1`
Output: True
This is because 2 gets converted to an integer and 2>1. 

B. `'2' < '12'`
Output: False
Here, the output will be false as a result of string comparison and it compares 2 with 1, and 2>1 in terms of strings.

C. `2 == '2'`
Output: True
'2' gets converted to an integer and since, 2==2, the output will be true. 

D. `2 === '2'`
Output: False
This is because '===' checks the value and the type. Since, '2' ≠ 2 (string ≠ integer), output is false. 

E. `true == 2`
Output: False
This is because true gets converted to 1. Since, 1 ≠ 2, output is false. 

F. `true === Boolean(2)`
Output: True
This is because Boolean(2) is also true. So, true = true, output is true. 

---

## Question 15
The main difference between `==` and `===` is that:
- `==` compares the values after type conversion
- `===` compares the values before type conversion

---



