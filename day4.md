Bootcamp 1 Day 4
================

#Work on the assignment below:

Using what you learned the previous day create the standard HTML mark up. 

+ Go over file structure and setting up the folders. 
+ tag nesting (makes everything cleaner).

####The code below 	
```html
<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8">
     <title>Our Favorite Everything</title>
</head>
<body>
     <header>
          <div class="logo">
               <img src="http://upload.wikimedia.org/wikipedia/commons/e/e1/Featured_Article_Star.svg" alt="star">
               <p>Our favorite everything</p>
          </div>
     </header>

     <nav>
          <ul>
               <li><a href="../2-16/index.html">About Us</a></li>
               <li><a href="../2-18/index.html">Projects</a></li>
               <li><a href="../2-23/index.html">Skills</a></li>
               <li><a href="../2-25/index.html">Contact Us</a></li>
          </ul>
     </nav>

     <main>
          <h1>Welcome!</h1>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Modi, quo ad, eaque doloremque placeat voluptas accusamus aut qui ea sed, ab culpa iusto officia expedita quia animi! Quidem omnis, fugiat!</p>

          <h2>Favorites:</h2>
          <ul>
               <li>TV Shows</li>
                    <ol>
                         <li><a href="http://abc.go.com/shows/shark-tank">Shark Tank</a></li>
                         <li><a href="http://www.amctv.com/shows/breaking-bad" target="_blank">Breaking Bad</a></li>
                         <li><a href="http://www.nbc.com/americas-got-talent">AGT</a></li>
                    </ol>
               <li>Movies</li>
               <ol>
                    <li>The Pursuit of Happiness</li>
                    <li>Shutter Island</li>
                    <li>Avatar</li>
               </ol>
          </ul>

          <h3>Important</h3>
          <p>Lorem ipsum dolor sit <a href="mailto:blah@gmail.com">email me</a>, consectetur adipisicing elit. Officiis asperiores natus, commodi tempore id mollitia in eius nam iste modi dolore error, voluptatibus quisquam repellendus vero eos rem ab maxime.</p>

          <h4>Semi Important</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Blanditiis optio quisquam eveniet, eius nemo cum at corporis vitae itaque! Modi quibusdam ducimus, necessitatibus ad excepturi alias qui sint possimus nam.</p>

          <h5>Not As Important</h5>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officia consequuntur atque, qui possimus deserunt voluptatem nam blanditiis obcaecati similique voluptatum perferendis natus, optio impedit architecto dolorum cum sit. Voluptatem, nulla.</p>

          <h6>Least Important</h6>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto magni labore illo architecto ipsum? Magni voluptates porro dicta, laborum, quae dolorem, sint non atque repudiandae inventore ab id cupiditate, odio.</p>
     </main>

     <footer>
          <p>Copyright &copy; 2015</p>
     </footer>
</body>
</html>
```
 ###best practices in coding.
	good and bad practices
### Let's look at some popular websites with out their style sheets.
+ We will look into a few sites and remove all the styling from them.
	+ [craiglist](https://fresno.craigslist.org/)
	+ [This is an example of bad HTML code](http://www.highcallingcockers.com/)
	+ [This is an example of good HTML code](http://transferwindow.info/)
+ Create a skeleton site with all the attributes. 
+ introduction to validator.     
+ intro to css