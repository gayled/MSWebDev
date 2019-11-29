# Lesson 5.8 Styling Anchor Elements Using Pseudo-Classes

**Pseudo-classes** are used when elements, such as anchor elements, have different states that must be styled differently. For example, you can style links differently depending upon whether they have not been visited, when the user hovers over them, when they are clicked, and when they have been visited. The selector syntax is to insert a colon between the element and its state. Anchor pseudo-classes must appear in this order: **a:link**, **a:visited**, **a:hover** and **a:active**.

1. Remove the underline from the anchors by setting the **text-decoration** property to none.
2. Style the four states of the anchor elements by changing the color, weight, and or size of the font.

## Example Code

```text
a {
 text-decoration: none;
 font: bold 20px "Arial Black", Gadget, sans-serif;
}
a:link {
 color: DarkSlateGray;
}
a:visited {
 color: MidnightBlue;
}
a:hover {
 color: Maroon;
 font-size: 22px;
}
a:active {
 color: Red;
 font-size: 22px;
}
```

**`a {`**

**`text-decoration: none;`**

**`font: bold 20px "Arial Black", Gadget, sans-serif;`**

**`}`**

**`a:link {`**

**`color: DarkSlateGray;`**

**`}`**

**`a:visited {`**

**`color: MidnightBlue;`**

**`}`**

**`a:hover {`**

**`color: Maroon;`**

**`font-size: 22px;`**

**`}`**

**`a:active {`**

**`color: Red;`**

**`font-size: 22px;`**

**`}`**

