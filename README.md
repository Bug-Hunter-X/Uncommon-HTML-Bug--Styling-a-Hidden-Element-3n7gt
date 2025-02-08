# Uncommon HTML Bug: Styling a Hidden Element

This repository demonstrates a subtle bug related to styling HTML elements that have been hidden using `display: none;`.

The `bug.html` file contains the problematic code.  The issue occurs when attempting to modify the style of an element after setting its `display` property to `none`.  This can lead to inconsistent results or errors across different browsers.

The `bugSolution.html` file provides a corrected version, illustrating best practices for handling such situations.  Specifically, it checks if the element is visible before attempting to modify its style.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Click the "Click Me" button.
4. Observe the behavior (or lack thereof) in your browser's developer console.
5. Compare this to the behavior of `bugSolution.html`.

## Solution
The solution involves checking the element's visibility before applying style changes.  This avoids potential errors and ensures consistent behavior across browsers.