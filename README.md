# FizzBuzz TDD Kata

## Requirements

Make sure you are using at least Python 3.

### Installing Python 3 with pyenv

Install [pyenv](https://github.com/yyuu/pyenv) and install Python 3.8.0 running the following command:

```
pyenv install 3.8.0
```

Now set local project Python version running this command:
```
pyenv local 3.8.0
```

## Description

This Kata is designed to get you used to Test Driven Development.

There is a set of tests in the `./test/` path that are currently failing.

Your task (if you wish to accept it) is to write an implementation of the `./FizzBuzz/FizzBuzz.py` that makes all the tests pass.

Start at the first failing test and see if you can write an implementation to make it pass. Once that test is passing, move to the next failing test, rinse and repeat.

The coding Dojo link below gives the business logic that has already been provided for you in the unit tests.

Stage 2 requires you to implement some new tests, ensure they fail, do an implementation and ensure the tests pass. Once the tests are passing, you may want to refactor (clean up, optimise) your code.

This is called the Red-Green-Refactor approach to Test Driven Development.

### Stage 1

Here is the `FizzBuzz` kata description, that is a little different than the original one:

```
Write a program that evaluate a number and for multiples of three returns "Fizz" instead of the number and for the multiples of five returns "Buzz".
For numbers which are multiples of both three and five print "FizzBuzz".
```

Source: [CodingDojo](http://codingdojo.org/cgi-bin/index.pl?KataFizzBuzz)

### Stage 2

Once you completed the stage 1, try these new requirements:

```
 * A number is fizz if it is divisible by 3 or if it has a 3 in it
 * A number is buzz if it is divisible by 5 or if it has a 5 in it
```

## How to run the Unit Tests

Go to the project root and run the following command:

```
 python -m unittest test.test_FizzBuzz.TestFizzBuzz
```

or just:

```
python -m unittest discover
```