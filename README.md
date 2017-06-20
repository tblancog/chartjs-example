# chartjs-example

A simple chart using chart.js library

## Installation
```bash
npm install chart.js --save
```

## Usage
Create a canvas element and then in javascript create a context to initialise it

```html
<body>
  <canvas id="myChart"></canvas>
  <script type="text/javascript" src="node_modules/chart.js/dist/Chart.min.js" charset="utf-8"></script>
</body>
```

And initialize the desired chart

```javascript
<script type="text/javascript">
let ctx = document.getElementById('myChart').getContext('2d')
var myChart = new Chart(ctx, {
    type: 'line',
    data: data,
    options: options
});
</script>
```

You can browse all examples for any charts in the plugin [docs](http://www.chartjs.org/docs/latest/charts/)
