```# Build a Simple Calculator

## Learning Goals

- Use Ruby math operations to build a calculator
- Define instance method
- Use the Ruby `Math` class to call a method provided by Ruby

## Introduction

Calculators can be very useful devices in day-to-day activities. You've likely
used a calculator to add up bills for this month or calculate the tip at a
restaurant. We're going to take our arithmetic knowledge and put it to the test
by writing functions that will do basic math calculations for us, just like we
can see in IRB.

## Use Ruby Math Operations to Build a Calculator

Fork and clone this repo and open `lib/math.rb`. You'll find a bunch of empty
methods that take numbers as arguments. Build the appropriate behavior for each
of the following methods:

- `addition` - Build the method `addition` that adds `num1` to `num2` and returns the result of this calculation
- `subtraction` - Build the method `subtraction` that subtracts `num1` from
  `num2` and returns the result of this calculation
- `multiplication` - Build the method `multiplication` that multiplies `num1`
  from `num2` and returns the result of this calculation
- `division` - Build the method `division` that divides `num1` into `num2` and returns the result of this calculation
- `modulo` - Build the method `modulo` that divides `num1` into `num2` and gives
  us the _remainder_ of this calculation
- `square_root` -- Build the method `square_root` that finds the square root of
  `num` and returns the result

## Use Methods Provided by Ruby

If a few places we've asked specific instances of data to run _methods_
(`.class` or `.to_s`) have come up in the Programming as Conversation series.
We call those _instance methods_. We're asking _a_ given number, say `314` for
its `.class` (`314.class #=> Integer`).

But sometimes Ruby provides standard helpful functions as _class_ methods. A
class method is like a utility method that's contained in a special namespace.
Let's say you needed to do some trigonometry. Ruby has you covered! You can use
`Math.sin()` to find the sine of an angle. Ruby also provides `Math.sqrt` as a
_class method_ so that you can use Ruby's understanding of squares to help out.

The `square_root` method this lab requires you to write should use `Math.sqrt`.

This is scratching the surface of "Object-Oriented Programming." Helpful
functions are available to _instances_ and _classes_ to help do work. There's a
_lot_ to say about this, but for the time being, we can use some _class
methods_ to help do some advanced mathematics.

## Conclusion

Submit the lesson once all tests are passing.

Ruby gives us many operators that can be used to perform calculations. This is
the tip of the iceberg--we can do so much more than simple arithmetic, however,
these operations are the most common that a developer will encounter. Grasping
the basics will get you very far!
