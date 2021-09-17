### Notes:
- Cascade value -- A value for a particular property applied to
  an element as a result of the cascade.
- Declaring `display: initial` is equivalent to `display: inline`.
  It won't evaluate to `display: block` regardless of what type of
  element you apply it to. That's because `initial` resets the initial
  value for the property, not the element; `inline` is the default value
  for the display property.
- If you're working with a property that specifies two measurements
from a corner, think "cartesian grid". If you're working with one
that specifies measurements for each side all the way around an element,
think "clock".
- Keep selectors specificity under control.
- Don't confuse cascade with inheritance.
- Certain properties are inherited, including those for text, lists, and table borders.
- Don't cofuse initial and auto values.
- Stay out of TRouBLe with shorthand properties.
