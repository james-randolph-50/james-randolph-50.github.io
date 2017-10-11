---
layout: post
title:      "Page Layout Cheat Sheet "
date:       2017-10-11 22:04:28 +0000
permalink:  page_layout_cheat_sheet
---


Page Layout Cheat Sheet
Box Model

Box Model is a term in web design that describes how all web elements - text, pictures, graphics - fall into a box shape as they all have height, width, and padding parameters.
Layout Types
Fixed (px)

Define pixel (px) width, height, margins, etc. to set a fixed distance for all easureable web elements.

	Pros: Rigid structure, regardless of viewing port.

	Cons: Small screens (phones) may have to scroll horizontally - generally considered bad user interface (UI).
Elastic (em)

Columns are proportionately sized to text.

Pros: Responsive web design, scales up and down to keep everything in proportion.

Cons: Due to the variety of devices, individual users may get different layouts per device
Fluid (%)

Elements are assigned to take up a certain % of the screen.

	Pros: Makes use of entire screen. Eliminates horizontal scroll bars in smaller screen resolutions.

	Cons: Less control over design - type and media layout
Using min/max

Sets starting and stopping point for elements

	Pros: Control over design - fixed points but still a little flexible

	Cons: Screen resolutions are varied, needs plenty of testing

Overflow
Hidden (overflow: hidden;)
Text that has a height greater than the height of its element will not appear.

Scroll (overflow: scroll;)
Adds scroll bar functionality to element..

Visible (overflow: visible;)
Text pops out of element - required fixed height on element.
Fluid Height

Height of divs are, by default, equal to the height of the content. To change, set height in body and height in CSS.

Element Display

Display: inline;

Appears side by side, does not accept width or top and bottom margins

Display: block;

Displays one above the other, takes up the entire line. Can set top and bottom margins.

Display: inline-block;

Displays side by side, allows top & bottom margins, along with width, to be specified.

Float

Floating allows for content to be positioned to the left or right of the window. It helps create column structure.

Warning: Content below Floats will try to ‘pull up’ to floats. Set clear: both; to prevent that. (target the html element you want to clear, not the float)

Collapsed Parent



Centering

Centering elements on the webpage.

Margin: 0px auto;


CSS Positioning Techniques

Relative Positioning

.box {
	Position: relative;
	Top: 25px;
	Left: 200px
}

Pushes from top and left (moves down and over)

Absolute Positioning

.box {
	Positions: absolute;
	Top: 0;
	Right: 0;
}

Refers to relationship in browser window or relatively positioned parent class.

Fixed Positioning
Element will stay in place as browser is scrolled through.

