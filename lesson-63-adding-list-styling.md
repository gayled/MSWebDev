# Lesson 6.5 Adding List Styling

Lists can also be styled to set them off from the rest of the page

1. The bullets of a **&lt;ul&gt;**  can be squares, circles, none, or the default, disks. Set the **list-style-type** to another type.
2. Lists can be given backgrounds, borders, padding, and box shadows. Give your lists back-ground color, border, padding, and box shadow rules using separate selectors or a multiple selector for ul and ol.
3. The default for numbers and bullets is outside the list. Change this by adding a **list-style-position** property to inside.

Example:

**`ul {`**

**`list-style: circle;`**

**`width: 150px;`**

**`}`**

**`ol {`**

**`width: 350px;`**

**`}`**

**`ul, ol {`**

**`background-color: Maroon;`**

**`border: solid 5px DarkSlateGray;`**

**`-webkit-box-shadow: 5px 5px 5px 2px rgba(41,35,41,1);`**

**`-moz-box-shadow: 5px 5px 5px 2px rgba(41,35,41,1);`**

**`box-shadow: 5px 5px 5px 2px rgba(41,35,41,1);`**

**`padding: 10px;`**

**`list-style-position: inside;`**

**`}`**

