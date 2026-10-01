# Parallel Computing Calculator

## Project Overview

This project is a basic Python calculator developed for a Distributed and Parallel Computing task. It performs four basic arithmetic operations and demonstrates the difference between sequential and parallel execution.

## Basic Operations

The calculator performs:

- Addition
- Subtraction
- Multiplication
- Division

## Sequential Computing

In sequential execution, the calculator performs each operation one after another.

The execution time is measured using Python's `time.perf_counter()` function.

## Parallel Computing

In parallel execution, the calculator uses Python's `multiprocessing` module.

Four separate processes are created:

- Addition process
- Subtraction process
- Multiplication process
- Division process

These processes can execute independently.

## Execution Time

The program measures and compares the execution time of both approaches.

Example:

```text
Sequential Time: 0.000018 seconds
Parallel Time: 0.462 seconds

