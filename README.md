### JavaScript
:+1: Click this link to view <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from" title="Click here to view JavaScript Array">*JavaScript Array* </a><br>
:+1: Click this link to view <a href="https://javascript.info/array" title="Click here to view JavaScript Arrays">*JavaScript Arrays* </a><br>
:+1: Click this link to view <a href="https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/" title="Click here to view Difference Between var, let, and const in JavaScript">*Difference Between var, let, and const in JavaScript* </a><br>
:+1: Click this link to view <a href="https://www.geeksforgeeks.org/javascript-object-freeze-method/" title="Click here to view JavaScript Object freeze() Method">*JavaScript Object freeze()* </a><br>
:+1: Click this link to view <a href="https://www.w3schools.com/js/js_arrow_function.asp" title="Click here to view JavaScript Arrow Function">*JavaScript Arrow Function* </a><br>
:+1: Click this link to view <a href="https://www.smashingmagazine.com/2016/07/how-to-use-arguments-and-parameters-in-ecmascript-6/" title="Click here to view arguments in JavaScript">*arguments in JavaScript* </a><br>
### :dart: Filter vs Map vs Reduce vs Foreach
Map, Filter, and Reduce are Array methods which help to create new arrays in various ways. They are all 'higher order' functions because they take user-defined functions as parameters.

<b>Map:</b> returns an array of pieces of information from the original array. In the callback function, return the data you wish to be part of the new array.

<b>Filter:</b> returns a subset of the original array based on custom criteria. In your callback function, return a boolean value to determine whether or not each item will be included in the new array.

<b>Reduce:</b> can be used to return almost anything. It is often used to return a single number, like an sum, but it can also be used to combine the logic of Map and Filter to return an array of values matching certain criteria. This can remove unnecessary iterations.

The callback for Reduce has two parameters: the accumulator and the current value. Make sure you always return the accumulator after modifying it! In addition to the callback, Reduce receives a second parameter that will define the initial value of the accumulator.

:+1: Click this link to view <a href="https://code.tutsplus.com/how-to-use-map-filter-reduce-in-javascript--cms-26209t" title="Click here to view Array Methods Explained">*Array Methods Explained* </a><br>
### :dart: What is the meaning of "...args" (three dots) in a function definition?
... is called the spread operator.<br>
With respect to (...args) =>, ...args is a rest parameter.<br>
:+1: Click this link to view <a href="https://www.geeksforgeeks.org/what-is-the-rest-parameter-and-spread-operator-in-javascript/" title="Click here to view Difference between Spread and Rest Operator in JavaScript">*Difference between Spread and Rest Operator* </a><br>
```
function max(...value) {
  // ...
}
max(1,2,3);
```
```
console.log(sum(1, 2, 3, 4));  // expected output: 10

function sum(...allItems) { 
  let total = 0;
  for (const item of allItems) {
     total += item;
   }
   return total;
}
```
