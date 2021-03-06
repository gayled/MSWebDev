# Lesson 6.3 Adding Margins to HTML Elements

Elements such as headings and paragraphs are **block level** elements. That means that they can be thought of as existing in a rectangular block on the web page. Because of this, the margins of this block can be adjusted to add or subtract space around these elements.

1. Remove some of the space between the h1 heading and the following h2 heading by setting the **margin-bottom** of the h1 to 0 and the **margin- top** of the h2 to 0;
2. There is a **margin shorthand**. The margins are set in the following order: **top, right, bottom, left**. Experiment with setting different amounts of margin to your img selector.
3. You can center your content in the browser by creating a body selector, adjusting its width and setting the body margins to 0 auto. \(When there are only two values, the first sets the top and bottom margins and the second sets the left and right margins.One value sets all margins to the same value.\)

## Code Example:

```text
body {
  margin: 0 auto;
}
img {
  margin-top: 15px;
  margin-right: 50px;
  margin-bottom: 25px;
  margin-left: 50px;
}
/*This is the same rule as above
img {
  margin: 15px 50px 25px 50px;
}
*/ 
  
```



