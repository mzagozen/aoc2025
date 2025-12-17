# Advent of Code 2025 in Acton

This year, I chose to use [Acton](https://github.com/actonlang/acton) to solve
the puzzles. Acton lets you write code that feels like Python, but it also
offers the advantage of strong typing and execution speed that is comparable to
a C program.

## Running the code

To run the tests with sample data:

1. install Acton: https://www.acton-lang.org/install/
2. `acton test` to run all the tests on sample inputs

This repository does not include the input files, only sample data for each
puzzle. You can place your input files in the `input/` directory as
`input/dXY.txt` text files. Then you can compute a solution specific to your
input file:

1. compile the dXY executable: `acton build`,
2. running `out/bin/dXY`