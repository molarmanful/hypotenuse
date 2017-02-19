# hypotenuse
A basic CSS-only library for mathematical formatting. Meant as a proof-of-concept rather than a real alternative to existing math formatting libraries.

#Specs
The library mainly provides formatting not easily achievable through only Unicode. It is extremely fast compared to other math formatting libs because it uses a small amount of HTML and CSS to render the necessary syntax.

The library uses DejaVu Sans Mono for wider Unicode support and more consistent spacing. All font units are expressed in `em`s for easy scaling.

# Usage
`hypot.css` contains the distribution code. Wrap all formatting in `expr` tags.

##Tags
###`e`, `sub`
Superscript/subscript tags that are compatible with `hypotenuse` formatting.
###`f` --> `n`, `d`
Fraction. `n` is numerator, `d` is denominator.
###`sum`, `prod` --> `i`, `l`
Summation and product notation. `i` is the lower limit, `l` is the upper limit.
###`int`, `ev` --> `l`, `u`
Integral and evaluation block. `l` is lower bound, `u` is upper bound.
###`r`, `rn`
Radical. `rn` is an optional tag that goes before `r` and defines the radical's power.
