# Lesson 4.5 Meta Tags and Comments

1. **Meta** tags are non-displaying HTML elements that provide specific information \(metadata\) about your website. They are always located in the head section of your website. This [link](http://www.w3schools.com/tags/tag_meta.asp) explains some of the more common ones. On each page we will use these three:

   a. **&lt;meta charset=”UTF-8”&gt;** defines the preferred Unicode encoding for web pages.

   b. **&lt;meta name=”description” content=”This part will show up in search engine results!”&gt;** What you write here will show up in search engine results for your website!

   c. **&lt;meta name="viewport" content="width=device-width, initial-scale=1"&gt;** This tag optimizes

   your site to display correctly with different device screen sizes.

   1. It is good practice to add comments to your code as your documents become longer and more complex to help anyone \(including yourself\) who needs to look at your code to understand what it is doing. To practice adding a comment we will add a comment to the head section to remind ourselves that we completed the html for this website on this day's date.

Example: **&lt;!- - HTML completed on "add today's date" - - &gt;**

Notice the exclamation point in the opening tag as well as the two hyphens. Comments are closed with two hyphens followed by an angle bracket. There is no forward slash. Be careful with the syntax of comments. If the closing tag isn't written properly, none of your code past the comment will display!.

## Code Example

```text
	<head>
		<title>Snow Leopard Challenges</title>
		<meta name="description" content="This page describes where the snow leopard is endangered and the causes of its endangerment"/>

		<link href="https://fonts.googleapis.com/css?family=Days+One&display=swap" rel="stylesheet">
		<link rel="stylesheet" href="style.css" />
		
		<meta charset="UTF-8"/>
		<meta name="viewport" content="width=device-width, initial-scale=1"/>
	</head>
```

