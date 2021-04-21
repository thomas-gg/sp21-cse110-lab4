### Part 1a

var: 
1. values added: 20
2. values result: 20

let:
1. values added: 20
2. error --> result is not defined. This is because result has block scope inside the if statement and we attempt to call result after the if statement.

const:
1.  previous error means this line doesn't print --> Assignment to constant variable. This is because result is a const which can be assigned only once after being declared.
2. previous error means this line doesn't print --> Assignment to constant variable. This is because result is a const which can be assigned only once after being declared.

### Part 1b
1. 3 will be printed because there are 3 elements in the array.
2. 150 will be printed because it was the last time that the discountedPrice was set in the loop. Each time in the loop discountedPrice is being reset and the last time it is run, it is being set to 300 * 0.5 which is 150.
3. 150 will be printed because it was the last time that the finalPrice was assigned in the loop. Each time in the loop finalPrice is being reset to be the rounded value of the discount. In this case finalPrice was being set to the rounded version of 150.
4. This function returns [ 50, 100, 150] because we in this case the function works to multiply each element in the array by 0.5.
5. This will cause an error because i is not defined within the function scope but rather within the for loop scope (and this console.log is executed after the for loop ended).
6. This will cause an error because discountedPrice is not defined within the function scope but rather within the for loop scope (and this console.log is executed after the for loop ended).
7. This will print 150 because finalPrice is defined in the same scope and is changed to 150 in the last iteration of the for loop.
8. This function returns [ 50, 100, 150] because we in this case the function works to multiply each element in the array by 0.5.
9. This will cause an error because i is not defined within the scope of the function but rather it is defined within the for loop.
10. 3 is printed because length is set at the top to be the length of the array prices which in this case was an array with length 3.
11. This function returns [ 50, 100, 150] because we in this case the function works to multiply each element in the array by 0.5.
12. 
    * student.name
    * student["Grad Year"]
    * student.greeting()
    * student["Favorite Teacher"].name
    * student.courseLoad[0]
13. 
    * '32'
    * 1
    * 3
    * '3null'
    * 4
    * 0
    * '3undefined'
    * NaN
14. 
    * true
    * false
    * true
    * false
    * false
    * true
15. The == operator compares only value, whereas the === compares value and type
17. When modifyArray is called, array is set to [1,2,3] and callback is set to the function doSomething which takes in a parameter and returns 2 times that parameter. When calling modifyArray we create a new array, newArr, which has the values of the returned values of the callback pushed to it, in each iteration of the for loop a value of the array is passed to the callback function, which is doSomething. doSomething then returns 2 times the value it was passed in meaning that the value passed to the push of the newArr is 2 * the original value.
19. * 1
    * 4
    * 3
    * 2