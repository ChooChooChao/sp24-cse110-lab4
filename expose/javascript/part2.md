Question 12:
- A. `student.name`
- B. `student["Grad Year"]`
- C. `student.greeting()`
- D. `student['Favorite Teacher].name`

Question 13:
- '3' + 2 = '32' 
  - The operand 2 is converted to a string by JavaScript, thus you are concatenating the 2 to the end.

- '3' - 2 = 1
  - JavaScript will automatically attemp to convert operands to a numeric value, making this 3 - 2 = 1

- 3 + null = 3
  - It will output the int value 3, since null is treated like a 0.

- '3' + null = '3null'
  - the value null is treated as a string and concatenated

- true + 3 = 4
  - the numerical value of true is 1, thus it is converted to an int and added to 3.

- false + null = 0
  - Again, both have a numerical value of 0, thus 0 + 0 = 0.

- '3' + undefined = '3undefined'
  - 'undefined' is converted to a string type, and concatenated to the '3'.

- '3' - undefined = NaN (not a number)
  - since JavaScript attempts to convert the values to numbers because of the subtraction sign, undefined has no numerical value. 

Question 14:
- '2' > 1 ==> true
  - Since there are two types, JavaScript converts the string to a numeric value, so it was 2 > 1 which is true.

- '2' < '12' ==> false
  - It is compared lexicographically, so looking at the first characters, '2' has a higher value lexicographically than '1' making this statement false.

- 2 == '2' ==> true
  - The string is converted to a num, making the boolean true as 2 == 2.

- 2 === '2' ==> False
  - this returns false, as the `===` is a strict equality operator that checks without type conversion.

- true == 2 ==> False
  - True has a numerical value of 1, thus 1 != 2.

- true === Boolean(2) ==> true
  - The Boolean function converts the value to a true/false value, thus since 2 is non-zero value it has a boolean value of true. 
  And true === true is the same making its output true. 

Question 15:
- The difference between the `==` and `===` operators is that `===` is a strict operator. This means it does the comparison without type conversions. 
whereas as `==` will use type conversion first to make things a numeric value.

Question 17: 
- modifyArray is called with [1, 2, 3] and doSomething
  - so it creates newArr
  - then it goes through the for-loop, iterating 3 times as it is the length of [1, 2, 3]
  - then it uses the function callback, which is the doSomething function 
  - it multiplies each element in array (which is [1, 2, 3]), then pushes it to the newArr
  - this makes it [2, 4, 6], which is then return by modifyArray

Question 19:
- the code outputs:
1
4
3
2

- it does so in this order due to the `setTimeout()` function which causes a delay.
