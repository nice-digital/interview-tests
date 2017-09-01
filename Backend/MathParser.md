# Interview Technical Assignment - Math Parser

As part of the interview process, we require all candidates to undertake a technical test so that we can assess your technical abilities.  We assess a number of things including the design aspect of your solution and your object oriented programming skills. While this is a small problem, we expect you to submit what you believe is “production-quality” code that you would be able to run, maintain and evolve. You don’t need to “gold plate” your solution, but we are looking for something more than a bare-bones algorithm.  You may not use any external libraries to solve this problem, but you may use external libraries or tools for building or testing purposes.  You should provide sufficient evidence that your solution is complete by, as a minimum, indicating that it works correctly against the supplied test data. Please note that you will be assessed on your judgment as well as your execution. 

===================

# Instructions
Implement a custom maths parser to take a string expression and compute its numerical value.

Operators should be applied in order of precedence from left to right. An exception to this is brackets which are used to explicitly denote precedence by grouping parts of an expression that should be evaluated first.

Rules:

a = '+', b = '-', c = '*', d = '/', e = '(', f = ')'

## Test inputs

```
Input: 3a2c4
Result: 20

Input: 32a2d2
Result: 17

Input: 500a10b66c32
Result: 14208

Input: 3ae4c66fb32
Result: 235

Input: 3c4d2aee2a4c41fc4f
Result: 990

```

* Submit your solutions via email as a zip file (please add '.test' to the extension of the file so that it can get past email server filters, for example: 'mathparser.zip.test')
