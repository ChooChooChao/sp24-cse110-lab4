Part 1-Question 1:
- Line 9 prints 
  - values added:  20

Part 1-Question 2:
- Line 13 prints
  - final result:  20

Part 1-Question 3:
- Line 9 prints
  - values added:  20

Part 1-Question 4:
- There is an error, since `let` is block-scoped it is not seen outside the if-statement.

Part 1-Question 5:
- There is an error. Because result is defined as constant and initialized with the value 0, you cannot change its value.

Part 1-Question 6:
- There is error. If you comment out the original error in line 9, there is the same issue as question 4, which is block-scoped.

Part 2-Question 1:
- The code at line 12 outputs the value: 3.

Part 2-Question 2:
- The code at line 13 outputs the array: [ 50, 100, 150 ].

Part 2-Question 3:
- The code at line 14 outputs the value: 150.

Part 2-Question 4:
- The function returns the value of discounted prices in an array ([ 50, 100, 150 ]), however it is now shown in the terminal/console. The code `console.log()` is 
like JavaScript's equivalent to Java's `System.out.print()`. Meaning the value of disconted is return, but not stored or printed anywhere.

Part 2-Question 5:
- Since `let` is block-scoped, it can only be used withing the block of the for loop. Thus since the `console.log(i)` is outside 
of that block, it is considered undefined.  

Part 2-Question 6:
- Output: [ 50, 100, 150 ]
  - The output is a list, because the array variable `discounted` is defined at the start of the function, meaning it has the scope of the 
  entire function.

Part 2-Question 7:
- Output: 150
  - Again, since the varaible `finalPrice` is defined at the top of the function, it has the scope of the entire function.

Part 2-Question 8:
- Similar to question 4, the function will properly return the list of discounted prices ([ 50, 100, 150 ]), however since there is no use of 
`console.log()` it is not printed to the terminal or stored anywhere. 

Part 2-Question 9:
- Line 11 produces an error.
  - Since `let` is block-scoped, it can only be used withing the block of the for loop. 

Part 2-Question 10:
-  Output: 3
   - when we call the function at the end, we pass a list `prices` that has 3 elements. thus when we define length at the beginning of the function, it 
   is set to 3 and will remain always be 3 since it is a variable of type `const`.

Part 2-Question 11:
- The function will properly return the list of discounted prices ([ 50, 100, 150 ]), however since there is no use of 
`console.log()` it is not printed to the terminal or stored anywhere. 