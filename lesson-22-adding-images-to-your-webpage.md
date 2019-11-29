## Lesson 2.2 **Adding Images to Your Web Page**

1. Add your first image between the 1st paragraph and the subheading for the second paragraph.

2. The tag for adding an image is **&lt;img src=”images/yourimagename.ext”/&gt; **\(img is a self-closing tag\).

**Note: **The difference between an **href **and a **src** attribute is that href just refers to another resource that your web page links to and a src actually embeds the resource in your web page.

1. When you preview the web page you will probably find that the image is too big or too small for the page. You can adjust the size by adding the attribute-value pair **width=”experiment\_with\_different\_sizes**”. The value should be a number with no units, such as width=”150”. Be sure to add a space between the src attribute value pair and the width attribute value pair.

2. Above your image, add an **h3** caption.

3. Repeat the first step with your logo image. Add it before the h1 heading. Logos are generally small. Don’t add a caption.

### Code Example

`<!DOCTYPE html>`

`<html>`

`<head>`

`<title>Snow Leopard Home</title`

`<link href="https://fonts.googleapis.com/css?family=Days+One&display=swap" rel="stylesheet">`

`<link rel="stylesheet" href="style.css" />`

`</head>`

`<body>`

`<img  src="images/logo.png" width="60"/>`

`<h1>Snow Leopards</h1>`

`<h2>Introducing the Snow Leopard</h2>`

`<p>Have you ever seen a snow leopard? They are some of the most beautiful animals on Earth. They have a whitish-gray fur coat spotted with large black spots that allows them to blend in with the rocky mountains where they live. Snow leopards have also adapted to live in some of the most severe climates on Earth? You would think that they would be tough survivors but you would be wrong.</p>`

`<img src="images/face.jpeg" width="400"/>`

`<h3>A Fierce Stare</h3>`

...

`</body>`

`</html>`

...

