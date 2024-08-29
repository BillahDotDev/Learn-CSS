                                                                                                            
# Learn CSS (Cascading Style Sheets)              

# What is CSS?     
### CSS stands for Cascading Style Sheets.  It's a computer language specifically used to style and layout web pages.  Imagine CSS as the makeup for websites!  It allows you to change the fonts, colors, and layout to create a visually appealing website.


# Here are some familiar terms to get you comfortable before starting CSS:     

1. CSS (Cascading Style Sheets): A language used to describe the style of HTML documents.
2. Selector: The part of a CSS rule that specifies which HTML elements the styles apply to.
3. Property: An aspect of the HTML element you want to change, like color or font size.
4. Value: The setting you want to apply to the property, like "blue" or "16px".
5. Declaration: A combination of a property and a value.
6. Declaration Block: A group of declarations enclosed in curly braces.
7. Rule: A selector followed by a declaration block.
8. Inline Style: CSS written directly in the HTML element using the style attribute.
9. Internal Style Sheet: CSS written inside a <style> tag in the head of an HTML document.
10. External Style Sheet: CSS written in a separate .css file and linked to the HTML document.
11. Class Selector: A selector that targets elements with a specific class attribute, starting with a dot (.).
12. ID Selector: A selector that targets an element with a specific ID attribute, starting with a hash (#).
13. Element Selector: A selector that targets all instances of a specific HTML element.
14. Universal Selector: A selector that targets all elements, represented by an asterisk (*).
15. Attribute Selector: A selector that targets elements with a specific attribute.
16. Pseudo-class: A keyword added to selectors that specifies a special state of the selected elements, like :hover.
17. Pseudo-element: A keyword added to selectors that style a specific part of the selected elements, like ::before.
18. Inheritance: The mechanism by which some CSS properties applied to a parent element are inherited by its children.
19. Specificity: The rules that determine which CSS rule is applied when multiple rules match the same element.
20. Cascade: The order in which conflicting CSS rules are applied, based on specificity, origin, and importance.
21. Box Model: The model that describes the rectangular boxes generated for elements, including content, padding, border, and margin.
22. Content: The actual content of the HTML element.
23. Padding: The space between the content and the border of an element.
24. Border: The edge around the padding and content of an element.
25. Margin: The space outside the border of an element.
26. Width: The width of an element's content area.
27. Height: The height of an element's content area.
28. Max-width: The maximum width of an element's content area.
29. Max-height: The maximum height of an element's content area.
30. Min-width: The minimum width of an element's content area.
31. Min-height: The minimum height of an element's content area.
32. Display: Determines how an element is displayed on the page, like block, inline, or flex.
33. Inline: An element that does not start on a new line and only takes up as much width as necessary.
34. Block: An element that starts on a new line and takes up the full width available.
35. Inline-block: Like inline, but allows setting width and height.
36. Flexbox: A layout model for arranging elements in a flexible way.
37. Grid: A layout model for creating complex, responsive web layouts.
38. Float: A property that makes elements float to the left or right, allowing text to wrap around them.
39. Clear: A property used to control the behavior of floating elements.
40. Position: Specifies the positioning method for an element (static, relative, absolute, fixed, or sticky).
41. Static: The default positioning, where elements are positioned according to the normal flow of the document.
42. Relative: An element's position is adjusted relative to its normal position.
43. Absolute: An element is positioned relative to its nearest positioned ancestor or the initial containing block.
44. Fixed: An element is positioned relative to the viewport and stays in the same place when the page is scrolled.
45. Sticky: An element toggles between relative and fixed positioning, depending on the scroll position.
46. Z-index: Specifies the stack order of an element, with higher values appearing on top.
47. Overflow: Controls what happens when an element's content is too big to fit in its block (visible, hidden, scroll, auto).
48. Visibility: Controls the visibility of an element (visible, hidden, collapse).
49. Opacity: Controls the transparency level of an element.
50. Color: Sets the color of text in an element.
51. Background-color: Sets the background color of an element.
52. Background-image: Sets the background image of an element.
53. Background-repeat: Specifies if/how a background image is repeated.
54. Background-position: Sets the starting position of a background image.
55. Background-size: Specifies the size of the background image.
56. Font-family: Specifies a list of fonts for text in an element.
57. Font-size: Sets the size of the text.
58. Font-weight: Sets the weight (boldness) of the text.
59. Font-style: Specifies the style of the text (normal, italic, oblique).
60. Text-align: Sets the horizontal alignment of text.
61. Text-decoration: Specifies the decoration added to text (underline, overline, line-through, none).
62. Text-transform: Controls the capitalization of text (uppercase, lowercase, capitalize).
63. Line-height: Sets the amount of space between lines of text.
64. Letter-spacing: Controls the space between characters in text.
65. Word-spacing: Controls the space between words in text.
66. White-space: Controls how white space inside an element is handled.
67. Vertical-align: Sets the vertical alignment of an inline or table-cell element.
68. List-style: A shorthand property for setting list-style-type, list-style-position, and list-style-image.
69. List-style-type: Specifies the marker style for a list item.
70. List-style-position: Specifies the position of the list-item marker.
71. List-style-image: Specifies an image as the list-item marker.
72. Border-radius: Sets the rounded corners of an element's border.
73. Box-shadow: Adds shadow effects around an element's frame.
74. Transition: A shorthand property for defining the transition between two states of an element.
75. Transform: Applies a 2D or 3D transformation to an element.
76. Translate: Moves an element from its current position.
77. Rotate: Rotates an element.
78. Scale: Resizes an element.
79. Skew: Skews an element along the X and Y axes.
80. Animation: A shorthand property for animating elements.
81. Keyframes: Defines the intermediate steps in a CSS animation sequence.
82. Media Query: Applies styles based on the characteristics of the viewport or device.
83. Responsive Design: Designing web content to work on different devices and screen sizes.
84. Viewport: The user's visible area of a web page.
85. Rem Unit: A relative length unit equal to the font-size of the root element.
86. Em Unit: A relative length unit based on the font-size of the parent element.
87. Px Unit: A unit of length equal to one pixel of the display.
88. % Unit: A percentage value relative to another length property.
89. Vh Unit: A unit of length equal to 1% of the viewport height.
90. Vw Unit: A unit of length equal to 1% of the viewport width.
91. Calc() Function: Allows you to perform calculations to determine CSS property values.
92. Custom Properties (CSS Variables): Variables defined by the user for reusing values throughout a CSS document.
93. Import Rule: A rule to import an external stylesheet into another stylesheet.
94. Charset Rule: Specifies the character encoding used in the stylesheet.
95. Namespace Rule: Declares an XML namespace and associates it with a CSS prefix.
96. Supports Rule: Applies styles only if a browser supports a specific CSS feature.
97. Counter: Manages counters in CSS for ordered lists or custom numbering.
98. Counter-increment: Increments a counter value.
99. Counter-reset: Resets a counter value.
100. Content Property: Used with pseudo-elements to insert generated content.






  

