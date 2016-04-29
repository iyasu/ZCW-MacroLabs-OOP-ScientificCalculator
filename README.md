# Project 1: Calculator


## Description

In this project you will build a small app to function as a calculator. This app  will be built in Java, and will use the topics and techniques discussed during the week.

You should work on this project in your own repository. Click the `fork` button in the top right corner to create a copy of this repository on your github account. You can go through the [GitHub forking tutorial](https://help.github.com/articles/fork-a-repo/) if you need additional practice with this.


## Requirements

### Testing

All features must be tested. Tests must include normal behavior, and any possible error situations. Tests must have descriptive names and should be independent of each other (running or not running one test should not influence the behavior of any other test).

### Documentation

You must produce UML diagrams for your program. All classes (excluding test classes) must be included in the UML class diagrams.

### Core Features

All calculators should have the following features:

- A state, representing the value currently displayed on the calculator (default 0) *
- Get the current number on the display *
- Clear the display *
- Change the number on the display *
- Add, subtract, multiply, and divide the value on the display by a given number
- Calculate the square (x<sup>2</sup>) and square root (√x) of the number on the display *
- Calculate variable exponentiation (x<sup>y</sup>)
- Calculate the inverse of the number on the display (1/x) *
- Invert the sign of the number on the display (switch between positive and negative)
- Update the display to `Err` if an error occurs (eg: Division by zero) *
- Errors must be cleared before any other operation can take place *

Each operation should automatically update the display


### Scientific Features

- Switch display mode (binary, octal, decimal, hexadecimal)
  - `switchDisplayMode()` should rotate through the options
  - `switchDisplayMode(String mode)` should set the display to the mode given
- Memory - Store up to one numeric value in memory for recall later (default to 0) *
  - (`M+` key) Add the currently displayed value to the value in memory (store in memory and update display) *
  - (`MC` key) Reset memory *
  - (`MRC` key) Recall the current value from memory to the display *
- Trig functions
  - Sine - Calculate the sine of the displayed value and display it
  - Cosine - Calculate the cosine of the displayed value and display it
  - Tangent - Calculate the tangent of the displayed value and display it
  - Inverse Sine
  - Inverse Cosine
  - Inverse Tangent
- Switch trig units mode (Degrees, Radians)
  - `switchUnitsMode()` should rotate through the options
  - `switchUnitsMode(String mode)` should set the trig units to the type given
- Logarithmic functions
  - Log
  - 10<sup>x</sup> (inverse logarithm)
  - Ln (natural logarithm)
  - e<sup>x</sup> (inverse natural logarithm)
- Factorial function  


### Custom Features

In addition to the Core and Scientific features, you are required to create at least two of your own features for the calculator. They can be any two features that are not already covered and that you can implement as you see fit. These features must be properly tested.

### Hints

The following functions should take the displayed value (x) and updated it according to the given formula: (this may not be an exhaustive list)

- `square()`: x<sup>2</sup>
- `squareRoot()`: √x
- `inverse()`: <sup>1</sup>/<sub>x</sub>
- `switchSign()`: -x
- `sine()`: sin(x)
- `cosine()`: cos(x)
- `tangent()`: tan(x)
- `inverseSine()`: sin<sup>-1</sup>(x)
- `inverseCosine()`: sin<sup>-1</sup>(x)
- `inverseTangent()`: tan<sup>-1</sup>(x)
- `factorial()`: x! (x factorial)

## Submission

Completed projects should be submitted by submitting a pull request against the [original repository](https://github.com/Zipcoder/project-1-calculator). All work should be done in your own repository.
