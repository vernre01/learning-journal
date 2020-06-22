-[Return to Home](/README.md)

# Learning Journal
*Blog Entry-* Lab 05

## Designing Webpages with CSS

### What is CSS?
**CSS**, short for Cascading Style Sheets, allows you to change the way your HTML code is presented to the viewer.  Best practice is to put all your CSS code in a separate file and link to it from your HTML code.  You will also want to check your CSS in multiple browsers as there can be slight differences between them.

#### CSS Selectors
The CSS selector tells you which element the rule applies to.  CSS selectors can be:

- **Universal-** Applies to everything.
- **Type-** Applies the rule to all instances of an element.
- **Class-** Applies the rule to an entire class attribute.
- **ID-** Applies the rule to a single id attribute.
- **Child-** Applies the rule to all *children* of another element.
- **Descendant-** Applies the rule to all *descendants* of another element.
- **Adjacent Sibling-** Applies the rule to only the *first sibling* of another element.
- **General Sibling-** Applies the rule to *all siblings* of another element.

#### CSS Declarations
Declarations are made up of properties and values. **Properties** indicate what you want to change about the selected element.  **Values** say what to change it to.

#### Okay...But Why 'Cascading'?
This refers to which rules the CSS impliments in your code.  If you have multiple rules applying to the same element, either the **last rule** will be applied or the selector that is the **most specific**. Some types of child elements also inherit the style rules of their parent element.

### Color in CSS
Color can be applied to the foreground and the background of elements.  Background colors show up as a color block behind the element.  Foreground color refers to the color of text.

You can use four different methods for specifying color:
1. RGB Values: (red, green, blue, transparency)
2. Hex Codes: #hexadecimal code (two letters for each red, green, and blue)
3. Color Names: 147 predefined names, such as darkslategray
4. HSL Values: (hue, saturation, lightness, transparency)

A variety of color pickers on the Internet can be used to pick colors for your design.  Be sure to check contrast between colors and combinations that work poorly for those with color-blindness before finalizing your color scheme.