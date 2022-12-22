
===== Guid to the solution =====

* bar consists of two unordered lists, containing three and two list items.
* style the navigation bar as follows:
	- the navigation bar should be a horizontal bar, all of its list items should be displayed in a single row.
	- the first Unordered list contains(Product, Testimonials,and Pricing) should appear on the left side of the nav bar.
	- the second Unordered list contains(Team and Contact Us) should appear on the far right side of the navigation bar.
	- the navigaton bar should have a background color of #6e072d; and white font color;
	- the Unordered list should have no marigin and padding, however, individual list items should have vertical padding equal to their font size and horizontal padding equal to their font size multiplied by 1.5; their font size should be 18px.
	- hovering over list item should change it's background color to #b90e4d; and mouse cursor to a pointer.
	- border should be 2px solid white. however this border shouldn't appear on the right side of Pricing or on the left of Team and on the right of Contact us

===== Solution hit =====
* use flexbox layout
* use list-style -type  to remove the default bullet points on the items
* use pseudo classes li: not(:last-of-type) to place the borders ont he correct elements. 
