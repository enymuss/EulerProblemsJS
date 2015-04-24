# EulerProblemsJS
JS Solutions to Project Euler problems. https://projecteuler.net
#1.
```javascript
var sum = 0
var limit = 1000

for (var i = 0; i<limit; i++){
    if (i % 3 == 0 || i % 5 == 0) {
        sum += i;
    }
}```
#2.
```javascript
var sum = 0;
var firstFib = 1
var secondFib = 2

while (firstFib <= 4000000) {
    var tempSum = firstFib + secondFib
    var firstFib = secondFib
    var secondFib = tempSum
    
    if (firstFib % 2 == 0) {
        sum += firstFib
    }
}```
