
===== Rainbow Circles Solution =====

Using only CSS, style the HTML to have the appearance of
six concentric colored circles.

From outside to inside, the circles should have the following
characteristics:

- 300px by 300px, #ff0000
- 250px by 250px, #ffa500
- 200px by 200px, #ffff00
- 150px by 150px, #0080000
- 100px by 100px, #0000ff
- 50px by 50 px, #800080


===== Solution =====
Since there are 6 colors and only 3 div, some of the 
colors will need to come from borders.

Start from the innermost circle, using
background-color, width, height, border and paddding to 
create the colors

finally use div to assign border-radius of 50% to create
a perfect circle for all layers 

