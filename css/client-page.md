# Differences between Client X/Y and Page X/Y

`pageX`, `pageY`, `screenX`, `screenY`, `clientX`, and `clientY` returns a number which indicates the number of physical “CSS pixels” a point is from the reference point. The event point is where the user clicked, the reference point is a point in the upper left. These properties return the horizontal and vertical distance from that reference point.

`pageX` and `pageY`:
Relative to the top left of the fully rendered content area in the browser. This reference point is below the URL bar and back button in the upper left. This point could be anywhere in the browser window and can actually change location if there are embedded scrollable pages embedded within pages and the user moves a scrollbar.

`screenX` and `screenY`:
Relative to the top left of the physical screen/monitor, this reference point only moves if you increase or decrease the number of monitors or the monitor resolution.

`clientX` and `clientY`:
Relative to the upper left edge of the content area (the viewport) of the browser window. This point does not move even if the user moves a scrollbar from within the browser.

## Reference

[What is the difference between screenX/Y, clientX/Y and pageX/Y?](https://stackoverflow.com/questions/6073505/what-is-the-difference-between-screenx-y-clientx-y-and-pagex-y)
