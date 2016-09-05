# MIPS Assembly: Difference Of Squares

Find the difference between the sum of the squares and the square of the sums of the first N natural numbers.

The square of the sum of the first ten natural numbers is,

    (1 + 2 + ... + 10)**2 = 55**2 = 3025

The sum of the squares of the first ten natural numbers is,

    1**2 + 2**2 + ... + 10**2 = 385

Hence the difference between the square of the sum of the first
ten natural numbers and the sum of the squares is 2640:

    3025 - 385 = 2640

For these problems, we use the popular MIPS simulator [MARS](http://courses.missouristate.edu/KenVollmar/mars/). Download the MARS jar archive from the MARS website and place it somewhere easily accessible. Also install the Java SDK if you do not have it already.

To run the tests, assemble and run the test runner file for a given exercise either via the MARS simulator GUI, or on the command line. To run on the command line,
specify first the runner file and then your implementation, like so:

    java -jar /path/to/mars.jar nc runner.mips impl.mips

To run in the GUI, `include` your implementation at the bottom of "runner.mips"
by uncommenting the final line.

The test runner will either complete with a “success” message or terminate on a failing test with a message specifying the input for which that test failed.

## Source

Problem 6 at Project Euler [http://projecteuler.net/problem=6](http://projecteuler.net/problem=6)

This exercise is from the [MIPS Assembly][mips] track on [Exercism][exercism]

[exercism]: http://exercism.io
[mips]: http://exercism.io/languages/mips



