1. Line 12 returns 2 because var i = prices.length - 1 = 3 - 1 = 2. Since "i" is a var type, it exists and is accessiblewithin the function.
2. Line 13 returns 150 because 300*(0.5) = 150. Since "discountedPrice" is a var type, it exists and is accessible within the function.
3. Line 14 returns 150 because 150*100/100 = 150. 
4. This function returns [50,100,150]. "discountedprice" as a let variable allows reassignment, so each value in "discounted" is the value of "discountedPrice" after every iteration.
5. Line 12 returns an error because "i" is a let type and only exists within the for loop. At line 12, "i" is an undefined variable, hence the error.
6. Line 13 also returns a "variable not found" error. Same reason as #5.
7. Line 14 returns 150 because 150*100/100 = 150. 
8. This function returns [50,100,150]. Same reason as #4.
9. Line 11 returns an "undefined variable" error similar to #5.
10. Line 12 returns 3 because the input array has length of 3.
11. This function returns [50,100,150].
12. 
    1. student.name, 
    2. student["Grad Year"]
    3. student.greeting()
    4. student["Favorite Teacher"]["name"]
    5. student.courseLoad[0]
13. 
    1. '32'
    2. 1
    3. 3
    4. '3null'
    5. 4
    6. 0
    7. '3undefined'
    8. NaN
14. 
    1.  true
    2.  false
    3.  true
    4.  false
    5.  false
    6.  true
15. "==" performs type coercion, so the type of two variables must match first before comparison. "===" performs literal comparison for both content and types of variables.
16. for (const prop in stats) {
  if (prop[0] == "r" || stats[prop]%2 == 1) {
    console.log(stats[prop])
  }
}
17. The call returns [2,4,6]. We pass in the array [1,2,3] and doSomthing function, which simply doubles the input. We then traverse through the array input, performs doSomething on each array element, and pass it in the new array newArr. 
19. 1,4,2,3
