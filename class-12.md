# HTML <canvas> Element & Chart.js
`<canvas>` :element is used to draw graphics, on the fly, via JavaScript and its  only a container for graphics. You must use JavaScript to actually draw the graphics.
> Canvas has several methods for drawing paths, boxes, circles, text, and adding images.
## how to draw Shapes using Canvas
The  canvas element can be styled just like any normal image margin, border, background. These rules, however, don't affect the actual drawing on the canvas. 
 canvas only supports two primitive shapes: rectangles and paths lists of points connected by lines. All other shapes must be created by combining one or more paths.
 there are three functions that draw rectangles on the canvas:
 1.fillRect(x, y, width, height)
 2.strokeRect(x, y, width, height)
 3.clearRect(x, y, width, height)

# what is chart js
:Chart.js is a free open-source JavaScript library for data visualization, which supports 8 chart types: bar, line, area, pie, bubble, radar, polar, and scatter
steps in applaying chart js in your web page
1. download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in
2. To draw a line chart, the first thing we need to do is create a canvas element in our HTML
`<canvas id="buyers" width="600" height="400"></canvas>`
3.  add this to the foot of your body element:
 `<script>`
`var div = document.getElementById('id div').getContext('2d');`
`new Chart(div).Line(buyerData);`
`</script>`4
4. Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart
5. Drawing a pie chart
`<canvas id="id of that div were using" width="600" height="400"></canvas>`
6.we need to get the context and to instantiate the chart
`<script>`
`var div= document.getElementById("id of the div").getContext("2d");
new Chart(div).Pie(pieData, pieOptions);`
`</script>`
7. Next we need to create the data
ex:
`var pieData = [`
	`{`
		`value: 20,`
		`color:"#878BB6"`
	`},`
8.immediately after the pieData we’ll add our options
` var pieOptions = {`
`	segmentShowStroke : false,`
	`animateScale : true`
}
