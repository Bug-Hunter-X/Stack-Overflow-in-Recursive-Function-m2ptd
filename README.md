This repository contains a Hack program that demonstrates a potential stack overflow error in a recursive function. The function `foo` calculates the factorial of a number using recursion. However, if a large negative number is passed as input, the recursion will not terminate, leading to a stack overflow.  The solution demonstrates how to prevent this by adding a base case that stops when the input becomes negative.