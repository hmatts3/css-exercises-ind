# The Holy Grail of Layout

In this last flexbox exercise you're going to recreate an incredibly common website layout. It is so common that it is often called the [Holy Grail](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img) layout... and with flexbox it is actually pretty easy to pull off.

As with the previous exercise, we've left a little more for you to do.

### Hints
- You will need to change the flex-direction to push the footer down.
- You will need to add some divs as containers to get things to line up correctly.
- `flex-wrap` will help get the cards aligned correctly.
-  Make sure you define how much space the cards should take up, in order for `flex-wrap` to work as intended.

## Desired outcome

![desired outcome](./desired-outcome.png)

The number of cards lined up in that section will change based on the width of your screen, so don't stress about getting _exactly_ a 2x3 or 3x2 grid.

On a smaller screen it will look like this:

![smaller](./desired-outcome-smaller.png)

### Self Check
- The header text is size 32px and weight 900. # size 32 weight 800
- The header text is vertically centered and 16px from the edge of the screen. # Yes and 10
- The footer is pushed to the bottom of the screen (the footer may go _below_ the bottom of the screen if the content of the 'cards' section overflows and/or if your screen is shorter). # yes via flex column, middle section only grows
- The footer text is centered horizontally and vertically. # yes nested flex justify, align. 
- The sidebar and cards take up all available space above the footer. # yes flex 1
- The sidebar is 300px wide (and it doesn't shrink). # yes 0 0 auto
- The sidebar links are size 24px, are white, and do not have the underline text decoration. # yes 20 px
- The sidebar has 16px padding. # NO couldn't figure this out - figured it out; made ul margin/padding 0
- There is 32px padding around the 'cards' section. # did 70 and 20 for some reason
- The cards are arranged horizontally, but wrap to multiple lines when they run out of room on the page. # yep - through max height and max width; could have just done width

I think i got it. Could make it more efficient, understand a bit better. 

