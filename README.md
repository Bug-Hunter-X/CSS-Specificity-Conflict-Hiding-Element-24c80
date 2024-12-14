# CSS Specificity Conflict

This repository demonstrates a common CSS issue where a specificity conflict prevents an element from being hidden, even though `display: none;` is applied.  The `bug.css` file shows the conflicting CSS rules, and the `solution.css` file provides a fix.

**Problem:** The element with the class `hidden` should be hidden, but it remains visible due to a specificity issue.  The solution involves understanding and addressing the specificity conflict to ensure the correct styling is applied.

**Solution:**  Several approaches exist, including increasing the specificity of the `.hidden` rule, using the `!important` flag (use cautiously!), or reorganizing the CSS to ensure the intended rule takes precedence.