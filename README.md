# Uncommon HTML Bug: innerHTML on Non-Existent Element

This repository demonstrates a subtle but important bug in HTML involving the `innerHTML` property.  Attempting to modify the `innerHTML` of an element that doesn't exist in the Document Object Model (DOM) will result in a runtime error, preventing your JavaScript from functioning correctly.

The `bug.html` file shows the erroneous code, while `bugSolution.html` provides the corrected version.

**Key Learning:** Always check if an element exists before manipulating its properties, especially when dealing with dynamically generated content or user interactions.