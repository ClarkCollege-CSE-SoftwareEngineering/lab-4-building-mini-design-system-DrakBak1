Jarryd Toves
1/30/2026

Reflection question 1: Organizing the colors by semantics (i.e. green as success or yellow for warning) helps in the naming convention when assigning warning colors in future. Rather than looking over 100's of shades of yellow and assigning it to any individual warning the ability is to instead have a predefined package for any warning and easily assign it where it need be, thus making the semantic package interchangeable and convenient for the developer.

Reflection question 2: You would simply need to change the values of the spacing values, since the values are stored in the name every instance of the value being used throughout the value will be changed automatically as opposed to finding every instance and changing it manually.

Reflection question 3: Only a few files actually change the button. So if the buttons would be needed to change then you would only need to go in and switch the needed values for the desired button changes. This demonstrates how organized and effective atomic design can be.

The lab demonstrates atomic design's value by composing a molecule from atoms: Icon, Text, and Button. Each atom has a single defined responsibility but when combined form a cohesive functioning UI component. The Alert molecule is more useful than any individual atom, yet it doesn't duplicate logic or styling. 

Design tokens maintain consistency across components. Colors, spacing, and typography are defined once and reused elsewhere making a unified visual project. Because components rely on tokens instead of hardcoded values updating to branding or layout can be done centrally without needing to recreate individual components.

For a dark mode to be added most changes would occur in the token files. New color values for backgrounds, borders, and text could be defined for dark mode whereas the components themselves would remain unchanged. This separation of design from component logic highlights the scalability/flexibility of the token based atomic design system.

Atomic design hierarchy (atoms, molecules, organisms, templates, pages)

Component reusability and interchangeable design

design token enforcing consistency 

abstraction simplifies large scale project design