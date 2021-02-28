# MK Charts
A simple pure Javascript for displaying circle charts.

Demo: <https://mkirschen.de/mk-scripts/mk-charts/>

## Circle charts

![alt text](https://mkirschen.de/assets/images/circle_charts_examples_github.PNG "MK Charts Examples")

To insert a chart all you need is the following `div`:
```html
<div class="mkCharts" data-percent="15" />
```

The other attributes are optional and customize the appearance.
```html
data-type      | default = circle
data-color     | default = #2F4F4F
data-size      | default = 100
data-stroke    | default = 1
```

### Examples
```html
<div class="mkCharts" data-percent="15"></div>
<div class="mkCharts" data-percent="42" data-color="#654321"></div>
<div class="mkCharts" data-percent="83" data-color="pink" data-size="125"></div>
<div class="mkCharts" data-percent="94" data-color="rgb(0,100,200)" data-size="155" data-stroke="3"></div>
```
