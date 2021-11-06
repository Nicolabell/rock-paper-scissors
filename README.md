# Rock Paper Scissors

A tutorial from FreeCodeCamp

I found this to be a really excellent tutorial to follow in order to solidify what I have learned over the last couple of years about how HTML, CSS and JavaScript interact.
I built the game in codepen. My original version is here: https://codepen.io/nicolarb/pen/PoYvamR (I plan to fork for different iterations which I can improve on.)

The tutorial starts by building out the HTML to show what was going to appear on the page, including images. CSS classes and IDs are included within the HTML to be used later for the CSS. Using the classes specified in the HTML, CSS is applied to these elements. We then build out the JavaScript by referencing the DOM elements and applying different event listeners to them. There is opportunity to practice JavaScript loops, arrays, traversing the DOM, updating DOM elements, writing functions, using inbuilt methods to generate random numbers, understanding the difference between const var and let, switch statements, logging to the console and more.

There were some good examples of how to use absolute positioning in CSS to position the labels for the scoreboard. The screengrab below shows how when we start to use this rule, by default the positioning is going to be based on the top left hand corner of the DOM. In this scenario the positioning needed to be based on the scoreboard itself. This is where we have to specify that we want the positioning to be based on the parent element.

When the tutorial had moved on to the JavaScript section I also learned how to 'cache the dom'. This is a really efficient way to store the references to the different dom elements at the start of the javaScript build so that the full reference does not have to be written out each time. You can see in the screengrab below that I am writing out a const variable that caches the reference to the dom element based on it's ID. 


