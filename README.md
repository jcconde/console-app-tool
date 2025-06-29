# PHP Console Tool Base

## Overview

The **PHP Console Tool Base** is a framework designed to create console applications in PHP. It leverages the robust `symfony/console` component, providing a foundation for developers to quickly implement and organize their own console commands.

This tool is optimized for PHP versions 8.1+, adhering to modern PHP standards and practices.

---

## Features

- **Command-Line Structure**: Build and execute custom console commands effortlessly.
- **Customizable Project Layout**: Organize your project using the provided `app/code` directory.
- **Framework Leveraging**: Powered by `symfony/console` for superior functionality.
- **Development Tools**: Includes integrations for PHPStan, PHP Mess Detector (PHPMD), PHPUnit, PHP CodeSniffer, and PHP CS Fixer, for seamless code quality checks and testing.

---

## Quick Start

Follow these steps to get started with the project:

### 1. Clone and Install Dependencies

Clone the repository and install required dependencies:

### 2. Run a Test Command

The project includes a default test command to verify the setup. Run it using:

```
bin/console test:command
```

You should see the following output:

```
Execute test command...
````

### 3. Add Your Code

Organize your code within the `app/code` directory, structured for modularity. Each subfolder can encapsulate a separate set of functionalities.
