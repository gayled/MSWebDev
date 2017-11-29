## Adding Header and Footer Styling

The header and footer are usually given the same styling in background color, font properties, etc.

1. Add a multiple selector rule for header and footer, giving both the same background-color and text alignment \(text-align\).
2. Adjust the margins to remove the padding that was added in the body margin rule by giving a negative value to each value. Example: **margin: -10px -50px -10px -100px**;

3. Adjust the header border-bottom separately, giving it a style and a width.

4. Adjust the footer-top separately, giving it a style and a width and extend its top margin to clear the element above it.

Example:

`header, footer {`

`background-color: Silver;`

`margin: -10px -50px -10px -100px;`

`text-align: center;`

`}`

`header {`

`border-bottom-style: groove;`

`border-bottom-width: 5px;`

`}`

`footer {`

`border-top-style: groove;`

`border-top-width: 5px;`

`margin: 10px 0 0 0;`

`}`

This concludes the first series of lessons using basic html and css to build a simple website of two one-column web pages.

