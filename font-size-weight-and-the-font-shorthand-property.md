## Font Size, Font Weight, and the Font Shorthand Property

**Font size** can be specified many ways, both in absolute values such as pixels and relative values such as ems. We will use pixels to specify the font size for this website. **Font weight** describes the thickness of the font. Most commonly, it is specified as normal or bold. The default for elements such as paragraphs is normal, heading defaults are bold. Finally, font properties can be specified using a **font shorthand** which declares all the properties in one rule. The order matters and, for the common properties are: **font: font-weight font-size font-family**. There are no commas.

1. Add font-sizes to all headings.

2. Specify the h1 rule in font shorthand. The font shorthand needs at least font-size and font-family to work.

Example:

**`h1 {`**

```
font-family: normal 25px "Lucida Sans Unicode", "Lucida Grande", sans-serif;
```

**`}`**

**`h2, h3 {`**

**`font-family: 15 px  "Comic Sans MS", cursive,  sans-serif;`**

**`}`**

