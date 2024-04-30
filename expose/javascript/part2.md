1. It will print out the number 3, because after the loop ends, i is 3,
and since it's declared var, it still exists
2. It will print out 150 because in the final loop, discountedPrice is set to 150
3. It will print 150 because in the final loop, finalPrice is set to discountedPrice and it's declared var
4. It will return [50, 100, 150], as each iteration of the loop pushes a 50% discounted price
to the discounted array and it returns that
5. It will be an error because in this case i is declared with let, and does not exist outside of the for loop context
6. It will be an error because in this case discountedPrice is declared with let, and does not exist outside of the for loop context
7. It will print 150 because in the final loop, finalPrice is set to discountedPrice and it's declared outside of the for loop
8. It will return [50, 100, 150], as each iteration of the loop pushes a 50% discounted price 
to the discounted array and it returns that
9. It will be an error because in this case i is declared with let, and does not exist outside of the for loop context
10. It will print out 3 because prices has length 3 and it was declared in the outer scope
11. It will return [50, 100, 150], as each iteration of the loop pushes a 50% discounted price
to the discounted array and it returns that
12. 
    1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0]
13. 
    1. '32', 2 is type cast to string representation
    2. 1, the minus operator converts all operands into numbers
    3. 3, null is type cast to 0
    4. '3null', null is converted to the string 'null'
    5. 4, true is converted to the integer 1
    6. 0, false is converted to 0, and null is converted to 0
    7. '3undefined', undefined is converted to the string 'undefined'
    8. NaN, the - operator tries to convert operands to numbers. undefined converts to NaN, which when added to 3, is NaN
14. 
    1. true, as '2' converts to the number 2
    2. false, as when comparing strings, javascript uses lexicographical ordering, and '2' is bigger than '12'
    3. true, '2' is converted to 2, and this expression evaluates to true
    4. false, the === operator checks for type equality
    5. false, true is converted to 1, and 1 != 2
    6. true, Boolean(2) converts 2 into true
15. == does not check for type equality while === makes sure the types are the same
16. in js file
17. the function will return the array [2, 4, 6]. this is because we pass in the
doSomething function, which is called on each element of the original array and
doubles the element, pushing it to newArr, which is returned
18. in js file
19. 1 4 3 2, as setTimeout puts the function execution in a future iteration
of the event loop, so 1 and 4 are executed first. 2 prints after 3 because of its longer timeout
 