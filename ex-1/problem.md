## Exercise 1: 

## Part 1

Write a function that accepts an array of numbers as an argument, and returns the sum of those numbers:

Template:
```
function sumArray(arr) {
  // Your code here
}

// Invoking the function
const result = sumArray([1,2,3,4])

console.log(result) // 10
```


## Part 2

Adapt the function from part 1 so that you can pass in an 'operation' to perfom, in addition to adding the numbers. So you could pass in 'add', 'subtract', 'multiply', or 'divide', and the appropirate result will be returned. The numbers are expected to be operated on in the order of their position in the array.

Template:
```
function operateOnArray(arr, operand) {
  // Your code here
}

// Invoke the function
const addResult = operateOnArray([1,2,3,5], 'add')
const subtractResult = operateOnArray([1,2,3,5], 'subtract')
const multiplyResult = operateOnArray([1,2,3,5], 'multiply')
const divideResult = operateOnArray([1,2,3,5], 'divide')

console.log(addResult) // 10
console.log(subtractResult) // -8
console.log(multiplyResult) // 24
console.log(divideResult) // ~0.0416666666
```
