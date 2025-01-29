# CSS calc() Function Errors

This repository demonstrates a common error encountered when using the `calc()` function in CSS. The error stems from the incorrect usage of units and operator precedence within the `calc()` function, which may lead to unexpected or erroneous layout.

The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.

## Problem

Incorrect unit usage within `calc()` function can result in unexpected width and height calculations which will break the layout and the page will not be responsive.  Using percentages and pixels without proper consideration and parenthesis can lead to incorrect results.