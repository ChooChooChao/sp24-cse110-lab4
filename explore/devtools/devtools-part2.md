1. What was the bug?
- The bug is that the sum is concatenating the values num1 and num2. This is because when it is taken in, it is a string, but is 
never converted into a number. 

2. How would you fix it? Include a screenshot of your fix. Name it fix.png (or whatever image extension you would like to use) and add it to your expand/screenshots director
- I would fix this issue by converting num1 and num2 into numbers using type conversion: `Number()` in the calculateSum function.