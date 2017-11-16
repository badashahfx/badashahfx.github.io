## Website Performance Optimization portfolio project

Challenge was to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques.

> Desktop Score: 95/100

> Mobile Score: 94/100

### Instructions
  
* Open 'index.html' from the folder.

* Scroll down and Click on 'Cam's Pizzeria' link.

* Scroll down to see the pizzas sliding at 60 fps.

* Use the pizza size slider on the page to change the size of pizza.


#### Part 1: Optimize PageSpeed Insights score for index.html

 * Converted pics from external hosting to local.
 
 * Optimized images using optimizilla.com.
 
 * Resized pizzeria thumb image.
 
 * Moved scripts to the bottom of the body.
 
 * Inlined styles from styles.css to eliminated this style sheet.
 
 * Minified css and js.


#### Part 2: Optimize Frames per Second in pizza.html

Optimized views/pizza.html, by modifying views/js/main.js until frames per second rate is 60 fps or higher and Time to resize pizzas is less than 5 ms using the pizza size slider.
 
 * Redcued number of pizzas in the DOMContentLoader.
 
 * Time to resize pizza optimzed down to less than 5ms for the pizza side slider.
 
 * Modifed updatePositions() function to calculate outside of the loop.
 
 * Changed query.Selectors to getElementId

 * Minified css and js.

#### Links

* <a href="http://optimizilla.com">Optimizilla</a>
* <a href="https://www.minifier.org/">Minifier</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
