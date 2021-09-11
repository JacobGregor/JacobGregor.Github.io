### Chart.js


### **Line Chart**
1. create a `<canvas>` and write a `<script>` we will attach to the body. 
2. Inside our script tag where we declared our canvas we will create our Var. & Objects for the charts. (example below)
``` javaScript

var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}

```

### **Pie CHart**
1. Canvas Element
`<canvas id="countries" width="600" height="400"></canvas>`

2. Context and chart instantiation
`var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions);`

3.  Add our pie data

`var pieData = [
	{
		value: 20,
		color:"#878BB6"
	},
	{
		value : 40,
		color : "#4ACAB4"
	},
	{
		value : 10,
		color : "#FF8153"
	},
	{
		value : 30,
		color : "#FFEA88"
	}
];`

4. lastly we edit our Pie pieOptions
`var pieOptions = {
	segmentShowStroke : false,
	animateScale : true -> //Allows us to animate the chart//
}`

### **Bar Chart**

1. `<canvas id="income" width="600" height="400"></canvas>`

2. Gather Elements and build chart
`var income = document.getElementById("income").getContext("2d");
new Chart(income).Bar(barData);`

3. Build Bar Chart 
`var barData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "#48A497",
			strokeColor : "#48A4D1",
			data : [456,479,324,569,702,600]
		},
		{
			fillColor : "rgba(73,188,170,0.4)",
			strokeColor : "rgba(72,174,209,0.4)",
			data : [364,504,605,400,345,320]
		}

	]
}`

### Further Documentation on Chart.js found here: https://www.chartjs.org/docs/latest/


## Canvas 

`<canvas id="tutorial" width="150" height="150"></canvas>`
-> by default the canvas element will be 300px wide by 150 tall. 
-> its best to determin a canvas size within this declaration, rather than styling with CSS later..


Rendering Canvas Context: 

`var canvas = document.getElementById('tutorial');
var ctx = canvas.getContext('2d');`

- Scripts start blank so by giving context we are able to render our content to the page. 

### Drawing shapes with Canvas

Origin of a canvas grid is Top left Corner (0,0) positions are pixel relations from there. 

**BAsic Draw() Functions:**

`fillRect(x, y, width, height)
Draws a filled rectangle.`

`strokeRect(x, y, width, height)
Draws a rectangular outline.`

`clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.`

**PAth Functions**
-> Paths are used to draw segments between points. 

`beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.`

`Path methods
Methods to set different paths for objects.`

`closePath()
Adds a straight line to the path, going to the start of the current sub-path.`

`stroke()
Draws the shape by stroking its outline.`

`fill()
Draws a solid shape by filling the path's content area.`

Documentation on Canvas Color: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors

Documentation on Canvas drawText(): https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text

