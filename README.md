# CSS Specificity Gotcha: Unexpected Selector Override

This repository demonstrates a subtle bug related to CSS specificity and the cascade.  The bug arises from a misunderstanding of how specificity is calculated, leading to unexpected style overrides.

## Bug Description
The CSS code in `bug.css` showcases a situation where a seemingly less specific selector unexpectedly overrides a more specific one due to the way specificity is calculated in CSS.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` (or create your own HTML with the corresponding elements).
3. Observe the unexpected color of the nested `div` element.

## Solution
The solution, provided in `bugSolution.css`, demonstrates how to correctly apply the styles to achieve the desired outcome.

## Lesson Learned
This example highlights the importance of understanding the nuances of CSS specificity.  It's not just about the number of selectors but the types of selectors and their order.  IDs have the highest specificity followed by classes and then element types. Careful consideration of specificity is vital in avoiding unexpected styling behavior.