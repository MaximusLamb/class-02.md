# Lists

```html
<li></li>
```
* All lists are filled with these. And lists can be put in other lists which is called **Nested Lists**

### Ordered List

## 

```html
<ol></ol>
```
* This creates an ordered list.

### Unordered List

```html
<ul></ul>
```
* This creates an unordered list.

## Definition List

```html
<dl></dl>
```
* This creates a definition list which usually consists of a series of terms and definitions.

```html
<dl>
    <dt></dt>
</dl>
```
* This is used to contain the term being defined.

```html
<dl>
    <dd></dd>
</dt>
```
* This is used to contain the definition.


# Boxes

## Box Dimensions
* **width** and **height** are used to set the dimensions of a box.
## Limiting Width and Height
* **min-width**, **min-height** and **max-width**, **max-height** are used to set limited dimensions for a box.
## OverFlow
* The overflow property tells the browser what to do if the content contained within a box is larger than the box itself.  It can have two values.
* **hidden**: Simply hides any extra content that does not fit in the box.
* **scroll**: This property adds a scrollbar to the box so that users can scroll to see the missing content.

# Border, Margin and Padding
## Border
* Every box has a border (even if it is not visible or is specified to be 0px wide)
### border-width
* The **border-width** property is used to control the width of the border. You can use pixels or **thin, medium, thick**.
### border-style
1. **solid**: a single solid line
2. **dotted**: a series of square dots
3. **dashed**: a series of short lines
4. **double**: two solid lines
5. **groove**: appears to be carved into the page
6. **ridge**: appears to stick out from the page
7. **inset**: appears embedded into the page
8. **outset**: looks like it is coming out of the screen
9. **hidden/none**: no border is shown

### border-color
* You can specify the color of a border using either **RGB** values, **hex codes** or **CSS color names**
### border-radius
* This is the ability to create rounded corners on any box.

## Margin
* Margins sit outside the edge of the border.  You can set the width of a margin to create a gap between the borders of two adjacent boxes.
## Padding
* Padding is the space between the border of a box and any content contained within it.  Adding padding can increase the readabliity of its contents.

# Display
* The **display** property allows you to turn an inline element into a block-level element or vice versa, and also be used to hide an element from the page.

## inline
* This causes a block-level element to act like an inline element.
## block
* This causes an inline element to act like a block-level element.
## inline-block
* This causes a block-level element to flow like an inline element, while retaining other features of a block-level element.
## none
* This hides an element from the page.  In this case, the element acts as though it is not on the page at all.
# Visibility
## hidden
* This hides the element.
## visibile
* This shows the element.