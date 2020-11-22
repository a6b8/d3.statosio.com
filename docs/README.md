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
[Source Code](../tutorials/select-data.html)


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
[Source Code](../tutorials/sort-data.html)


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
[Source Code](../tutorials/dark-mode.html)

## Speedtest

| **Name** | **Result** |
| Loading Time | <insert id='statosioLoadingTime'>waiting..</insert> |
| Dom Elements | <insert id='statosioDomElements'>waiting..</insert> |


