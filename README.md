# Uncommon Tailwind CSS Bugs and Errors

This repository demonstrates some uncommon errors encountered when using Tailwind CSS, along with their solutions.

## Common Issues

* **Conflicting CSS Rules:** Overlapping specificity in CSS rules can lead to unexpected styles.  Prioritize your styles carefully.
* **Unpurged CSS:** Unused CSS classes in production builds increase file size.  Ensure your build process purges unused styles.
* **Misconfigured Plugins:** Incorrectly configuring Tailwind CSS plugins can lead to unexpected behavior.
* **Conflicting Utility Classes:** Applying multiple utility classes with conflicting styles to the same element can produce unexpected results.

## How to reproduce

The `bug.css` file contains code exhibiting these problems. Run a build to see the resulting effects. The solutions are presented in `bugSolution.css`.