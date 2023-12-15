# Array practice

Identify the time complexity of each of these functions with a 1 sentence
justification for your answer. Assume `arr` is an array of length _n_.

## `arr.push()`

Time complexity: O(?) 1 ?
Space complexity: O(?) 1?
Justification: _Fill this in_

[push on MDN] 


## `arr.pop()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_

[pop on MDN][pop]

## `arr.shift()`

Time complexity: O(?) O(n) because it shifts all the elements
Space complexity: O(?) 1 because it just removes one
Justification: _Fill this in_

[shift on MDN][shift]

## `arr.unshift()`

Time complexity: O(?) O(N)
Space complexity: O(?) SAME 
Justification: _Fill this in_
because a new is created to store the additional element and its happening at the beginning of the array not the end of it .
[unshift on MDN][unshift]

## `arr.splice()`

Time complexity: O(n)
Space complexity: O(n)
Justification: _Fill this in_
creates a new array with the modified elements worst case would O(n + m) 
[splice on MDN][splice]

## `arr.slice()`

Time complexity: O(k)
Space complexity: O(k)
Justification: _Fill this in_
slice creates a copy of the array so O(K) or O(n) for both time and space because it iterates over the indicated values of the array 
[slice on MDN][slice]

## `arr.indexOf()`

Time complexity: O(n)
Space complexity: O(1)
Justification: _Fill this in_
it has to go through the entire array in worst case scenario 
[indexOf on MDN][indexOf]

## `arr.map()`

Time complexity: O(n)
Space complexity: O(n)
Justification: _Fill this in_
it iterates over the original array changing some values so it has the same length as the orignial array with the modified values so time and space complexity both are o or n 
[map on MDN][map]

## `arr.filter()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_
it also iterates over the entire array so it has a time and space complexity of o(k) also know as o n
[filter on MDN][filter]

## `arr.reduce()`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_
it is usually has a time complexity of o of n and a spac e complexityy of o of 1 but this is in basic behaviour becuase it doesnot create a new array and it still iterates over the old one 
[reduce on MDN][reduce]

## `arr.reverse()`

Time complexity: O(n)
Space complexity: O(1)
Justification: _Fill this in_
it has a time complexiyy of o of n and a space complexity of o  of 1 because it modified the arrray in place 
[reverse on MDN][reverse]

## `[...arr]`

Time complexity: O(?)
Space complexity: O(?)
Justification: _Fill this in_
each element is processed individually so time and space complexity of o of n
[spread on MDN][spread]

[push]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
[pop]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
[shift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift
[unshift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift
[splice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
[slice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
[indexOf]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf
[map]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
[filter]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
[reduce]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
[reverse]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse
[spread]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax