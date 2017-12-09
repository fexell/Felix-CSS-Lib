# Felix-CSS-Lib
My Work In Progress Lib

This is a work in progress "library" to make my workflow faster and easier. If others want to use it, they can.

Flexbox
-------------------------------------

Check the unminified "flexbox.css" version for a more extensive read on the classes.


`.flexbox, .fbox` - The main flexbox CSS class to make the flex possible (with the display: flex and its fallbacks for older browser versions).

```
.flex-order-1,
.fo1,
.f-o-1,
.flor1,
.fl-or-1
```
To order the flexbox items/children, up to 4 (basically changed the number **1** to 2, 3, 4, 5, 6, 7, 8). Higher values will be added in due time.

`.flexbox-row or .flexbox-column` - To either make the flexbox children align in a row or column direction/manner.

```
.auto-flex, /* For Auto-Flex, give the container of the flexboxes the .flexbox class. Otherwise it won't auto-grow. */
.a-f, /* Auto */
.aufl,
.au-fl,
.aflex,
.flex-auto,
.f-a,
.flau,
.fl-au,
.flexa,
.one-flex, /* 1 */
.o-f,
.ofl,
.o-fl,
.oflex,
.flex-one,
.f-o,
.flon,
.fl-on,
.flexo,
.flex-1,
.two-flex, /* 2 */
.twfl,
.tw-fl,
.twflex,
.flex-two,
.fltw,
.fl-tw,
.flextw,
.flex-2,
.three-flex, /* 3 */
.thfl,
.th-fl,
.thflex,
.flex-three,
.flth,
.fl-th,
.flexth,
.flex-3,
.four-flex, /* 4 */
.ff,
.fofl,
.fo-fl,
.fflex,
.flex-four,
.flfo,
.fl-fo,
.flexfo,
.flex-4,
.five-flex, /* 5 */
.fif,
.fifl,
.fi-fl,
.fiflex,
.flex-five,
.flfi,
.fl-fi,
.flexfi,
.flex-5
```
All the flex options (`flex: <number>`). Multiple for each to give more choices and fallbacks.

`.flexbox-left, .fbox-left` - The justify content for flex. One can change "left" into: right, center, space-between and/or space-around.

```
.flexbox-stretch, .fbox-stretch,
.flexbox-stretch-items, .fbox-stretch-items,
.flexbox-stretch-self, .fbox-stretch-self
```
For the flex "align". Change stretch to either: center, flex-start, flex-end, space-between and/or space-around.

** PRESETS / ALREADY DONE FLEXBOX LAYOUTS **
--------------------------------------------
These presets/layouts should work from start. Give the container the flexbox main CSS class name.

FLEXBOX-1
--------------------------------------------
`.flexbox-1` - Will give you a header, a section/content with 2 rowed flexboxes and a footer. Remember it will always be 100% width and 100vh height, no matter the screen size.

**Example 1:**
```
<div class="flexbox-1">

  <header></header>
  
  <section>
    <article></article>
    <aside></aside>
  </section>
  
  <footer></footer>
  
</div>
```
**Example 2:**
```
<div class="flexbox-1">

  <div></div> <!-- HEADER DIV -->
  
  <div> <!-- SECTION / CONTENT DIV -->
    <div></div> <!-- ARTICLE / LEFT SIDE CONTENT -->
    <div></div> <!-- ASIDE / RIGHT SIDE CONTENT -->
  </div>
  
  <div></div> <!-- FOOTER DIV -->
  
</div>
```


