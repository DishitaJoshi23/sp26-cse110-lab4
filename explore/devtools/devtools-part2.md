## Question 1: What was the bug?
The bug was that .value always returns a string, not a number. We need the num1 and num2 values to be integer types so that we can sum them up. 

---

## Question 2: How would you fix it?
I edited the code such that we convert num1 and num2 to integer type by type casting. 