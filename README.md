# Java Calculator

A simple calculator application built using Java AWT. This project demonstrates the basics of GUI programming in Java and implements a functional calculator with memory operations.

## Features

- **Basic arithmetic operations:** Addition, subtraction, multiplication, division, and percentage
- **Special functions:** Square root, reciprocal (`1/x`)
- **Memory operations:** MC (Memory Clear), MR (Memory Recall), MS (Memory Store), M+ (Memory Add)
- **Special buttons:** Backspace, Clear (`C`), Clear Entry (`CE`)
- **Decimal point support**
- **User-friendly interface**

> **Note:** The `+/-` button is present in the UI, but not implemented in the code.

## Limitations

- The `+/-` button does not function.
- No menu bar included.
- Not designed for scientific calculations.
- Floating-point arithmetic may result in imprecise results due to hardware representation.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your system.

### Compilation

Save the source file as `MyCalculator.java`.

To compile:

```bash
javac MyCalculator.java
```

To run:

```bash
java MyCalculator
```

## Code Structure

- **MyCalculator.java:** Main class that sets up the calculator window, buttons, and labels.
- **MyDigitButton:** Handles digit and decimal inputs.
- **MyOperatorButton:** Handles arithmetic and special operations.
- **MyMemoryButton:** Handles memory functions.
- **MySpecialButton:** Handles backspace and clear operations.


## License

This project is for educational purposes. No specific license is attached.

## Author

Created by [ChakradharReddy01](https://github.com/ChakradharReddy01).
