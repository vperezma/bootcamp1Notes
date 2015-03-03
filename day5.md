Bootcamp 1 Day 5
=================

#Goals: review CSS, assess HTML knowledge and review, begin “talk nerdy”site to learn wireframes, headers, footers, container, div(classes & id's) sidebars, navigation.

*6:05 - 6:15: Recap on what happened last week. HTML rundown and introduction to CSS.

##CSS review
	- What are some of the CSS styles we went over last Wednesday?
	- How do you style a border in CSS? 
	- What are the three ways you can connect your CSS to your HTML?

*6:15 - 6:45: 
###[HTML Quiz](http://tinyurl.com/lxjewvy)
###[Answers to the quiz with links to w3school](https://docs.google.com/document/d/1yovPxQSEBlNx_BWmSYRZNcVsdVjhapCbaGN6pwr7c0w/edit)

*6:45 - 7:00 TAKE A BREAK!

*7:00 - 7:20 
###[Let's take another quiz!](http://tinyurl.com/l6rfgu3)

*7:20 - 8:30
 ##Setting up a new folder and HTML document from scratch.

 ##HTML code for talk nerdy.
 ```html
	<!DOCTYPE html>
<html lang="en">
<head>
	<title>Talk Nerdy</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>

	<div class="container">
		<header>
			<img src="img/header.png">
		</header>

		<nav>
			<ul>
				<li>
					<a href="index.html">Home</a>
				</li>
				<li>
					<a href="#">Blog</a>
				</li>
				<li>
					<a href="#">Contact</a>
				</li>
			</ul>
		</nav>
	</div><!-- /container -->

</body>
</html>

 ```
 ##CSS code for talk nerdy.
 ```CSS
	.container {
		width:1000px;
		margin: 0 auto;
	}

	header {
		width:1000px;
	}

	nav {
		background-color:#3e7ca5;
	}

	nav ul {
		text-align: center;
	}

	nav ul li {
		list-style-type: none;
	}

	a:link {
		text-decoration: none;
		color: #fff;
	}

	a:visited {
		color: #000;
	}

	a:hover {
		color: #999;
	}

	a:active {
		color: #CC3300;
	}
 ```

<!-- At the end of these next 2 classes we will have a site that looks like this: [talk nerdy](http://www.talknerdy.net) -->

*8:30 - 8:45 questions.

*8:45 - 9:00 Wrap. 
