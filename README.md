To access this updated portfolio:

http://reversearrow.github.io/web-perf/views/pizza.html

Optimizations made:

1) Displaying pizzas based on the screen size
2) De-bouncing scroll events
3) Fixing Slider using applying % with newwidth
4) Achieved above 90 score on mobile by inlining the CSS on index.html
5) Implemented GRUNT and minifed HTML, CSS and Javascript
6) Optimized Image using Grunt
7) Replace "document.querySelector" by document.getElementById() for faster API calls.
8) Saved array length for optimization purposes
9) Moved DOM lookup outside the for loop for faster processing

Sources used to optimize the page:

http://gent.ilcore.com/2011/03/how-not-to-trigger-layout-in-webkit.html
http://www.html5rocks.com/en/tutorials/speed/animations/
http://ejohn.org/blog/learning-from-twitter/
https://github.com/udacity/fend-office-hours/tree/master/Web%20Optimization/Effective%20Optimizations%20for%2060%20FPS
https://javascriptweblog.wordpress.com/2010/10/11/rethinking-javascript-for-loops/
