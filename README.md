# CSS Nested :hover Pseudo-class Issue

This repository demonstrates a subtle bug related to the CSS `:hover` pseudo-class when applied to nested elements.  In some browsers, the hover effect does not propagate correctly to inner elements.

## Problem
The provided `bug.css` file contains CSS that attempts to style a nested `<a>` element using the `:hover` pseudo-class.  However, the expected hover effect does not always occur.

## Solution
The `bugSolution.css` file provides a corrected version of the CSS, fixing the issue and ensuring consistent behavior across different browsers.

This is likely caused by specificity issues or the inheritance model of certain CSS properties. The solution employs a more robust approach to style the nested elements.