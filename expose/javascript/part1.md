1. By line 9, the function returns 20. Since "add" is true, the if block gets executed. I.e, var "result" is created and set to be the sum of num1 & num2.
2. Line 13 also returns 20. Because "result" is a var, it can be access outside of the if block. Since this block is executed, "result" is created and available to access anywhere in the function.
3. By line 9, the function returns 20. Since "add" is true, the if block gets executed. I.e, var "result" is created and set to be the sum of num1 & num2.
4. Line 13 returns a "variable not found" eror because "result" is undefined at this point. A "let" variable only exists in a block scope,
5. Line 9 returns an "assignment to constant variable" error because const "result" cannot be reassigned. 
6. Line 13 will not get executed because of the error in line 9.