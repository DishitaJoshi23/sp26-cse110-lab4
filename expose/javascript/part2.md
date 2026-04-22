
## Question 1
Line 12 will print: 3
This is because the line prints the value of the variable `i` which is declared using `var`. Since, `var` is function-scoped, the value of `i` is still accessible even after the loop ends. The loop ends when the value is no longer less than the length of the input prices array. Since, the length of the array is 3 and the value of `i` increments by 1 every time, the loops stops when the value of `i` is 3 and that's the value that gets printed at line 12. 

---

