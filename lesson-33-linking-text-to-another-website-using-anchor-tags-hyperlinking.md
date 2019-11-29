# Lesson 3.3 Linking Text to Another Website Using Anchor Tags \(Hyperlinking\)

The anchor tag was the ground-breaking innovation that caused the Web to grow to what it is today by allowing users to instantly jump from document to document and server to server. You will create a link from some text on your page to a Wikipedia article on your topic.

1. Choose a word or phrase in one of your paragraphs for which you think your user might want more information.
2. Find the page on the Simple English Wikipedia website that pertains to this topic and copy its URL \(uniform resource locater\) in the browser address bar.
3. Enclose the text you chose within opening **&lt;a&gt;** and closing **&lt;/a&gt;** tags. In the opening &lt;a&gt; tag, insert the attribute-value pair **href=”paste\_full\_URL”**. Test that your link works correctly.
4. The default behavior is for the link to open in the same tab, replacing your webpage and forcing your user to use the browser back button to return to your page. You can force the link to open in a new tab by inserting another attribute-value pair, **target=”\_blank”**, in the opening anchor tag. Be sure that there are no spaces in your attribute-value pairs, but a space between every attribute-value pair.

## Code Example

```text
<p>Have you ever seen a <a target="_blank" href="https://simple.wikipedia.org/wiki/Snow_leopard">snow leopard</a>? 
```

