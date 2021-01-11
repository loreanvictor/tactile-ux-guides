<div align="center">

<img src="/logo.svg" width="360"/>

# Linearity

</div>

<br><br>

Linearity refers to natural ordering intuitively imposed by the visual indicators of the degree of interactivity of elements, in terms of how much they draw
user attention to themselves. Simply put:
- [Not Interactive](/degrees-of-interactivity.md#not-interactive) elements **SHALL** draw less attention to themselves
than [Disabled](/degrees-of-interactivity.md#disabled) elemenets
- [Disabled](/degrees-of-interactivity.md#disabled) elemenets **SHALL** draw less attention
to themselves than [Standby](/degrees-of-interactivity.md#standby) elemenets
- [Standby](/degrees-of-interactivity.md#standby) elemenets **SHALL** draw less attention
to themselves than [Interactive](/degrees-of-interactivity.md#interactive) elemenets
- [Interactive](/degrees-of-interactivity.md#interactive) elemenets **SHALL** draw less attention to themselves than elements that are
[Reaching Out](/degrees-of-interactivity.md#reaching-out)

<br><br>

## Continuous Visual Indicators

Some visual indicators can be placed in a continuous space. For example, `opacity` can be any number between `0` and `1`, elevation can be any value
from `0` to `∞`. Luminosity (or contrast with background) are other examples.

Use of continuous visual indicators for representing various degrees of interactivity is highly **RECOMMENDED**, as users can intuitively percieve
linearity and by extension, the degree of interactivity of elements. This notion can even further be enhanced by natural transitions between various
degrees of interactivity.

<br><br>
