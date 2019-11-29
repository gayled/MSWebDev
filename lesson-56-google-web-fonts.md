# Lesson 5.6: Google Web Fonts

Google provides a repository of web safe fonts that your web pages can link to in order to have more choice in fonts. All you need to do is add their stylesheet link to your pages and then use them for any of your projects.

1. Navigate to **fonts.google.com** and use the search feature to choose an appropriate font that you like.
2. Select the font that you want. The embed code needs to be copied and pasted into the &lt;head&gt; tag of each webpage **before** your stylesheet links. This is important because any outside stylesheet link appearing before your own stylesheet lmay override your own styles due to the "cascade" effect.
3. The font-family rule should be copied and pasted into the selector\(s\) you want to use it with.
4. If the Google font doesn’t display at all, try changing the https:// to // in the head tag.

Example HTML:

&lt;head&gt;

**`<link href="`**[`https://fonts.googleapis.com/css?family=Lato`](https://fonts.googleapis.com/css?family=Lato)**`" rel="stylesheet">`**

**`<link rel="stylesheet" href="styles.css">`**

&lt;/head&gt;

Example CSS:

**`h1`**```**``{\`\*\*

**`font-family: "Arial Black", Gadget, sans-serif;`**

**`}`**

