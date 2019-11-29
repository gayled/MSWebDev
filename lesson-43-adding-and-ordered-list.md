# Lesson 4.3 Adding an Ordered List

When the order of your list matters, you want to use the ordered list element, &lt;ol&gt;.

1. Create another subheading and short paragraph to introduce the content of your ordered list.
2. Ordered lists use numbers as defaults. Ordered list elements are **&lt;ol&gt;** and **&lt;/ol&gt;**.
3. Nest the list items **&lt;li&gt;** and **&lt;/li&gt;** of your ordered list within your **&lt;ol&gt;** tags just as you did for your unordered list.
4. HTML uses **&lt;strong&gt; &lt;/strong&gt;** tags as a semantic element which adds emphasis to words or phrases. This replaces the deprecated \(not supposed to be used anymore\) &lt;b&gt; or bold tags. Enclose the part of your list items that need emphasis with &lt;strong&gt; tags.
5. Add another image between the two lists.

## Code Example

```text

<!DOCTYPE html>
<html>

	<head>
		<title>Snow Leopard Challenges</title>
		<link rel="stylesheet" href="style.css" />
	</head>

	<body>
			<a href="index.html"><img class="logo"  src="images/logo.png" width="60" alt="logo"/></a>

			<nav>
				<a href="index.html">Snow Leopard Home  </a>|
				<a href="#"> Snow Leopard Challenges</a>
			</nav>

		<h1>Snow Leopard Challenges</h1>

		<h2>Countries Where the Snow Leopard Is Endangered</h2>

		<p>Although snow leopards have ruled the mountains of Central 
		Asia for thousands of years, recently their numbers are dropping 
		in the following countries:</p>

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
			<li><strong>Climate change</strong> - greatest long term threat that could destroy 30% of their habitat</li>
			<li><strong>Local communities</strong> - kill the animals snow leopards prey upon</li>
			<li><strong>Killed by farmers</strong> - when they prey on their livestock to survive</li>
			<li><strong>Human settlement in their range</strong> - forces them to survive in smaller areas with less prey</li>
		</ol>

	</body>
</html>
```

