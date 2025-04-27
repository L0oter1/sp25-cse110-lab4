# Part 2

1. Console would log the value of i which is 2 since i is used in the for loop which has it loop through the array of prices which has a length of 3. So i would go through 0, 1, 2. Since i is declared by var, it exists in the function scope so it would return i no problem.

2. It would return the last discountedPrice variable. This is because discountedPrice is declared with var so it exists within the entire function. Since the last assignment of discountedPrice is in the for loop, then the last value will be logged.

3. finalPrice will be printed because similar to above, finalPrice is declared with var so itll still exist inside the function.

4. This function will return discounted which will be an array that contains all the discounted prices of all the products. So in this case since the discount is 0.5, it will return [50, 100, 150] since those are the discounted prices of the original prices with a 50% discount.

5. It will return an error because i is not defined in the scope. Since we declare i by using let, that means i only exists within the for loop so when we call it outside the for loop there will be an error.

6. Throws error because discountedPrice is not defined in the scope outside of the for loop and our console.log is outside that for loop.

7. the function will properly return the last finalPrice which is 150. This is because finalPrice is declared with let inside the entire function. So it's scope exists in the entire function.

8. It will properly return discounted because discounted is declared with let inside the function scope so the return keyword can return discounted.

9. There will be an error because i only exists in the scope of the for loop so outside the for loop, we can not return i.

10. Length will be properly returned because length is declared as a const which exists in the scope of the entire function so console.log will be able to return it. And also we are not changing the value of length anywhere in our code.

11. Returns discounted because discounted is properly used because we use discounted.push and we don't directly change discounted. Also discounted is a const so it exists without the entire function since it was declared inside the function.

12. 
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher].name
E. student.courseLoad[0]

13.
A. '32', node converted the integer 2 into it's string representation of '2' and concatenated the two strings
B. 1, node converted the string 3 into it's integer representation and subtracted them to get 1
C. 3, node refers to null as 0 so 3 + 0 = 3
D. '3null', turned null into the string 'null' and concatenated 3 and null together
E. 4, true is also represented as 1 so it became 1 + 3 = 4
F. 0, both false and null map to 0 so 0 + 0 = 0
G. 3undefined, node turned undefined into a string and concatenated them together
H. NaN, converted the '3' into undefined and overall just became NaN

14.
A. true, converted '2' into integer 2 and 2 is greater than 1
B. false, node compares two strings from left to right and 2 is greater than 1 so it returns false
C. true, converted '2' into integer and 2 == 2 is true
D. false, 2 is not literally the same as the string 2 so it's false
E. false, true is converted to 1 and 1 does not equal 2
F. true, all numbers except 0 are true in Node so true is true

15. == allows conversions of different things to try to make them equal while === does not do type conversions and requires both sides to be the same type or else it's false. 










