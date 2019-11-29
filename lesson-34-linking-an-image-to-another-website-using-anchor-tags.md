# Lesson 3.4: Linking an Image to Another Website Using Anchor Tags

You can turn an image into a hyperlink by nesting the src tag for your image within anchor tags.

1. Find another website that gives your user further information about the topic of your webpage. Be careful with your links; a home page of a site that looks as if it will still be around in the future would be the safest choice. Copy its URL.
2. Enclose the &lt;img&gt; tag within opening and closing &lt;a&gt; tags. Example: **&lt;a&gt;&lt;img src=”path\_to\_image”&gt;&lt;/a&gt;** To your opening &lt;a&gt; tag add the **href=”path\_to\_website”** attribute-value pair to generate the link. Add **target=”\_blank”** to open the website in a new tab. Test your link.

## Code Example

`<a target="_blank" href="https://defenders.org/wildlife"><img src="images/face.jpeg" width="400" alt="Snow leopard face" title="Snow Leopard Face"/></a>`

