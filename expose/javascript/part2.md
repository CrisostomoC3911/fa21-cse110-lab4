1. It prints out 3. Since 'i' was declared as a var, it has full function scope, so it can be called outside of the for loop.
2. It prints out 150. Since 'discountedPrice' was declared as a var, it has full function scope, so it can be called outside of the for loop.
3. It prints out 150. 'finalPrice' was declared as a var, and is still within the same scope as when line 14 is called.
4. This function returns [50, 100, 150]. It calulates 50, 100, and 150 from [100, 200, 300] and the discount of 50% off and pushes it into the final result. The for loop halves each price of the prices array one by one, and pushes them into the discounted array.
5. Line 12 attempts to call it outisde the for loop. An error occurs because it calls 'i' out of scope. Since it was declared as a let variable, it exists only within the for loop.
6. Line 13 attempts to call it outisde the for loop. An error occurs because it calls 'discountedPrice' out of scope. Since it was declared as a let variable, it exists only within the for loop.
7. At line 14, 150 is printed. This is because the variable finalPrice is in scope with where the console.log is called. Therefore, it is able to be printed.
8. This function returns [50, 100, 150]. It calulates 50, 100, and 150 from [100, 200, 300] and the discount of 50% off and pushes it into the final result. The for loop halves each price of the prices array one by one, and pushes them into the discounted array.
9. Line 11 attempts to call it outisde the for loop. An error occurs because it calls 'i' out of scope. Since it was declared as a let variable, it exists only within the for loop.
10. It prints out 3. 'length' was declared within scope of the whole function as a const, so there are no errrors.
11. This function returns [50, 100, 150]. It calulates 50, 100, and 150 from [100, 200, 300] and the discount of 50% off and pushes it into the final result. The for loop halves each price of the prices array one by one, and pushes them into the discounted array.
12. notation:
    - student["name"]
    - student["Grad Year"]
    - student.greeting()
    - student["Favorite Teacher"]["name"]
    - student["courseLoad"][0]
13. Arithmetic
    - '32' since 2 is converted into a string and appended to '3'
    - 1 since '3' is converted into a number and subtracted by 2.
    - 3 since null is converted into 0 and adds to 3.
    - '3null' since null is converted into a string and appended to '3'
    - 4 since true is converted into 1 and adds to 3.
    - 0 since false is converted into 0 and null is converted into and they are added together.
    - '3undefined' since undefined is converted into a string and appended to '3'
    - NaN since undefined is converted into NaN. None of the types can be converted, so it outputs NaN.
14. Comparison
    - TRUE since 2 gets converted into a number and 2 is greater than 1
    - FALSE since neither are converted into a number and '2' is greater than the first character of '12'
    - TRUE since it converts '2' into a number
    - FALSE since it checks whether they're the same type
    - FALSE since it converts true into 1 and 1 != 2
    - TRUE since it converts 2 into a boolean so they're the same
15. == will convert the types of the variables to the same thing while === does not
16. This function returns [2, 4, 6]. This goes through a for loop where in each iteration we push the output of doSomething with array[i] as an input.
17. 1
    4
    3
    2
