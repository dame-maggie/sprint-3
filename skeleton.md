
What happens to the layout when you resize the screen to less than 550 px? How do you think that works?

When you resize the screen below that point the elements shift from lining up horizontally to lining up vertically. This is so they aren't too small when you view on smaller screens, but then, when you enlarge, that they aren't massive and can be better arranged in the bigger space.
It does this by having a media query checking when the screen is above 550px. At this point it makes some changes such as the max width some elements can have, how the display is arranged, and some of the distances between elements.
