# Lesson 6.3 Box and Text Shadows

Box shadows give a three-dimensional effect to HTML elements. The first item in the property value is the horizontal length \(positive numbers move it right, negative numbers move it down\); the second item is the vertical length \(positive is down, negative is up\); the third item is the blur radius \(smaller numbers are sharper\); the last number is the spread radius \(positive numbers increase the shadow, negative numbers decrease it\).

**Note:** Browser prefixes are sometimes added before these properties with older browsers. Consult [https://caniuse.com/ ](https://caniuse.com/)which compiles information on how many browsers support CSS properties. This site reports that over 90% of browsers currently support box and text shadows without browser prefixes.

1. Because this is a complex property, the website [cssmatic.com](http://www.cssmatic.com/box-shadow) can be used to generate values for  this property, including browser-prefixes.
2. When you are satisfied with the appearance of the box-shadow including the shadow color, copy the code into your img selector.
3. Set the box-shadow property of the logo class to none.

Text-shadows are like box-shadows but do not have the spread property. This

[site](http://www.cssportal.com/css3-text-shadow-generator/) will generate values for this property for you.



## Code Example

box-shadow with browser prefixes:

```text
ul, ol {
  -webkit-box-shadow: 5px 5px 5px 2px maroon;
  -moz-box-shadow: 5px 5px 5px 2px maroon;
  box-shadow: 5px 5px 5px 2px maroon;
}
```

