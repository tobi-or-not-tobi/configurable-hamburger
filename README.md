# configurable-hamburger

css hamburger menu driven by css variables

The intend of this small repo is to demonstrate (and provide) a small hamburger menu implementation that is configurable by CSS custom properties

## Supported custom properties

| property             | description                                                           | default |
| -------------------- | --------------------------------------------------------------------- | ------- |
| --cx-width           | Main property that influence width, height, and _calculated_ padding  | 3vmax   |
| --cx-color           | The color of the lines. The color after focus can set on the selected | #fff    |
| --cx-border-width    | The width of the lines.                                               | 2px     |
| --cx-transition-time | The transition time for animating 3 lines to cross                    | 0.4s    |
| --cx-factor          | The grow factor for the lines when they turn into a cross             | 10%     |

## Effects

This hamburger menu only supports a single effect, the _traditional_ hamburger-to-cross animation.

-   the key effects are bound to the focus of the hamburger element as well as an `.active` class
-   all changes are animations are done by css transitions
-   the upper and bottom line rotate in order to transition lines into a cross
-   the inner line dispears
