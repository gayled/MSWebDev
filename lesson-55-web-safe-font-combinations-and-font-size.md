## **Web Safe Font Combinations and Font Size**

The font-family property should have several font names in its value as a fail-safe mechanism in case an older browser doesn’t support the first font named, it tries the next; the ending font should be a generic font. Font sizes can be specified in several ways: cm\(centimeters\) and in\(inches\) \(both are rarely used\) and more commonly in px\(pixels\)and em \(a font size that is relative to the screen size it is viewed upon\). We will use pixels.

1. Go to this w3schools [link](http://www.w3schools.com/cssref/css_websafe_fonts.asp) and replace all your fonts with the web-safe font combinations.

Example:

**html {**

```
font-family: "Lucida Sans Unicode", "Lucida Grande", sans-serif;
```

**}**

**h1 {**

```text
 font-family:  "Lucida Sans Unicode", "Lucida Grande", sans-serif;
```

**}**

**h2, h3 {**

**font-family: "Comic Sans MS", cursive, sans-serif;**

**}**

Notice that a comma is placed between two selectors that are styled the same way.

