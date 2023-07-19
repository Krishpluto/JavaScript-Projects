# JavaScript-Projects
This repository has JavaScript projects which i had practiced
-----------------------------------------------------------------------------------------------------------------------
Project 1: Digital Clock:
NOTES: 
-> Why margin and padding is 0 in css sometimes: 
ans: In CSS, the default margin and padding for the body element are often set to 0 by user agent stylesheets (default styles applied by web browsers). This is done to provide a consistent starting point for web developers and designers when creating their own styles.

Setting margin: 0; and padding: 0; on the body element helps ensure that there are no default spacing or gaps around the content of the web page. By removing any initial margins and padding, you have more control over the layout and appearance of your webpage.

When you explicitly set margin: 0; and padding: 0; for the body element in your CSS, you create a clean slate from which to build your page layout. Then, you can add margins and padding to specific elements as needed to achieve the desired spacing and positioning.
-> In my code, the width and height of the container element have been set using the vw (viewport width) and vh (viewport height) units. These units are used to size elements relative to the size of the viewport, which is the visible area of the web page.

Here's a brief explanation of the available units:

vw (Viewport Width):

1vw is equal to 1% of the viewport width.
It is used to size elements based on a percentage of the viewport width.
For example, if you set an element's width to 50vw, it will be half the width of the viewport.
Useful for creating responsive designs and ensuring elements scale proportionally with the viewport size.
vh (Viewport Height):

1vh is equal to 1% of the viewport height.
It is used to size elements based on a percentage of the viewport height.
For example, if you set an element's height to 50vh, it will be half the height of the viewport.
Useful for creating elements that occupy a specific percentage of the viewport's height, regardless of the screen size.
% (Percentage):

1% is equal to 1% of the parent element's size (width or height).
It is used to size elements based on a percentage of their parent element's size.
For example, if you set an element's width to 50%, it will be half the width of its parent element.
Useful for creating responsive layouts within a parent container.
px (Pixels):

Pixels are fixed units used to size elements in absolute terms.
The size of the element will be fixed regardless of the viewport size or parent element's size.
For example, if you set an element's width to 100px, it will be exactly 100 pixels wide.
Useful for creating elements with fixed dimensions that should not change with screen size.
em and rem:

em and rem are relative units that depend on the font size of the element or the root (html) element, respectively.
1em is equal to the font size of the element, while 1rem is equal to the font size of the root (html) element.
They are used to create responsive designs that scale based on the font size.
em is relative to the parent element's font size, while rem is relative to the root (html) element's font size. 

-> Flexbox is a layout model in CSS that provides a flexible way to arrange and align elements within a container. It allows you to create responsive and dynamic layouts without relying on float or positioning properties. Flexbox makes it easier to create complex layouts with less code and is well-suited for creating responsive designs.

To use Flexbox, you set the display property of the container element to flex. This turns the container into a flex container, and its direct children become flex items. Flex items can then be arranged along the main axis and cross axis of the container using various Flexbox attributes. Here are the key Flexbox attributes:

display: flex;:

This is the fundamental attribute to enable Flexbox on the container element.
It turns the container into a flex container, and its children become flex items.
flex-direction:

Specifies the direction of the main axis along which flex items are placed.
Values: row (default) - left to right, row-reverse - right to left, column - top to bottom, column-reverse - bottom to top.
flex-wrap:

Specifies whether flex items should wrap to multiple lines or not if they overflow the container's width.
Values: nowrap (default) - all flex items are on one line, wrap - flex items wrap onto multiple lines if needed, wrap-reverse - flex items wrap onto multiple lines in reverse order.
justify-content:

Aligns flex items along the main axis.
Values: flex-start (default) - items are packed to the start of the main axis, flex-end - items are packed to the end of the main axis, center - items are centered along the main axis, space-between - items are evenly distributed with the first item at the start and the last item at the end, space-around - items are evenly distributed with equal space around them.
align-items:

Aligns flex items along the cross axis (perpendicular to the main axis).
Values: stretch (default) - items are stretched to fill the container's cross-axis, flex-start - items are packed to the start of the cross axis, flex-end - items are packed to the end of the cross axis, center - items are centered along the cross axis, baseline - items are aligned based on their baselines.
align-content:

Aligns the lines of flex items along the cross axis when there are multiple lines of flex items.
Values: flex-start - lines are packed to the start of the container, flex-end - lines are packed to the end of the container, center - lines are centered within the container, space-between - lines are evenly distributed with the first line at the start and the last line at the end, space-around - lines are evenly distributed with equal space around them, stretch - lines are stretched to fill the container's cross-axis.
flex:

Specifies how flex items grow and shrink to fill the available space.
It is a shorthand for flex-grow, flex-shrink, and flex-basis.
Example: flex: 1 1 auto; - the item will grow and shrink equally, and its initial size is determined by its content.
These attributes can be applied to the flex container or individual flex items to achieve the desired layout. Flexbox provides a powerful and intuitive way to create responsive designs and organize elements within a container. It is widely supported across modern browsers and is often used in combination with media queries for responsive web design.
-------------------------------------------------------------------------------------------------------------------------------------------------------------
