# Part 1

1. values added: 20

2. final result: 20

3. You should ignore var because it ignores block scopes. In this case even though result was createdin the scope of the if statement, after the if statement, it could still be used by the console.log. This would be very bad especially when using for loops since you'd usually reuse the variable "i", but if you were to use var, it would mess up all your for loops in the same function.

4. values added: 20

5. It would return an error because you declared result with let so it only exists in the if else scope. Since we then tried to print out result outside of the if else, the variable result doesn't exist and therefore we encounter an error.

6. It would return an error because const can only be declared and initialized once. Since result is already set equal to 0, you can't set it again equal to num1 + num2 which results in an error.

7. It returns an error. This is because const has the same scope as let and thus outside of the if else statement, result does not exist for console to log it.
