1. var declaration is function scope, so i is printed
2. var declaration is function scope, so discountedPrice is printed
3. var declaration is function scope, so final price is printed
4. the array [50, 100, 150] is returned because each element in [100, 200, 300] is multiplied by 0.5 and stored in discounted before it is returned
5. 'i' was declared in a tighter scope, so the variable is not defined here (error)
6. 'discountedPrice' was declared in a tighter scope, so the variable is not defined here (error)
7. 'finalPrice' was declared in the same scope, so it is correctly printed 
8. the array [50, 100, 150] is returned because each element in [100, 200, 300] is multiplied by 0.5, the same functionality as questions 1-4
9. 'i' was declared in a tighter scope, so the variable is not defeined here (error)
10. 'discountedPrice' was declared in a tighter scope, so the variable is not defined here (error)
11. 'finalPrice' was declared in the same scope, so it is printed as the value assigned at declaration (0 here)
12. the array [50, 100, 150] is printed as the array is not constant, only the reference to it is
13. 
    a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
14. 
    a. '32' because left hand side is a string so 2 is converted to a string for concatenation
    b. 1 because '3' is converted to a number for subtraction
    c. 3 because null is converted to 0 for addition
    d. '3null' because null is converted to a string for concatenation
    e. 4 because true is converted to 1 for addition
    f. 0 because false and null are both converted to 0 for addition
    g. '3undefined' because undefined is converted to a string for concatenation
    h. NaN because "3" is converted to a number and undefined is converted to NaN for subtraction
15. 
    a. true because '2' is converted to a number for comparison
    b. false because '2' comes after '1' 
    c. true because '==' doesn't check for type equality
    d. false because '===' checks for type equality
    e. false because true is converted to 1 for comparison
    f. true because 2 is converted to true (non-zero number)
16. the '==' operator converts opperands to numbers if they are of different types where the '===' requires type equality and will never do any conversions
17. 'How are you?' is printed because '2 == true' evaluates to false because true is converted to 1, then (2) is converted to true so the code in the 'else if' block runs
18. see 'part1-question18.js'
19. [6, 8, 10] is the result, as modifyArray uses its callback function (in this case doSomething) to modify each element of the array. It also supplies the function x\*2 to doSomething. The function doSomething increments by 2 then passes the result to x\*2, which is ultimately retuned to modifyArray
20. see 'part1-question20.js'
21. ```
    1
    4
    3
    2
    ```