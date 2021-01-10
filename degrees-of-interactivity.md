<div align="center">

<img src="/logo.svg" width="360"/>

# Degrees of Interactivity

</div>

<br><br>

Tactile UX revolves around five different degrees of interactivity that apply to all visual elements. The core idea is to communicate the degree of
interactivity of any element at all times in a [clear](/clarity-and-consistency.md#clarity) and [consistent](/clarity-and-consistency.md#consistency) manner
to obtain a _tactile user experience_ (i.e. the degree of interactivity of all elements **MUST** be communicated clearly and consistently at all times).

Here are the five degrees of interactivity:

<br>

### Not Interactive

This denotes visual elements that will never become interactive in any manner whatsoever. This includes text, images, content dividers, etc.
For these guides, in-text links are also considered not interactive, despite them having an interaction.

<br>


### Disabled

This denotes elements that are not interactive in current program state, but might become interactive in a different state.
This includes submit buttons that are disabled because some input data is invalid, or inputs that are readonly due to user permissions.

<br>

### Standby

This denotes elements that are not interactive currently, but might become interactive with some future event (which is typically less significant
than a _change in program state_). This includes non-focused inputs, save buttons after being pressed but before getting the response from
the server, etc.

👉 The difference between _Standby_ and _Disabled_ is purely based on significance of events that are required for the element to become interactive.
The judgement of significance of such events are completely up to programmers / designers and context dependent.

<br>

### Interactive

This denotes elements that can readily be interacted with. This includes buttons, cards, focused inputs, etc.

👉 Inputs by default have _focus_ / _blur_ interaction, but since this is a secondary interaction, when not focused they are considered to be in _Standby_.
The main interaction of an input is for example keyboard input, so the input is _Interactive_ only when using the keyboard interacts with it.

<br>

### Reaching Out

This denotes elements that are actively trying to grab user's attention to interact with them. This includes hovered buttons (optional), inputs whose
value need correction before the user can proceed, submit buttons when input data is complete and valid, etc.

