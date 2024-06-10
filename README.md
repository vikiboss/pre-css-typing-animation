# Pure CSS Typing Animation

This repository contains the code for demonstrating a typing animation using purely CSS. The typing effect is achieved without any JavaScript, relying entirely on CSS animations and keyframes.

## See Online Example

[View the live example here.](https://vikiboss.github.io/pure-css-typing-animation)

## Key Concepts

This project leverages several important CSS concepts to achieve the typing animation effect:

- **CSS Animations**: Utilizes `@keyframes` to define the animation sequence from a starting point to an end point.

- **Animation Property**: Applies the animation to a selector using the `animation` shorthand property, which combines duration, timing function, and other animation properties.

- **Steps() Timing Function**: Utilizes the `steps()` function within the animation definition to create a stepping effect, making the animation appear like typing. This is crucial for simulating the discrete nature of typing.

- **ch Unit**: Uses the `ch` CSS unit to scale widths in a way that's relative to the character width of the font. This unit is particularly useful for text-related sizing as it can provide a measure that's more relevant to content width than pixels or ems.

- **Monospace Font**: The example uses a monospace font to ensure that each character occupies the same amount of space, adding to the realism of the typing animation.

- **Overflow and White Space**: Combines `overflow: hidden` with `white-space: nowrap` to contain the text within a specified width, ensuring that the typing effect works as expected without any text wrapping.
