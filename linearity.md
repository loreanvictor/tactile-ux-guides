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

## Solution Template

Here, a template for design solutions satisfying linearity is proposed. Note that any solution for communicating the [five degrees of interactivity](/degrees-of-interactivity.md) with [clear](/clarity-and-consistency.md#clarity) and [consistent](/clarity-and-consistency.md#consistency) and in a linear fashion
can be considered a proper tactile experience design.

For this solution template, you can pick two independent visual indicators:

- _baseline_: needs to at least support two clearly distinct values, lets call them `on` and `off`
- _extent_: needs to at least support four clearly distinc values, lets call them `none`, `low`, `medium` and `high`

For example, _baseline_ can be a brighter background (or colorful background, etc), and _extent_ can be elevation.
Or _baseline_ can be having a clear rectangular border, and _extent_ be magnification, etc.

Each degree of interactivity will then be displayed using these combination of values:

<div align="center">

<sub>baseline</sub> \ <sup>extent</sup> | `none`           | `low`    | `medium`    | `high`
:-------------------------------------: | :--------------: | :----:   | :-------:   | :-------:
`off`                                   |  Not Interactive | Disabled | ❌          | ❌
`on`                                    |  ❌              | StandBy  | Interactive | Reaching Out

<br><br>
<img src="/figures/linear-example.gif" width="512"/>
<br>
<sub>In this example _baseline_ is background (gray / white) and _extent_ is elevation.</sub>
</div>

<br><br>
