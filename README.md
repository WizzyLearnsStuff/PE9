# Special Pythagorean Triplet

https://projecteuler.net/problem=9

## Solution Methodology

Approach 1: Exhaustive Search, everyone is happy

Cons: I was bored needed a challenge


Approach 2: Mathematics and a calculator
Pros: Learn new stuff

Prerequisite: https://en.wikipedia.org/wiki/Pythagorean_triple#Generating_a_triple
With this formulae our goal is to reduce the number of variables
in turn, hopefully, making our search space smaller.

Next, substitute the formulae in the constraint a + b + c = 1000
Solve the resulting quadratic equation

now the discriminant has to be a perfect sqaure, using this info
we pick the smallest value possible for the parameter of the equation,

since the negative solution is not allowed by the formulae we can safely ignore it

using the obtained solution to the constraint under the formula,
evaluate the formula for a, b, c

Optionally, verify all constraints till now

Finally, compute the answer a * b * c
