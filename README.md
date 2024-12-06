# Unexpected Behavior of `calc()` in CSS with Percentages and Viewport Units

This repository demonstrates an uncommon issue related to the CSS `calc()` function when used with percentages or viewport units (vw, vh). The issue involves unexpected calculations and inconsistencies across different browsers.  The `bug.css` file contains the problematic code, while `bugSolution.css` provides a potential fix.

## Problem Description

The `calc()` function in CSS is powerful for dynamic calculations, but it can be prone to errors if not used carefully. When combining percentages with fixed values (like pixels), the calculation order and unit compatibility needs to be meticulously considered.  The bug demonstrates a scenario where the expected width of an element is not achieved.

## Solution

The solution involves a thorough review of the calculation and potentially using alternative methods to achieve the desired outcome.  The provided solution might involve adjusting the calculation order or using different units to ensure compatibility and expected results across browsers.