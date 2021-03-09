# CSS (Chapter 15: Layout)

* `<div>` elements are often used as containing elements
to group together sections of a page.
* Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
* The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
* Pages can be fixed width or liquid (stretchy) layouts.
* Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
* Grids help create professional and flexible designs.
* CSS Frameworks provide rules for common tasks.
* You can include multiple CSS files in one page.

example:
![tables](https://www9.0zz0.com/2021/03/08/16/700197167.png).



### there is several positioning ways in CSS: 
1-the first one is the default one which is static positioning where each block-level element sits on the top of the next one 
position: static;
2-the second one is relative positioning which is simply where you want to move the block-level element from its 
default position from the 4 sides:
position: relative;
left: 100px;
top: 50px;
so it will move to the right for 100px and to the bottom for 50px
3-the third type of positioning is absolute positioning and what you can benifit from this kind of positioning is that the 
element that is given a absolute positioning it will act and position where ever you like and will deal with other elements aas if 
they are not visible 
position: absluote;
4-the fourth type of positions is fixed which is type of the absolute position but the fixed element will stay on the screen 
even if the user scrolls up and down and the most common use for it is the heading of the web page
position: fixed;
5- the fifth one is z- index which is used for overlaping elements, so this positioning is related to the previous one
when you determine a fixed position element the browser will make the elements that comes later on top on the element 
that came first so in order to manage what to appear on top of what you can use:
z- index: 10; /// note that the more the value the more the element is close to the top 
6-The float property allows you to take an element in normal flow and place it as far to the left or right of the containing
element as possible.
Anything else that sits inside the containing element will flow around the element that is floated.
position: float;
width: 200px;
