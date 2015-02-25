Bootcamp 1 Day 4
================

Using what we learned the previous day we will create the standard HTML mark up. 

+ Go over file structure and set up the folders. 
+ tag nesting (makes everything cleaner).

####The code below shows an example of nesting.	
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
          <ul class="tvList">
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
###Best practices in coding.
	+ [good and bad practices](http://learn.shayhowe.com/html-css/writing-your-best-code/)
### Let's look at some popular websites without their style sheets.
+ We will look into a few sites and remove all the styling from them.
	+ [craiglist](https://fresno.craigslist.org/)
	+ [This is an example of bad HTML code](http://www.highcallingcockers.com/)
	+ [This is an example of good HTML code](https://www.missionbicycle.com/)
+ introduction to validator.(With Sara)
	+ [click this to go to a validator](http://validator.w3.org/#validate_by_uri)     
+ intro to css (with Sara)