# Word Unscrambler

This Python module, `word_unscrambler`, is a versatile and user-friendly tool designed to find all word combinations from a set of letters. This module provides a reliable way to find these combinations, handling various scenarios, including input validation and error handling.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use the `word_unscrambler` module, you can simply install it using pip from the command line. Make sure to install `word_unscrambler` to the right python version (3.x), otherwise it will not work. There is no need to install other modules, as the required modules will be install when you install it using pip.

```python
pip install word_unscrambler
```

## Usage

You can use the `unscramble` function provided by the `word_unscramble` module to discover which words can be made from any combination of characters. Here's a basic example:

```python
import word_unscrambler as w

result = w.unscramble('enam')
print(result)  # Output: ['name', 'amen', 'mean', 'mane']
```

## Documentation

The `word_unscrambler` module includes detailed documentation in the form of docstrings. These docstrings provide information about the module's purpose, function arguments, return values, and usage examples. You can access this documentation using Python's built-in `help()` function or by viewing the docstrings directly in your code editor.

```python
import word_unscrambler as w

help(w.unscramble)
```

## Features

- **Input Validation**: The module ensures that input is all in the same case.

- **Error Handling**: If an invalid input is provided, the function will not break and will still return None.

- **Interactive Mode**: When run as a script, the module enters an interactive mode, allowing users to unscramble any word of their choice.

- **Documentation**: The module includes docstrings that provide information about its purpose, usage, and examples, making it easy for users to understand and use.

## Contributing

Contributions to this project are welcome! If you'd like to improve the module, fix a bug, or add a new feature, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Commit your changes and push them to your fork.
5. Open a pull request against the original repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This `README.md` file provides an overview of your project, including installation instructions, usage examples, documentation access, features, contribution guidelines, and licensing information. You can further customize it to match the specifics of your project if needed.
