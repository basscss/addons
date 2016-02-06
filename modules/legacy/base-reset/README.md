
This module resets a few basic values for the body, img and svg elements.

Note: this reset does **not** set box-sizing to border-box using the universal selector.
This is meant to discourage declaring widths unnecessarily throughout a stylesheet.
The base form and grid modules use border-box where widths are used,
and a `.border-box` utility is available in the utility-layout module.

This reset intentionally does not normalize cross-browser discrepancies.
If you would like to normalize styles, use [normalize.css](http://necolas.github.io/normalize.css/).

