# Lesson 6.2 Adding Borders to Images Using CSS

Image width and height can also be styled with CSS. The difference is that the units must be specified with CSS, such as width: 50px; 

1. Images as well as other HTML elements can have **borders**. Border styles are solid, dotted, dashed, double, groove, ridge, inset, outset, and none. Use the **img selector** to give your images a border style.
2. Adjust the border size with the **border-width** property.
3. The border color can be changed with the **border-color** property.
4. The border properties of style, size, and color can be combined in a **border shorthand**. The order doesn’t matter.
5. Optional: You may want to remove the border from your logo. In order to do that, you need to add a **class** attribute to the html. For the logo img, add **class=”some\_name”.** Make sure to do it for the logos on each page.

Class selectors in a stylesheet are preceded by a period. The class selector for my example would be **.some\_name**. I can now add a rule border: none; to remove the border from my logo.

## HTML Example

```text
<a href="index.html"><img class="logo"  src="images/logo.png" width="60" alt="logo"/></a>
```

## CSS Example

```text
img {
  border-style: solid;
  border-width: 5px;
  border-color:DarkSlateGray;
}

/* image shorthand below
img {
   border: solid 5px DarkSlateGray;
}
*/

.logo {
  border: none;
}
```

