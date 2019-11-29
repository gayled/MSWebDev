## Linking Web Pages Within Your Site Using the Nav and Anchor Tags

You will now add a second page to your site by selecting the File icon in the File pane and naming it. Before you add any content to this page, think about which non-displaying and structural elements you need to include in this new page and add them now.

1. Give your page a new title, a new main heading, and keep your logo.

2. On your index.html page, add opening and closing** &lt;nav&gt;** tags after your logo.

3. Within these nav tags, add the following markup:

**&lt;a href=”\#”&gt;Home\(or what you want to name your home page\)&lt;/a&gt; \|**

**&lt;a href=”name\_of\_second\_page.html”&gt;Name of your second page&lt;/a&gt;**

For now, we will separate the page links by using the \| \(pipe\) character. Notice how the link to the Home page is a hash tag, which is a link that goes nowhere, therefore staying on the current page.

1. Copy the nav element code to your second page in the same location, changing the Home link to index.html and the second link to \#. Check that your links work correctly.

### Code Example

`<!DOCTYPE html>`

`<html>`

`	<head>`

`		<title>Snow Leopard Home</title>`

`		<link rel="stylesheet" href="style.css" />`

`	</head>`

`	<body>`

`		<a href="#"><img  class="logo" src="images/logo.png" width="60" alt="logo"/></a>`

`		<nav>`

`			<a href="#">Snow Leopard Home  </a>|`

`			<a href="challenges.html"> Snow Leopard Challenges</a>`

`		</nav>`

`		<h1>Snow Leopards</h1>`

...

`      </body>`

`</html>`

