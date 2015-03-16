##Goal for the day: Recap understanding of the box model and floats. Go over positioning again. Implement the blog page for talk nerdy.
+ 6:00 - 6:30 = Recap Box Modeling & Floats (Vanessa)

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Box Model Theory & Floats</title>
	<link rel="stylesheet" href="css/styles.css">
</head>
<body>
	<div class="container">
	    <div class="box one">
	    	<h1>Box 1</h1>
	    	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum tempore dignissimos, modi impedit laboriosam alias, dolor nesciunt repellat ipsam commodi distinctio temporibus, veritatis et molestiae. Nihil, dicta eveniet vero tempore!</p>
	  	</div>
	  	<div class="box two">
	    	<h1>Box 2</h1>
	    	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum tempore dignissimos, modi impedit laboriosam alias, dolor nesciunt repellat ipsam commodi distinctio temporibus, veritatis et molestiae. Nihil, dicta eveniet vero tempore!</p>
	  	</div>
	  	<div class="box three">
	    	<h1>Box 3</h1>
	    	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum tempore dignissimos, modi impedit laboriosam alias, dolor nesciunt repellat ipsam commodi distinctio temporibus, veritatis et molestiae. Nihil, dicta eveniet vero tempore!Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum tempore dignissimos, modi impedit laboriosam alias, dolor nesciunt repellat ipsam commodi distinctio temporibus, veritatis et molestiae. Nihil, dicta eveniet vero tempore!Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum tempore dignissimos, modi impedit laboriosam alias, dolor nesciunt repellat ipsam commodi distinctio temporibus, veritatis et molestiae. Nihil, dicta eveniet vero tempore!</p>
	  	</div>
	  	<footer class="clearfix">
	    	<p>&copy; Bootcamp1 2015</p>
	  	</footer>
	</div>
</body>
</html>

```

```css
body{
	background-color: grey;
}
.container{
	border: 5px dashed red;
	width: 800px;
}
.clearfix{
	content: "";
	clear: both;
	display: table;
}
.box{
	background-color: white;
	padding: 10px;
	border-radius: 10px;
	text-align: center;
	float: left;
    min-height: 300px;
}
.one{
    width: 300px;
    border: 10px solid navy;
    margin: 10px;
}
.two{
    width: 190px;
    border: 10px solid green;
    margin: 10px 10px 10px 0px;
}
.three{
    width: 540px;
    border: 10px solid yellow;
    margin: 0px 10px 10px 10px;
}
footer{
    width: 100%;
    text-align: center;
    clear: both;
}
```

+ 6:30 - 7:30 = Positioning (Victor)

http://vperezma.github.io/positioning/

+ 7:30 - 7:45 = Break
		Take a break.


+ 8:30 - 8:45 = Questions


+ 8:45 - 9:00 = Wrap Up
