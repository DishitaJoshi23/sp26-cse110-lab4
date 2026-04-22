
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
