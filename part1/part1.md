# part 1a
1. values added: 20
2. final result: 20
3. values added: 20
4. returns an error, `let` is only accessible within the if block since it was declared there
5. returns an error, `const` cannot be reassigned in line 7
6. returns an error, `const` cannot be reassigned in line 7

# part 1b
1. since `i` is a `var`, it can be accessed by line 12. 3 will be printed because `i` is incremented in the for loop prior to 3.
2. since `discountedPrice` is `var`, it can be accessed by line 13. `300*(1-0.5)` is performed on `discountedPrice`, giving it the value of `150.0`. because it's calculating based on the passed in `prices` array, since we're printing outside of the loop, it will use the last value, `300`. thus, `150.0` will be printed.
3. since `finalPrice` is `var`, it can be accessed by line 14. `finalPrice` will be `150` because the value is being rounded at line 8 and it is using the final value of the `prices` array, `300`. thus, `150` will be printed.
4. the function will return an array of discounted prices using the parameters `prices` and `discount`, where each value of the returned array will be a rounded calculation from the for loop.
5. returns an error, because `i` is a `let`, it will only be accessible in the for loop it was declared in.
6. returns an error, because `discountedPrice` is a `let`, it will only be accessible in the for loop it was declared in.
7. since `finalPrice` is a `let` and declared in the same function block as line 14, `150` will be printed since the for loop's last iteration assigned `150` as the value of `finalPrice`.
8. the function returns an array with calculated (rounded to the cent) discount prices according to the given parameters. 
9. returns an error, because `i` is a `let`, it will only be accessible in the for loop it was declared in, and line 11 is not within the loop. 
10. 3 will be printed, since `const length` was declared in the same code block and was not reassigned and the value it is initalized with is the legnth of the passed in array.
11. the function returns a `const` array with calculated (not rounded to the cent) discount prices according to the given parameters. 
12. a) `student.name`
    b) `student["Grad Year"]`
    c) `student.greeting`
    d) `student["Favorite Teacher"].name`
    e) `student.courseLoad[0]`
13. a) `'32'`, the `integer` maps into a `string` and will then concatenate the two values 
    b) `1`, the `string` maps into an `integer` and will be subtracted from
    c) `3`, the `null` casts into 0
    d) `3null`, the `null` maps into a `string` and is concatenated with 3
    e) `4`, the `true` maps into integer `1` and is added to 3
    f) `0`, the `false` and `null` maps into integer `0`
    g) `3undefined`, the `undefined` maps into a `string` and is concatenated with 3
    h) `NaN`, the `undefined` cannot be mapped to a number, and `-` needs to be performed on number values unlike `+` as concatenation
14. a) `true`, the `2` maps into an integer
    b) `false`, the `2` is compared to the first character `1` of `12`
    c) `true`, the `2` maps into an integer
    d) `false`, `2` and `'2'` are of different types
    e) `false`, the value `true` maps to integer `1`
    f) `true`, `Boolean(2)` results to be true
15. `==` permits casting on values during value equivalencey comparison, while `===` doesn't permit casting on values and checks type
16. `part1b-question16.js`
17. `[2,4,6]`. The function call at line 13 calls `modifyArray`, which creates a new array and on each element in the passed in array, `doSomethihng` is called on them and returns double the value, and adds it into the created array. After the for loop, the array is returned. It's essentailly multiplying each value by 2 of `[1,2,3]`.
18. `part1b-question18.js`
19. ` javascript
    1 
    4
    3
    2`
