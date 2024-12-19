# CSS Specificity Issues: Unexpected Styling and Conflicts

This repository demonstrates a common yet subtle CSS issue related to selector specificity.  The problem arises from using selectors that are either too broad (affecting unintended elements) or too narrow (failing to style intended elements). This can lead to unexpected visual results and frustrating debugging sessions.

The `bug.css` file contains the problematic CSS, while `bugSolution.css` offers solutions using more precise selectors, addressing the specificity issue.

**Problem:** Incorrect selector usage causes unintended styling.

**Solution:** Refine selectors using techniques like IDs, classes, or more specific child selectors (`>`) to ensure accurate style application.