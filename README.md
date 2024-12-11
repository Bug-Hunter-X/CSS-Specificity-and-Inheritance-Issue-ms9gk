# CSS Specificity and Inheritance Issue

This repository demonstrates a common yet subtle bug in CSS related to specificity and inheritance. The bug arises from unexpected behavior when combining selectors with inheritance.  A child element may inherit a style from its parent but be overridden by a more specific selector.

The `bug.css` file contains the erroneous code. The `bugSolution.css` file offers a potential fix by explaining and reorganizing the rules to correctly prioritize styles.