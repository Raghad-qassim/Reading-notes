# Charts JS

charts better for displaying data visually than tables.
They are easier to look at and convey data quickly.

**Installation**

You can download the latest version of Chart.js from the GitHub releases or use a Chart.js CDN.

**Craeting a chart**

All  required is the script included in your page along with a single (canvas) node to render the chart.

**Type of chart:**

1)line chart

Steps to draw a line chart:

1) we need to do is create a canvas element in HTML

2) we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element.

![line chart](https://apexcharts.com/wp-content/uploads/2018/01/line-chart-zoomable-timeseries.svg)

2)pie chart

Steps to draw a pie chart:

1)we need the canvas element

2)we need to get the context and to instantiate the chart

3)we need to create the data. 

![pie chart](https://apexcharts.com/wp-content/uploads/2018/05/simple-donut-chart.svg)


3)bar chart

   Steps to draw a bar chart:

1)we add the canvas element

2)we retrieve the element and create the graph

3)add in the bar chart’s data

![bar chart](https://www.createwithdata.com/images/getting-started-with-chartjs/barchart-horizontal.png)

# canvas API

The (canvas) element has only two attributes, width and height.

The id attribute isn't specific to the (canvas) element but is one of the global HTML attributes which can be applied to any HTML element.

The (canvas) element requires the closing tag (/canvas)


The(canvas) element creates a fixed-size drawing surface that exposes one or more rendering contexts.

(canvas) only supports two primitive shapes: rectangles and paths (lists of points connected by lines).

**There are three functions that draw rectangles on the canvas:**

1)Draws a filled rectangle

fillRect(x, y, width, height)

2)Draws a rectangular outline

strokeRect(x, y, width, height)

3)Clears the specified rectangular area

clearRect(x, y, width, height)

**Step to drawing a path :**

1)create the path.

2) use drawing commands to draw into the path

3) stroke or fill the path to render it.

 functions used to perform these steps:

 1)beginPath()

 2)closePath()

 3)stroke()

 4)fill()

 **moving the pen**

 moveTo(x, y)

Moves the pen to the coordinates specified by x and y

**Drawing aline**

For drawing straight lines, use the lineTo() method.

lineTo(x, y)

**Drawing Arc**

To draw arcs or circles, we use the arc() or arcTo() methods.

arc(x, y, radius, startAngle, endAngle, anticlockwise)

# Applying style and colors

To apply colors to a shape, there are two important properties we can use: 
1)fillStyle 

Sets the style used when filling shapes.

2)strokeStyle.

Sets the style for shapes' outlines.

**The globalAlpha property can be useful if you want to draw a lot of shapes on the canvas with similar transparency**

**line style**

1)lineWidth = value

Sets the width of line

2)lineCap = type

Sets the appearance of the ends of lines.

3)miterLimit = value

Establishes a limit on the miter when two lines join at a sharp angle

4)getLineDash()

Returns the current line dash pattern array

5)setLineDash(segments)

Sets the current line dash pattern

6)lineDashOffset = value

Specifies where to start a dash array on a line

**The lineJoin property determines how two connecting segments (of lines, arcs or curves) with non-zero lengths in a shape are joined together**

We create a CanvasGradient object by using one of the following methods

1)createLinearGradient(x1, y1, x2, y2)

2)createRadialGradient(x1, y1, r1, x2, y2, r2)

3)createConicGradient(angle, x, y)

**Shadows**

Using shadows involves just four properties:

1)shadowOffsetX = float

2)shadowOffsetY = float

3)shadowBlur = float


4)shadowColor = color

# Drawing text

The canvas rendering context provides two methods to render text:

1)fillText(text, x, y [, maxWidth])

Fills a given text at the given (x,y) position

2)strokeText(text, x, y [, maxWidth])

Strokes a given text at the given (x,y) position

**Styling text**

1)textAlign = value

Text alignment setting

2)textBaseline = value

Baseline alignment setting.

3)direction = value

Directionality
