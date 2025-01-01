# JavaScript Bug: Loose Comparison and Null Handling

This repository demonstrates a common JavaScript bug related to loose comparison (==) and the implicit handling (or lack thereof) of null values.

## Bug Description

The `foo` function adds two numbers, but it does not explicitly handle `null` values.  Loose comparison can lead to unexpected results when `null` is involved, as demonstrated in the `bug.js` file.

## Solution

The `bugSolution.js` file provides a corrected version of the `foo` function. It explicitly checks for `null` values and returns `null` in those cases.  This prevents unexpected behavior.

## How to Run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run both files and observe the differences in output when `null` is passed as an argument.