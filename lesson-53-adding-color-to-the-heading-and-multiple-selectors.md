## **Adding Color to the Heading Tags and Multiple Selectors**

You will see the cascade in action when you add different colors to your heading tags. The more specific heading selectors override the color set by the html selector

1. Change the color of your h1 heading by adding a separate rule for it.

2. Change the color of your h2 and h3 heading to the same color. You can style multiple selectors the same way by adding a comma between them.

Example:

**html {**

```
background-color: Gainsboro;

color: slateGray;
```

**}**

**h1 {**

**color: Maroon;**

**}**

**h2, h3 {**

**color: MidnightBlue;**

**}**

Notice how each heading selector overrides the color assigned by the html selector.

