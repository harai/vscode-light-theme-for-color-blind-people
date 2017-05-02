# Light Theme for Color Blind People

This is a VSCode color theme for partially color-blind people.

The actual coloring follows these guidelines:

* Do not use many colors
    * As the number of color increases, it gets harder and harder to distinguish them instantly.
* Do not use vague colors
    * Vague colors are also hard to distinguish.
* Use **blue** *(#0000FF)* for keywords-like values
    * In addition to strict reserved keywords such as `if` and `function`, keyword-ish values can be blue. For example, in HTML, tag names should be blue since they are the most keyword-ish values in typical HTML files.
* Use **red** *(#FF0000)* for literal-like values
    * As blues could be used for non-strict keyword values, red could be used for non-strict literal values as well.
* Use **grey** for comments
* Use **black** *(#000000)* as the default foreground color
* Use **white** *(#FFFFFF)* as the default background color
* Make chunks of colors
    * Large chunk of a color is easier to distinguish than a single character with the same color applied.
* Never use green
    * For most partially color-blind people, green and red are the most conflicting pair.