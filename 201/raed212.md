# Chart (JS)

### A chart is a graphical representation for data visualization, in which "the information is represented by the symbol. Briefly, it wonderful way to display the information.

> ![Chart](https://www.ft.com/__origami/service/image/v2/images/raw/ftcms%3A347ece48-0f69-11e9-a3aa-118c761d2745?source=ig)

### 'Chart.js', is great way to get started with charts, uses HTML5’s canvas element to draw the graph onto the page. how to use it :

1. Setting up

- Copy the Chart.min.js (script link) to your work.
- ` <script src='Chart.min.js'></script>`

2. Drawing a chart

- First thing we need to create a canvas element in our HTML, at end of the body.
  - `<canvas id="buyers" width="600" height="400"></canvas>`
  - canvas has only two attributes, width and height. And we can add id and class.
  - We can applying CSS to it like colors.

3. Next in js, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:

- ` var buyers = document.getElementById('buyers').`<br>`getContext('2d'); ` <br> `new Chart(buyers).Line(buyerData);`
- Then, create our data
- `var buyerData = {` <br> `labels : ["January","February","March","April","May","June"],` <br>` datasets : [`<br>` {`<br>` fillColor : "rgba(172,194,132,0.4)",`<br>` strokeColor : "#ACC26D",`<br>` pointColor : "#fff",`<br>` pointStrokeColor : "#9DB86D",`<br>` data : [203,156,99,251,305,247]`<br>` }`<br>` ]`<br>`}`

4. You can change the data as you want, but you should save the structure.

- the "labels" should be an array , the color should be in " " , ...
- You can change the type of the chart as you want , from bars to lines easily if you used other code in 'chart.js' Supports this feature.
- > ![chart type](https://vaadin.com/docs/v14/static/409a9ee854cf6d367c4dd6553d4c679f/03979/charts-overview.png)

### Conclusion

- You can view a demo of this in web site (www.chartjs.org), and if you prefer copy and paste,You modify it to suit your code.

> outsource : library of charts : https://www.chartjs.org
