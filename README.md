# d3.statosio

An add-on function for [d3](https://d3js.org){:target="_blank"} to generate simple chart diagrams, fast and reliable.


## Features

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
[Source Code](../options/show__average.html#source-code-1) | [Download Source Code as .zip](../sources/showAverage.zip)


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
[Source Code](../options/show__data_as_circle.html#source-code-2) | [Download Source Code as .zip](../sources/showDataAsCircle.zip)

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
[Source Code](../options/show__legend.html#source-code-2) | [Download Source Code as .zip](../sources/showLegend.zip)


## Features

### Select Row

<div id="selected-row">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { "dataXSelectors" : ["Data"], "showAverage": false, "viewDomId" : "selected-row" }
        )
    </script>
</div>
[Source Code](../options/data__x__selectors.html#source-code) | [Download Source Code as .zip](../sources/dataXSelectors.zip)


### Sort Data<br><br>

<div id="sort-data">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { "dataSortCurrent" : "values", "dataSortByValues" : "ascending", "showAverage" : false, "viewDomId" : "sort-data" }
        )
    </script>
</div>
[Source Code](../options/data__sort__by__values.html#source-code) | [Download Source Code as .zip](../sources/dataSortByValues.zip)


### Customize Style

<div id="customize">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { 
                "styleColorSelectorsChart": ["#E2B08E", "#CC8074"],
                "dataXSelectors" : ["Data"],
                "styleColorCanvasBackground" : "none",
                "styleColorGridline" : "#2F3138",
                "styleStrokeGridline" : 1,
                "styleColorFont" : "#BABABA",
                "styleColorSelectorsText" : ["#E2B08E", "#BABABA"],
                "dataSortSelection" : "start",
                "dataSortCurrent" : "values", 
                "dataSortByValues" : "ascending", 
                "showAverage" : false, 
                "viewDomId" : "customize" 
            }
        )
    </script>
</div>


## Speedtest

| **Name** | **Result** |
| Loading Time | <insert id='statosioLoadingTime'>waiting..</insert> |
| Dom Elements | <insert id='statosioDomElements'>waiting..</insert> |


