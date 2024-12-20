# CSS calc() Unexpected Calculation Results
This repository demonstrates an uncommon CSS error related to the `calc()` function. The issue arises when the calculation within `calc()` results in an invalid CSS value, such as a negative dimension.  This can lead to unexpected layout behaviors, as the browser may interpret the invalid value differently.

The `bug.css` file contains the problematic code, while `bugSolution.css` shows how to handle potential errors and provide fallback values.

This example showcases a scenario where a negative width is calculated.  The solution demonstrates how to use `max()` or `clamp()` to ensure the width doesn't become negative and the layout remains consistent.