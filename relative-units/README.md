### Notes:
- Values declared using relative units are evaluated by the browser to an absolute value, called the _computed value_.
- The root node is the ancestor of all the elements in the document. It has a special pseudo-class selector `:root` that you can use to target it. This is equivalent to using the type selector `html` with the specificity of a class rather than a tag.
- `rem` is short for root em. Instead of being relative to the current elements, rems are relative to the root element. No matter where you apply it in the document.
- Best practice is using `rem` for font sizes, `px` for borders, and `em` for most other measures, especially padding, margins, and border radius (though favor to use percentages for container widths when necessary).
- A unitless 0 can be used only for length values and perecentages, such as padding, borders, and widths. It can't be used for angular values, such as degree or time-based values like seconds.
- The `line-height` property is unusual in that it accepts both units and unitless values. You should always use unitless values because they're inherited differently. When you use a unitless number, that declared value is inherited, meaning its computed value is recalculated for each inheriting child element.
