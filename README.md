<div align="center">

<img src="/logo.svg" width="256"/>

# Tactile UX
A guide for designing tactile user experiences.

</div>

<br><br>

Tactile UX denotes user experience where state of interactivity of various elements is clearly and consistently communicated to the user. It is intended for contexts where a combination of interactive and non-interactive elements are present. Following these guides ensures that users can quickly and efficiently determine the state of interactivity of the UI with minimum error (error is when a user misses an interactive element, or where they mistake a non-interactive element for an interactive element).

👉 Tactile UX is **NOT** for contexts where most elements are interactive. It focuses on clear and explicit signaling of interactivity, which leads to visual clutter in contexts where most elements are interactive. Specifically, it is **NOT** to be used for designing input widgets (such as onscreen keyboards on smartphones, etc.).

👉 In this document, terms **MUST**, **SHALL**, **RECOMMENDED**, **MAY**, etc, when appear in caps and bold, are used per [this RFC](https://www.ietf.org/rfc/rfc2119.txt).


<br><br>


## Overview

Tactile UX aims to increase usability of interfaces with a combination of interactive and non-interactive elements. It helps users quickly understand what can they do with a particular interface and what they might be able to do. This is achieved by defining five degrees of interactivity that apply to ALL visual elements, and requiring _consistent_ and _clear_ visual indicators for each degree of interactivity.

#### Clarity

A visual signal is _clear_ if it is easily noticeable in a quick glance. A clear visual signal is not mistaken for another, and it is hard to miss. Clarity is subjective and open to interpretation, and differs based on context. For example, sufficient degree of clarity differs greatly based on age-range and/or professional background of target users.

#### Consistency

A particular piece of information is communicated by visual cues in a _consistent_ manner, when the very same design rules are utilized to communicate said information. For example, interactive elements are communicated consistently by a _blue left border_ when all interactive elements have a blue left border and other visual element that has a blue left border is also interactive.

Consistency should be required / applied with awareness of context. The goal of consistency is to increase learnability and memorability: for example is interactivity is only communicated by _blue left borders_, then users need to learn (and recall) one rule: _blue left borders mean interactivity_. If multiple inconsistent rules are used, the amount of rules the user should learn (and recall) will increase, which negatively affects learnability / memorability. That said, prior familiarity greatly affects that: for example a lot of users are already familiar with a _checkbox_ and expect it to be interactive regardless of existence of a blue left border, so consistency in this case can be applied with a more relaxed approach.


