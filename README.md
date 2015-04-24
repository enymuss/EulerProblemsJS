# EulerProblemsJS
JS Solutions to Project Euler problems. https://projecteuler.net
#1.
var sum = 0
var limit = 1000

for (var i = 0; i<limit; i++){
    if (i % 3 == 0 || i % 5 == 0) {
        sum += i;
    }
}
#2.
