# Questions:

1. What are the main differences between external, internal, and inline CSS?
2. What is the syntax for class and ID selectors?
3. How would you apply a single rule to two different selectors?
4. Given an element that has an id of title and a class of primary, how would you use both
   attributes for a single rule?
5. What does the descendant combinator do?
6. Between a rule that uses one class selector and a rule that uses three type selectors,
   which rule has the higher specificity?
7. From inside to outside, what is the order of box-model properties?
8. What does the box-sizing CSS property do?
9. What is the difference between the standard and alternative box model?
10. Would you use margin or padding to create more space between 2 elements?
11. Would you use margin or padding to create more space between the contents of an
    element and its border?
12. Would you use margin or padding if you wanted two elements to overlap each other?
13. What is the difference between a block element and an inline element?
14. What is the difference between an inline element and an inline-block element?
15. Is an h1 block or inline?
16. Is button block or inline?
17. Is div block or inline?
18. Is span block or inline?
19. What’s the difference between a flex container and a flex item?
20. How do you create a flex item?
21. What are the 3 values defined in the shorthand flex property?
22. How do you make flex items arrange themselves vertically instead of horizontally?
23. What is the difference between justify-content and align-items?
24. How do you use flexbox to completely center a div inside a flex container?
25. What’s the difference between justify-content: space-between and justify-content:
    space-around?

# Answers:

1. External CSS is in a separate file, internal CSS is in the head section of an HTML document, and inline CSS is applied directly to an HTML element.
2. Class selectors use a dot (.) before the class name, and ID selectors use a hash (#) before the ID name.
3. Separate the selectors with a comma.
4. Use the ID selector preceded by a hash (#) and the class selector preceded by a dot (.): #title.primary { /* CSS rule */ }
5. The descendant combinator selects an element that is a descendant of another element.
6. The rule that uses three type selectors has a higher specificity.
7. Content, padding, border, margin.
8. The box-sizing property specifies how the total width and height of an element is calculated.
9. In the standard box model, the width and height of an element does not include padding or border. In the alternative box model, the width and height of an element includes padding and border.
10. Margin.
11. Padding.
12. Margin (with a negative value).
13. Block elements start on a new line and take up the full width available, while inline elements stay on the same line and only take up as much width as necessary.
14. Inline elements do not have a set width and height, while inline-block elements have a set width and height but still flow like inline elements.
15. Block.
16. Inline by default, but can be changed to block or inline-block with CSS.
17. Block.
18. Inline.
19. A flex container is the parent element that contains flex items. Flex items are the child elements inside the flex container that are laid out using flexbox.
20. Add the display property with a value of "flex" to the element.
21. Flex-grow, flex-shrink, flex-basis.
22. Use the flex-direction property with a value of "column".
23. Justify-content aligns items along the main axis, while align-items aligns items along the cross axis.
24. Use justify-content and align-items properties with a value of "center".
25. justify-content: space-between distributes items evenly with space between them, while justify-content: space-around distributes items evenly with space around them.