# Felix-CSS-Lib
My Work In Progress Lib

This is a work in progress CSS file to make my workflow faster and easier. If others want to use it, they can.

Flexbox
-------------------------------------

**.flexbox, .fbox** - The main flexbox CSS class to make the flex possible (with the display: flex and its fallbacks for older browser versions).

**.flex-order-1,
.fo1,
.f-o-1,
.flor1,
.fl-or-1** - To order the flexbox items/children, up to 4 (basically changed the number "1" to 2, 3 or 4). Higher values will be added in due time.

**.flexbox-row or .flexbox-column** - To either make the flexbox children align in a row or column direction/manner.

**.auto-flex,
.a-f,
.aufl,
.au-fl,
.aflex,
.one-flex,
.ofl,
.o-fl,
.oflex,
.two-flex,
.twfl,
.tw-fl,
.twflex,
.three-flex,
.thfl,
.th-fl,
.thflex,
.four-flex,
.ff,
.fofl,
.fo-fl,
.fflex** - All the flex options (flex: <number>). Multiple for each to give more choices.

**.flexbox-left, .fbox-left** - The justify content for flex. Can changed "left" into: right, center, space-between and/or space-around.

**.flexbox-stretch, .fbox-stretch,
.flexbox-stretch-items, .fbox-stretch-items,
.flexbox-stretch-self, .fbox-stretch-self** - For the flex "align". Change stretch to either: center, flex-start, flex-end, space-between and/or space-around.

** PRESETS / ALREADY DONE FLEXBOX LAYOUTS **
--------------------------------------------
These presets/layouts should work from start. Give the container the flexbox main CSS class name.

FLEXBOX-1
--------------------------------------------
**.flexbox-1** - Will give you a header, a section/content with 2 rowed flexboxes and a footer. Remember it will always be 100vw and 100vh, no matter the screen size.

Check the unminified version for a more extensive read on the classes.
