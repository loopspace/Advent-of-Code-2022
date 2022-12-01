# Advent of code 2022

This year's competition is at [this
url](https://adventofcode.com/2022).

## Using LaTeX3

I've learnt from [last
year](https://github.com/loopspace/Advent-of-Code-2021) and am using a
simple LaTeX3 file for the core code with a document wrapper for the
nice typesetting.

I'm using the same function paradigm whereby a "function" defines a
scope and so to return a value then there are certain `output`
registers (one of each type) that get set globally, and which can then
be read for the solution.
