# Using the Array Find Method

## Learning Goals

* Practice using `find()` to isolate a specific result

## Introduction

We have learned that the `indexOf()` and `find()` methods can be used to locate
an element in an array, and that they return the **first** element for which the
condition is met. (If you instead want a list of _all_ elements that meet a
condition, you would use `Array.prototype.filter()` instead. We'll learn about
`filter()` in the next lesson.)

We've also learned that the `find()` method takes a _callback function_ as
its argument. This is a common pattern for the `Array` methods we'll be
learning about in this section — in fact, `indexOf()` is the only one that
_doesn't_ take a callback function as an argument. `find()` is one of two
`Array` methods that expects the callback function to return either `true` or
`false` (`filter()` is the other one).

In this lab, we'll practice using the `find()` method.

## Practice Using `find()` to Isolate a Specific Resultg
Remember the workflow:

1. Install the dependencies using `npm install`.
2. Run the tests using `npm test`.
3. Read the errors; vocalize what they're asking you to do.
4. Write code; repeat steps 2 and 3 often until a test passes.
5. Repeat as needed for the remaining tests.

After you have all the tests passing, remember to commit and push your changes
up to GitHub, then submit your work to Canvas using CodeGrade.

## Conclusion

`Array.prototype.find()` is a built-in function in JavaScript which is used to
get the value of the first element in the array that satisfies the provided
condition. With this, you can quickly check all the elements of the array and
return the first match.

## Resources

* [MDN: Array.prototype.find()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)

