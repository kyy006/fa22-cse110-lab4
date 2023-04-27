1. printed:"3" ,it means i=3,because i is var keyword,This means that regardless of the block it is defined in, it can be accessed anywhere inside the function it is defined in. line 12 is inside the function.
2. printed:"150" , it means discountedPrice=150,because discountedPrice is var keyword,This means that regardless of the block it is defined in, it can be accessed anywhere inside the function it is defined in. line 13 is inside the function.
3. printed:"150" ,it means finalPrice=150,because it is var keyword,This means that regardless of the block it is defined in, it can be accessed anywhere inside the function it is defined in. line 14 is inside the function.
4. The function should return discounted by giving the prices, on line 19, it will return "[ 50, 100, 150 ]". because the for loop will loop over all values inside the prices and do math calculation, and push it to discounted. after the for loop, we have return discounted.
5. ReferenceError: i is not defined, because line 12 printing "i", but i is let keyword, This means that it can only be accessed within the block it is defined in. line 12 is outside of the block of for loop.
6. ReferenceError: discountedPrice is not defined, because line 13 printing "discountedPrice", but discountedPrice is let keyword, This means that it can only be accessed within the block it is defined in. line 13 is outside of the block.
7. printed:"150", because the "finalPrice" is defined in the function as let keyword, so it can be accessed within the function/block, line 14 is still inside the block.
8. The function should return discounted by giving the prices, on line 19, it will return "[ 50, 100, 150 ]". because the for loop will loop over all values inside the prices and do math calculation, and push it to discounted. after the for loop, we have return discounted. It does not have change from question 4 because "discounted" as let keyword but it is defined inside the function, which it can be accessed within the function , and return the value.
9. ReferenceError: i is not defined ,because line 11 printing "i", but i is let keyword, This means that it can only be accessed within the block it is defined in. line 12 is outside of the block of for loop.
10. printed:"3" , becuase length as const keyword,and it prevents from being reassigned, and it is defined inside the function, so it can be accessed inside the function, and there is no code line which wants to change "length".
11. The function should return discounted by giving the prices, on line 17, it will return "[ 50, 100, 150 ]". because the for loop will loop over all values inside the prices and do math calculation, and push it to discounted. after the for loop, we have return discounted. It does not have change from question 4 because the 'const' keyword in JavaScript is used to prevent reassignment of the variable. When you declare an array with 'const', it means that you cannot reassign the array itself to a new value, but you can still modify the contents of the array.
12. 
A)student.name;
B)student['Grad Year'];
C)student.greeting();
D)student['Favorite Teacher'].name;
E)student.courseLoad[0];
13. 
A)Output: '32', explain: The '+' operator, when used with a string and a number, concatenates the two operands. In this case, '3' is a string and 2 is a number, so the result is the string '32'.
B)Output: 1, explain :The '-' operator implicitly converts both operands to numbers if they are not already numbers. In this case, '3' is a string, so it is converted to the number 3, and the calculation becomes 3 - 2, which is 1.
C)Output: 3 , explain :When the '+' operator is used with a number and null, null is treated as 0. Therefore, the calculation becomes 3 + 0, which is 3.
D)Output: '3null', The '+' operator, when used with a string and null, converts null to a string ('null') and concatenates the operands. In this case, the result is the string '3null'.
E)Output: 4 ,explain: The '+' operator converts the boolean true to the number 1. The calculation becomes 1 + 3, which is 4.
F)Output: 0, explain: The '+' operator converts the boolean false to the number 0 and null to the number 0. The calculation becomes 0 + 0, which is 0.
G)Output: '3undefined' explain: same as part d,  The '+' operator, when used with a string and undefined, converts undefined to a string ('undefined') and concatenates the operands. In this case, the result is the string '3undefined'.
H)Output: NaN, explain :The '-' operator converts both operands to numbers. '3' is converted to the number 3, but undefined cannot be converted to a number, so it becomes NaN (Not a Number). Any arithmetic operation involving NaN results in NaN.
14.  
A)Output: true, explain:Explanation: The '>' operator converts both operands to numbers. In this case, '2' is converted to the number 2, and the comparison becomes 2 > 1, which is true.
B)Output: false, explain: When comparing strings, the '<' operator compares them lexicographically (i.e., like a dictionary). In this case, '2' comes after '12', so the comparison is false.
C)Output: true, explain:The '==' operator compares the values of the operands after converting them to a common type. In this case, the number 2 and the string '2' are considered equal because they have the same value when '2' is converted to a number.
D)Output: false, explain:The '===' operator compares both the value and the type of the operands. In this case, the number 2 and the string '2' have different types, so they are considered not equal.
E)Output: false, explain:The '==' operator converts the boolean true to the number 1. The comparison becomes 1 == 2, which is false.
F)Output: true, explain:The '===' operator compares both the value and the type of the operands. In this case, true is a boolean, and Boolean(2) also evaluates to true (since any non-zero number is considered truth)
15.  '=='compares two values for equality, returning true if they are equal and false if they are not. When comparing operands of different types, the == operator performs type coercion, meaning it converts one or both operands to a common type before making the comparison. '===' is Strict Equality Operator.This operator compares both the value and the type of the operands. It returns true only if both the values and the types are equal, and false otherwise. Unlike the '==' operator, the '===' operator does not perform type coercion, so operands of different types are considered unequal.
16.  
output: 21
        45
        5
        2
17.  the result will be a new array '[2, 4, 6]',The 'modifyArray' function is called with an array '[1, 2, 3]' and a callback function 'doSomething'.Inside 'modifyArray', a new empty array 'newArr' is created.The for loop iterates through numbers of the input array '[1, 2, 3]'. For each element in the input array, it calls the callback function (which is doSomething) with the current element as the argument.The 'doSomething' function takes a number as an input and returns the result of the number multiplied by 2. So, for each element in the input array, 'doSomething' returns the doubled value.The modified values are pushed into the 'newArr' array as the loop iterates.After the loop finishes, 'newArr' contains the doubled values of the input array: '[2, 4, 6]'.Finally, newArr is returned.
19. output: 1
            4
            3
            2
because 'console.log(2)' statement to be executed after 1000 milliseconds (1 second), so it is last one.