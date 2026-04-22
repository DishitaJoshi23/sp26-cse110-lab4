## Question 1

Line 9 prints: `values added:  20`
 
Since `add` is `true`, the `if` block executes. Then,`result` variable is declared with `var` and assigned the value `num1 + num2` (10 + 10 = 20). Then, the value is printed by `console.log('values added: ', result)` which replaces the  logs `values added:  20`.
 
---

## Question 2
Line 13 will print: `final result: 20`

There won't be an error becuase of how var works. Because `result` is declared with `var`, its scope is set for the entire function. This means that `result` is accessible throughout the function and not just the if block.

---

## Question 3
You should generally avoid using `var` because it is function-scoped and not block-scoped. This means that it can be redeclared, and is hoisted, which leads to unpredictable behavior. It also makes it hard to find bugs, and creates confusion.

---
## Question 4

Line 9 prints: `values added:  20`
 
Since `add` is `true`, the `if` block executes. Then,`result` variable is assigned the value `num1 + num2` (10 + 10 = 20). Then, the value is printed by `console.log('values added: ', result)` which replaces the  logs `values added:  20`.
 
---
## Question 5

There will be an error thrown because the variable `result` is declared with `let`, which is block-scoped. This means that it is only accessible within the if block. Since, line 13 is outside the if-block, it can't access `result`.
 
---
