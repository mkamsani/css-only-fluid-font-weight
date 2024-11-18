# CSS-Only Fluid Font Weight

Using CSS to adjust font-weight based on screen width.

## Demo

https://html-preview.github.io/?url=https://github.com/mkamsani/css-only-fluid-font-weight/blob/main/index.html

## Usage

You will need to rework the measurements so that a smaller viewport width would be assigned a slightly larger font-weight.
See [this side-by-side comparison of Geist in medium weight at a smaller screen size](https://pimpmytype.com/font/geist/#:~:text=After,%20readable).

This implies using a variable font:

- Google Fonts - [Introducing variable fonts](https://fonts.google.com/knowledge/introducing_type/introducing_variable_fonts)
- v-fonts.com - [Resource for finding and trying variable fonts](https://v-fonts.com/)

Legibility after adjustments will vary based on the font used.

## References

- Temani Afif: [Update CSS variables using range slider](https://css-tip.com/css-variables-range-slider/)
- Jane Ori: [CSS Type Casting to Numeric: tan(atan2()) Scalars](https://dev.to/janeori/css-type-casting-to-numeric-tanatan2-scalars-582j)
- Mandy Michael: [Fluid Font Weight with Viewport Size - Variable Fonts](https://codepen.io/mandymichael/pen/oPoaEL)
