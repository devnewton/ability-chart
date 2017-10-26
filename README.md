# \<ability-chart\>

A canvas based ability chart component

## Preview
An easy to use and fully customizable ability chart web component based on Polymer 2.0.

## Usage
Add onto html just as normal tag elements. Use attribute `prop` to set up all the styles you want.

```html
<ability-chart prop='{
                  "eachPoint":[
	                  {"key":"Math", "value":85},
	                  {"key":"Physics", "value":30},
	                  {"key":"English", "value":55},
	                  {"key":"Chemistry", "value":100},
	                  {"key":"Chinese", "value":10},
	                  {"key":"History", "value":100}]}'>               	
</ability-chart>
```
## prop Options

prop Name | Description
--- | --- 
dimension | A number (i.e. `300`). <br>The height and width of the chart in px.
numLayer | A number (i.e. `3`). <br>The number of equally divided layers of the chart.
eachLayerStyle | An array of object (i.e. `{"fillColor: "#bf0a0a", ""borderColor": "#207476""}`).<br>`fillColor` is the color filled in the layer. <br>`borderColor` is the border color of the layer.
labelFont | A css font string (i.e. `"12px Arial"`). <br>The font of labels.
labelFontColor | A css color string (i.e. `"black"`). <br>The color of labels.
fillColor | A css color string (i.e. `"#d666c6"`). <br>The color of defined chart area.
borderColor | A css color string (i.e. `"#d666c6"`). <br>The border color of defined chart area.
frameBorderWidth | A number (i.e. `1`). <br>The border width of the chart frame. 
chartBorderWidth | A number (i.e. `1`). <br>The border width of the defined chart area.
decorLineColor | A css color string (i.e. `"black"`). <br>The color of the center-to-vertex decoration lines.
chartPortion | A number (i.e. `0.7`). <br>The portion of the chart within the canvas. 
chartAlpha | A number (i.e. `0.7`). <br>The opacity of the defined chart area.
eachPoint | An array of object (i.e. `{"key":"Strength", "value":30}`). <br>`key` is the label of each vertex. <br>`value` is the vertex value between 0 and 100.

## License
MIT