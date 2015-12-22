##Assignment 02 Feedback

###Let Content Determine Width/Height when Possible

In situations where you have a container (particularly when that container has a background image), it's best to let the height of the container be determined by the content within it, rather than specifying an explicit height with the `height` property, so that if that content adjusts, or the screen size is larger or smaller then what you are looking at, the height adjusts accordingly. See this example from the Testimonial section of the assignment: [http://codepen.io/poopsplat/pen/PZzEPm](http://codepen.io/poopsplat/pen/PZzEPm)

---

###Image backgrounds

You can set an image background like so:
```
.my-element {
    background-image: url('../images/my-background.jpg');
}
```
Background images can have a `size`, `position`, and a few other sub-properties applied. One useful `size` keyword value is `cover`, which sets a background image to fill the element, whether it has to stretch, or shrink, while maintaining its aspect ratio.