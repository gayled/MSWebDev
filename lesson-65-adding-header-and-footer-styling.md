# Lesson 6.7 Adding Header and Footer Styling

The header and footer are usually given the same styling in background color, font properties, etc.

1. Add a multiple selector rule for header and footer, giving both the same background-color and text alignment \(text-align\).
2. Adjust the margins to remove the padding that was added in the body margin rule by giving a negative value to each value. Example: **margin: -10px -50px -10px -100px**;
3. Adjust the header border-bottom separately, giving it a style and a width.
4. Adjust the footer-top separately, giving it a style and a width and extend its top margin to clear the element above it.

## Code Example

```text
header, footer {
	background-color: silver;
	text-align: center;
	margin: -20px; /*readjusted because body is not 100%*/
}

header {
	padding-bottom: 10px;
	border-bottom-style: groove;
	border-bottom-width: 5px;
}

footer {
	border-top-style: groove;
	border-top-width: 5px;
	margin-top: 10px; /*overrides margin rule to give more space above*/
}
```

This concludes the first unit of lessons using basic html and css to build a simple website of two single column web pages. When your website is completed,  select the arrow button on the top right of the preview pane to open your Repl.it-hosted website in a new tab. Share its URL with your friends and family.

