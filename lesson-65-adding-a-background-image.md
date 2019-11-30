# Lesson 6.6 Adding a Background Image

Adding a background image can set off the content of your website . Include it in your html rule and make the body rule a solid color while decreasing the screen width of the body element \(75-85% for the width of the body is a reasonable amount for a one column web page\).

1. Move the background-color to your body rule.
   1. Search for a background image that fits the overall design of your site and save it to your images folder, shortening its name if necessary.
   2. Add this image to your html rule using the format: **background-image: url\(image/your\_image.xxx\); Note:**  If your background image repeats your can add the rule background-repeat: no-repeat.
   3. Add **margin: 0 auto** to your html rule to center the image.
      1. Padding adds space between the margin \(or border if you have one\) and your content. Add a padding rule to your body and use it to adjust the left and right appearance of your column.

## Code Example

```text
html {
	background-image: url(images/background.png);
	color: darkslategray;
	font-family: Verdana, Geneva, sans-serif;
	font-size: 18px;
}

body {
	background-color: Gainsboro;
	width: 75%;
	margin: 0 auto;
	padding: 10px 20px;
}
```

