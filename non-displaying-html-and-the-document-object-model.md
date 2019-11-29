# Lesson 1.3: Non-Displaying HTML and the Document Object Model

The **&lt;!DOCTYPE html&gt;** tag should be the first line of your webpage.

**Note:** This tag and the ones that follow don’t display content in your web page, but should not be left out. The doctype allows the browser rendering engine to know that your web page is using the most current version of html, HTML5. If this doctype isn’t included, some browsers may not render \(display\) parts of your website correctly.

1. Add **title** tags with the title of your page between them on the second line. This is the title that will display on search engine results as a clickable link.
2. Link the stylesheet file, style.css, to your web page by adding &lt;link rel="stylesheet" href="style.css"/&gt; on the line following your title. The &lt;link/&gt; tag is a self-closing tag denoted by the &lt;.../&gt; syntax

   Test your link by typing this code into the style.css file:

   `body {`

    `background-color: #DDD`

   `}`

   You should see your web page’s background change color if you typed the link correctly.

**Note:** The construct, **attribute=”value”** is very common in opening tags. It modifies a certain attribute \(or feature\) of the tag by assigning a value to that feature. These are called **attribute-value** pairs. The **rel=”stylesheet”** attribute-value pair states that the **rel**ationship of this link is to a stylesheet. A stylesheet is a file of rules that determine the presentation of a web page: its colors, fonts, etc. The second attribute-value pair, **href=”style.css”**, tells the browser the location of that stylesheet file in your filesystem. It is a **link** or **h**ypertext r**ef**erence.

1. Enclose all the code you have written so far except &lt;!DOCTYPE html&gt; in **&lt;html&gt; &lt;/html&gt;** tags.
2. After the opening html tag, add **&lt;head&gt; &lt;/head&gt;** tags to enclose your title and stylesheet link.
3. All of your website that displays between the closing head and closing html tags should be enclosed in **&lt;body&gt; &lt;/body&gt;** tags.

**Note:** The browser represents your webpage, or document, as an object that resembles an inverted tree of html elements. The main **html** branch is subdivided into the non-displaying **head** branch and the displaying **body** branch. All other html elements are semantically related to each other in this tree. This is called the Document Object Model, or **DOM**. This will be important to understand when you start to add JavaScript to your pages.

## Document Object Model

![](.gitbook/assets/dom.png)

## Code Example

```text

<!DOCTYPE html>
<html>

	<head>
		<title>Snow Leopard Home</title>
		<link rel="stylesheet" href="style.css" />
	</head>

	<body>
		<h1>Snow Leopards</h1>

		<h2>Introducing the Snow Leopard</h2>

		<p>Have you ever seen a snow leopard? They are some of the most 
		beautiful animals on Earth. They have a whitish-gray fur coat 
		spotted with large black spots that allows them to blend in with 
		the rocky mountains where they live. Snow leopards have also 
		adapted to live in some of the most severe climates on Earth? 
		You would think that they would be tough survivors but you would 
		be wrong.</p>

		<h2>How the Snow Leopard Adapts to its Environment</h2>

		<p>For thousands of years, these large cats have been the kings
	  of the mountains of central Asia. They can jump six times the  
	  length of their body and can use their large tails for balance. 
	  They can also wrap their tails around their body for an
		extra fur coat when it is extremely cold. So why are they 
		endangered?</p>
		
	</body>
</html>
```

