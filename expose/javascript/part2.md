
## Question 1
Line 12 will print: 3
This is because the line prints the value of the variable `i` which is declared using `var`. Since, `var` is function-scoped, the value of `i` is still accessible even after the loop ends. The loop ends when the value is no longer less than the length of the input prices array. Since, the length of the array is 3 and the value of `i` increments by 1 every time, the loops stops when the value of `i` is 3 and that's the value that gets printed at line 12. 

---

## Question 2
Line 13 will print: 150 
This is because the line prints the value of the variable `discountedPrice` which is declared using `var`. Since, `var` is function-scoped, the value of `discountedPrice` is still accessible even after the loop ends. On the last iteration of the loop, `i = 2` so the value of `discountedPrice` is `price[2] *(1-0.5)` ,  which is equal to 300*0.5 = 150. So, 150 will be logged when line 13 is run.

---



