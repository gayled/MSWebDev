# Lesson 4.4 Adding a Header,  Main Section, and Footer to the Body of Your Website

1. Most websites are organized so that their logo and main site navigation are located at the top of each web page and use this same content and design on each page of the site. This is called the **header** area. Enclose your logo and site navigation \(**&lt;nav&gt;** and **&lt;/nav&gt;**\) within **&lt;header&gt; &lt;/header&gt;** tags.
2. Most websites also have site-specific information \(Conditions of Use, Privacy Notice, copyright, etc\) with the same content and design located at the bottom of each page. This is called the **footer** area. Add footer tags **&lt;footer&gt; &lt;/footer&gt;** and between them add **Created by First Name Last Initial**. Do not put your full name or those of your family and friends or any other information such as addresses or telephone numbers on any of your websites.
3. HTML **entities** are special characters such as copyright and trademark symbols that need special markup to display properly in websites. A collection of these characters and their codes can be found here: [https://dev.w3.org/html5/html-author/charref](https://dev.w3.org/html5/html-author/charref). Add a copyright symbol **©** between Created by and your First Name Last Initial.
4. The region of the web page body between the header and footer in this simple website can be divided into a main section with **&lt;main&gt; &lt;/main&gt;** tags.  Add header, footer, and main sections to both of your web pages.

## Code Example

```text
<!DOCTYPE html>
<html>

	<head>
		<title>Snow Leopard Challenges</title>
		<link rel="stylesheet" href="style.css" />
  </head>

	<body>
		<header>
					<a href="index.html"><img class="logo"  src="images/logo.png" width="60" alt="logo"/></a>

					<nav>
						<a href="index.html">Snow Leopard Home  </a>|
						<a href="#"> Snow Leopard Challenges</a>
					</nav>

		</header>

		<main>
		<h1>Snow Leopard Challenges</h1>

		<h2>Countries Where the Snow Leopard Is Endangered</h2>

		<p>Although snow leopards have ruled the mountains of Central Asia for thousands of years, recently their numbers are dropping in the following countries:</p>

		<ul>
			<li>China</li>
			<li>Bhutan</li>
			<li>Nepal</li>
			<li>India</li>
			<li>Pakistan</li>
			<li>Afghanistan</li>
			<li>Russia</li>
			<li>Mongolia</li>
		</ul>

		<a target="_blank" href="https://defenders.org/wildlife"><img src="images/cubs.jpg" width="400" alt="Snow leopard Cubs" title="Snow Leopard Cubs"/></a>
		
		<h3>Cute Snow Leopard Cubs</h3>


		<h2>Causes of Snow Leopard Population Decline</h2>

		<p>Many factors contribute to declining snow
			leopard numbers in these countries. Some of them are:
		</p>

		<ol>
			<li>Climate change - greatest long term threat that could destroy 30% of their habitat</li>
			<li>Local communities - kill the animals snow leopards prey upon</li>
			<li>Killed by farmers - when they prey on their livestock to survive</li>
			<li>Human settlement in their range - forces them to survive in smaller areas with less prey</li>
		</ol>


		</main>

		<footer>
			&copy; 2019 Created by Gayle D.
		</footer>	
	</body>
</html>
```

