## Lesson 1.3: Non-Displaying HTML and the Document Object Model

Add **&lt;!DOCTYPE html&gt;** to the first line of your webpage.

**Note: **This tag and the ones that follow don’t display content in your web page, but should not be left out. The doctype allows the browser rendering engine to know that your web page is using the most current version of html, HTML5. If this doctype isn’t included, the browser may not render \(display\) parts of your website correctly.

1. Add **title** tags with the title of your page between them on the second line. This is the title that will display on search engine results as a clickable link.

2. Add a new file, **styles.css**, to your website.

3. Link this stylesheet file to your web pages by adding **&lt;link rel="stylesheet" href="styles.css"&gt;** on the line following your title.

4. Test your link by typing this code into the styles.css file:

**body {**

**background-color: \#DDD;**

**}**

You should see your web page’s background change color if you typed the link correctly.

**Note: **This construct, **attribute=”value”** is very common in opening tags. It modifies a certain attribute \(or feature\) of the tag by assigning a value to that feature. These are called **attribute-value** pairs. The **rel=”stylesheet”** attribute-value pair states that the **rel**ationship of this link is to a stylesheet. A stylesheet is a file of rules that determines the presentationof a web page: its colors, fonts, etc. The second attribute-value pair, **href=”styles.css”**, tells the browser the location of that stylesheet file in your filesystem. It is a **link** or **h**ypertext r**ef**erence.

1. Enclose all the code you have written so far except &lt;!DOCTYPE html&gt; in **&lt;html&gt; &lt;/html&gt; **tags.

2. After the opening html tag, add **&lt;head&gt; &lt;/head&gt; **tags to enclose your title and stylesheet link.

3. All the part of your website that displays between the closing head and closing html tags should be enclosed in **&lt;body&gt; &lt;/body&gt;** tags.

**Note: **The browser represents your webpage, or document, as an object that resembles an inverted tree of html elements. The main **html **branch is subdivided into the non-displaying **head** branch and the displaying **body** branch. All other html elements are semantically related to each other in this tree. This is called the Document Object Model, or **DOM**. This will be important to understand when you start to add JavaScript to your pages.

![](/assets/DOM.png)

### Document Object Model



