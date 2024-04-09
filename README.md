 # Custom Lisp Project

## Overview

This project is a custom implementation of the Lisp programming language. It aims to provide a minimalistic yet functional Lisp interpreter with basic functionality. The interpreter supports common Lisp features such as symbolic expressions, basic arithmetic operations, variable bindings, and user-defined functions.

## Features

- **Symbolic Expressions**: The interpreter supports the evaluation of symbolic expressions, allowing users to perform calculations and manipulate data.
- **Arithmetic Operations**: Basic arithmetic operations such as addition, subtraction, multiplication, and division are supported.
- **Variable Bindings**: Users can define variables and assign values to them, allowing for reusable code blocks.
- **User-Defined Functions**: Functions can be defined by users to encapsulate and reuse code logic.

## Usage

To use the Lisp interpreter, follow these steps:

1. Clone the repository: `git clone https://github.com/gautamsingh6599/custom_lisp.git`
2. Navigate to the project directory: `cd custom-lisp`
3. Run the interpreter: `./lisp`

Once the interpreter is running, you can start entering Lisp expressions for evaluation. Here are some examples:

```lisp
;; Basic arithmetic operations
(+ 1 2 3) ;=> 6
(* 2 3 4) ;=> 24

;; Variable bindings
(define x 5)
(define y 10)
(+ x y) ;=> 15

;; User-defined functions
(define (square x) (* x x))
(square 3) ;=> 9
```

## Project Structure

The project structure is organized as follows:


## Contributing

Contributions to the project are welcome! If you have any ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

Special thanks to the creators of Lisp and the numerous resources available online that helped in understanding and implementing the language.
