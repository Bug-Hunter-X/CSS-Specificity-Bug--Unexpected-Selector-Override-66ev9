# CSS Specificity Bug: Unexpected Selector Override

This repository demonstrates a subtle CSS specificity bug where a more specific selector unexpectedly overrides a less specific one, resulting in unintended styling. 

The `bug.css` file contains the erroneous code, while `bugSolution.css` provides a corrected version.

The issue arises from the fact that `div.container` is more specific than `.container`.  Understanding CSS specificity is crucial for avoiding such issues.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected background color of the container.
4. Then compare this with `bugSolution.html`.