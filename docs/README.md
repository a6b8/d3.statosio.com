![# d3.statosio](./assets/images/d3-statosio-200.png)

An add-on function for [d3](https://d3js.org){:target="_blank"} to generate simple chart diagrams, fast and reliable.


:heavy_check_mark: build simple diagrams fast and reliable, with one function!

:heavy_check_mark: pure javascript, no additonal css.

:heavy_check_mark: highly customizable with 40+ style and data options.


## Chart Types

### Bar Charts

<div id="bar">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { "showAverage" : false, "viewDomId" : "bar" }
        )
    </script>
</div>
[Create simple bar chart](../tutorials/simple-bar-chart.html)

### Point Charts

<div id="point">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { "showDataAsCircle" : true, "showAverage" : false, "viewDomId" : "point" }
        )
    </script>
</div>
[Create a simple point chart](../tutorials/simple-point-chart.html)

### Stacked Bar Charts

<div id="stacked">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile", "desktop" ], 
            { "showLegend": true, "showAverage" : false, "viewDomId" : "stacked" }
        )
    </script>
</div>
[Create simple stacked bar chart](../tutorials/simple-stacked-bar-chart.html)

## Features

### Select columns<br><br>

<div id="select-columns">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { 
                "dataXSelectors" : ["Data", "Spock"],
                "dataSortSelection" : "start",
                "showAverage" : false,
                "viewDomId" : "select-columns"
            }
        )
    </script>
</div>
[Select and change position of columns](../tutorials/select-data.html)

### Sort Data<br><br>

<div id="sort-data">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { 
                "dataSortCurrent" : "values", 
                "dataSortByValues" : "ascending", 
                "showAverage" : false,
                "viewDomId" : "sort-data"
            }
        )
    </script>
</div>
[Sort dataset by values](../tutorials/sort-data.html)

### Customize Style

<div id="customize">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { 
                "styleColorSelectorsChart": ["#E2B08E", "#CC8074"],
                "styleColorCanvasBackground" : "none",
                "styleColorGridline" : "#2F3138",
                "styleStrokeGridline" : 1,
                "styleColorFont" : "#BABABA",
                "styleColorSelectorsText" : ["#E2B08E", "#BABABA"],
                "showAverage" : false,
                "viewDomId" : "customize"
            }
        )
    </script>
</div>
[Change style to dark-mode](../tutorials/change-style.html)

## Speedtest

| **Name** | **Result** |
| Loading Time | <insert id='statosioLoadingTime'>waiting..</insert> |
| Dom Elements | <insert id='statosioDomElements'>waiting..</insert> |


