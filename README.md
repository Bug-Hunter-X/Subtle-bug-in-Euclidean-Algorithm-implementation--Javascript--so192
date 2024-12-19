# Euclidean Algorithm Bug

This repository demonstrates a subtle bug in a Javascript implementation of the Euclidean algorithm for finding the greatest common divisor (GCD) of two integers. The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected version.  The bug lies in the handling of zero inputs, leading to unexpected behavior in certain edge cases.  Read the comments in the code files for more details.

## Bug Description:
The original code incorrectly handles cases where one or both inputs are zero.  This leads to inaccurate GCD calculations in these scenarios.