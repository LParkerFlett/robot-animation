# robot-animation
Robot animation with html and css

Practice using HTML and CSS learned in Zero to Mastery Frontend Developer course.

Note to self on natural stacking order within CSS:
The reason the torso overlaps the legs is due to the fact that the .torso element has a height of 200px, whereas its parent container, .upper_body, only has a height of 150px. This causes the torso to overflow its parent container.

What's happening:
The .upper_body container is set to a height of 150px, but the .torso element inside it is 200px tall.

Because of this, 50px of the torso overflows the .upper_body container, pushing into the space where the legs are located.

Since there is no specific rule to prevent the torso from overflowing, this natural overflow allows the torso to appear to overlap the top part of the legs.
