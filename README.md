# Incorrect Self-Closing HTML Tags

This repository demonstrates a common, subtle error in HTML: improperly formatted self-closing tags.  Self-closing tags (like `<br/>`, `<hr/>`, `<img/>`, `<meta/>`, etc.) should not have a space before the closing `/`.

The `bug.html` file contains the incorrect code, while `bugSolution.html` provides the correction.  This often leads to unexpected rendering inconsistencies across different browsers.  This subtle bug can be difficult to track down in larger projects.

**Note:**  Ensure your HTML validator is configured to enforce strict standards for better error detection.