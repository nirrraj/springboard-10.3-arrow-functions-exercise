Arrow Functions Exercise
In this exercise, you’ll refactor some ES5 code into ES2015.

-------
ES5 Map Callback

function double(arr) {
  return arr.map(function(val) {
    return val * 2;
  });
}

ES2015 Arrow Functions Shorthand
Refactor the above code to use two arrow functions. Turn it into a one-liner.

const double = arr => arr.map(val => val * 2)

-------
Refactor the following function to use arrow functions:

function squareAndFindEvens(numbers){
  var squares = numbers.map(function(num){
    return num ** 2;
  });
  var evens = squares.filter(function(square){
    return square % 2 === 0;
    });
   return evens;
}

Replace ALL functions with arrow functions:

const squareAndFindEvens = numbers => numbers.map(val => val ** 2).filter(squaredVal => squaredVal%2 === 0);


