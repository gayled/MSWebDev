# Lesson 5.2 Adding Color to the Background and Font and CSS Comments

CSS defines 140 color names that can be found along with their hex values \(which we will discuss later\) at [W3schools](http://www.w3schools.com/colors/colors_names.asp). Choose colors for your background and font that will enhance the design/aesthetics of your site.

1. A CSS rule is applied to a **selector** \(the HTML element that will be styled\). Since this rule is to be applied to the entire page, we will use html as the selector.
2. The selector is followed by a space and open and closed curly braces.
3. The properties to be styled and their values are enclosed within the curly braces and the property value is separated from the property name by a colon and a space.
4. Each rule is terminated with a semicolon.
5. Styling the html selector as below changes every page's background to red and font color to blue.
6. Unlike HTML comments, CSS comments are enclosed in /\* .... \*/ syntax.

## Code Example

```text
html {
/* styles the background and font of every page */
  background-color: red;
  color: blue;
}
```



