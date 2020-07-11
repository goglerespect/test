//задача 1
var test = [1,2,3,4,5];
var twist = test.map(function(num) {
 return num * 2;
});
console.log (twist)
//задача 2
var test = [1,2,3,4,5];
var twist = test.filter(function(num) {
 return num % 2;
});
console.log (twist)
//задача 3
const test = [1, 2, 3, 4, 5];
const twist = (element) => element % 2 === 0;
console.log(test.some(twist))
//задача 4
const test = [1, 2, 3, 4, 5];
const twist = (element) => element % 2 === 0;
console.log(test.every(twist))
//задача 5
const test = [1,2,3,4,5];;
const sum = (total, amount) => total + amount;
console.log(test.reduce(sum));
console.log(test.reduce(sum, 5));
