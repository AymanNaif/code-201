# Chart.js, Canvas

# Chart.js, Canvas

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. Theyâ€™re easier to look at and convey data quickly, but theyâ€™re not always easy to create.
A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5â€™s canvas element to draw the graph onto the page. Itâ€™s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

Setting up
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory youâ€™ll be working in. Then create a new html page and import the script:
![11](https://user-images.githubusercontent.com/79080942/111068087-f47f1d00-84cf-11eb-9104-d382a978aaf7.PNG)

Drawing a line chart
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart
Next, we need to write a script that will retrieve the context of the canvas,
nside the same script tags we need to create our data, in this instance itâ€™s an object that contains labels for the base of our chart and datasets to describe the values on the chart
If you test your file in a browser youâ€™ll now see a cool animated line graph.

Drawing a pie chart
Our line chart is complete, so letâ€™s move on to our pie chart.
Next, we need to get the context and to instantiate the chart
Youâ€™ll notice that this time, we are going to supply some options to the chart.

Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler 
Now, immediately after the pieData weâ€™ll add our options
These options do two things, first they remove the stroke from the segments, and then they animate the scale of the pie so that it zooms out from nothing.

Drawing a bar chart
Finally, letâ€™s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart weâ€™ve already added. 
Next, we retrieve the element and create the graph
And finally, we add in the bar chartâ€™s data As you can see, the data is largely the same, except this time weâ€™ve chosen to use RGBA to specify our colors which allows us to add transparency.


### Basic usage of canvas
Let's start this tutorial by looking at the <canvas> HTML element itself. At the end of this page, you will know how to set up a canvas 2D context and have drawn a first example in your browser.
The <\canvas> element

Drawing shapes with canvas
Now that we have set up our canvas environment, we can get into the details of how to draw on the canvas. By the end of this article, you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes. Working with paths is essential when drawing objects onto the canvas and we will see how that can be done.

Note: If your renderings seem distorted, try specifying your width and height attributes explicitly in the <canvas> attributes, and not using CSS.

The id attribute isn't specific to the <canvas> element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance). It is always a good idea to supply an id because this makes it much easier to identify it in a script.

The <canvas> element can be styled just like any normal image (margin, border, backgroundâ€¦). These rules, however, don't affect the actual drawing on the canvas. We'll see how this is done in a dedicated chapter of this tutorial. When no styling rules are applied to the canvas it will initially be fully transparent.

Fallback content
The <canvas> element differs from an <img> tag in that, like for <video>, <audio>, or <picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

Providing fallback content is very straightforward: just insert the alternate content inside the <canvas> element. Browsers that don't support <canvas> will ignore the container and render the fallback content inside it. Browsers that do support <canvas> will ignore the content inside the container, and just render the canvas normally.
 
