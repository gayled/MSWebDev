# Lesson 5.6 Google Web Fonts

Google provides a repository of web safe fonts that your web pages can link to in order to have more choice in fonts. All you need to do is add their stylesheet link to your pages and then use them for any of your projects.

1. Navigate to **fonts.google.com** and use the search feature to choose a category of font that you're interested in..
2. Select the font that you want. The embed code needs to be copied and pasted into the &lt;head&gt; tag of each webpage **before** your stylesheet links. This is important because any outside stylesheet link appearing before your own stylesheet may override your own styles due to the "cascade" effect.
3. The font-family rule should be copied and pasted into the selector\(s\) you want to use it with in your style.css file.

## Example HTML

```text
<head>
  <link href="
https://fonts.googleapis.com/css?family=Lato" rel="stylesheet">
  <link rel="stylesheet" href="styles.css"/>
</head>
```

Make sure to list all imported stylesheets, such as Google Fonts, before your style.css link.

## Example CSS:

```text
h1 {
 font-family: "Arial Black", Gadget, sans-serif;
}
```

Make sure that you have referenced the Google font in style.css and in every web page where you want to use it.

