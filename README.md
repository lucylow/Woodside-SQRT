# Woodside SQRT


## Fun Square Root Problem Game


## How it works 
* works with any natural number
* write out EACH number from 1 to chosen number 
* q: is it possible t write each of these numbers from 1 to n in an oder where 2 consecutive numbers result in a perfect square?


## Examples
* Ex1: choose number 1 --> 1 squared is 1
* Ex2: choose number 2 --> 1 + 2 , 2 + 1 both == 3, not perfect square 
* Ex3: choose number 3 --> 123, 132, 312 are only unique order solutions where each combination exists in one of these sets - not perfect square


## Pattern for number n
* take each number from collection and find numbers that can be added to it to create perfect square 
* find path from one endpoint to other hitting each number only once including every number
* Ex4: choose number 15 --> create a map chain where : 8 1 15 10 6 3 13 12 4 5 11 14 2 7 9, follows pattern so is square root since each number from  to 15 is included once and every 2 consecutive numbers sums to a prime
* ex5: choose number 18 --> map chain can not be made, does not follow pattern, not perfect square


