Rob Morgan - Static Comp 1

This is a static webpage built for Turing School of Software & Design.

Live version: https://rmorgan323.github.io/rm-comp-challenge-1/

I started with a few goals.  First, I wanted the content to fill the screen width on all screen sizes.  Second, I wanted the boxes to stay square on any screen size and not collapse in anyway, with only the orientation of the boxes to change on smaller screens.  After that, I tried to make things look nice.  

I achieved these things by using CSS grid to lay out the page and flexbox to position elements within the boxes.  There are background images underneath the squares that show up on hover.  That was done by putting an extra `<div>` inside the squares, putting a background on it, and lowering the opacity on the top element on hover.  I think the effect turned out pretty cool.

As a result of all of this, there is more CSS than I would have guessed for a page of this size, but it's organized, clean, and understandable and redundancy has been reduced as much as possible.

**********

![screenshot](assets/sc-2.png)
