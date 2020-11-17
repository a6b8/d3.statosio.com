# d3.statosio

An add-on function for [d3](https://d3js.org){:target="_blank"} to generate simple chart diagrams, fast and reliable.


## Features

:heavy_check_mark: build simple diagrams fast and reliable, with one function!

:heavy_check_mark: pure javascript, no additonal css.

:heavy_check_mark: highly customizable with 40+ style and data options.

## Try it out!

### Bar Charts

<div id="bar">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { "showTitle" : false, "viewDomId" : "bar" }
        )
    </script>
</div>
[Source Code](../options/show__title.html#source-code) | [Download Source Code as .zip](../sources/showTitle.zip)


### Point Charts

<div id="point">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { "showTitle" : false, "showDataAsCircle": true, "viewDomId" : "point" }
        )
    </script>
</div>
[Source Code](../options/show__data_as_circle.html#source-code) | [Download Source Code as .zip](../sources/showDataAsCircle.zip)


### Stacked Bar Charts

<div id="stacked">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile", "desktop" ], 
            { "showLegend": true, "viewDomId" : "stacked" }
        )
    </script>
</div>
[Source Code](../options/show__legend.html#source-code) | [Download Source Code as .zip](../sources/showLegend.zip)





