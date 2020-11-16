---
sort: 25
title: C.11. dataLegendTextSeparater
---
# dataLegendTextSeparater

This tweak split your keys with the separater and capitalize every word and insert a space in between.


## Specification

Default implementation: ```{ dataLegendTextSeparater : _ }```

### Key

| **Name**| **Alias**| **Category** |
| ```dataLegendTextSeparater```| ```data__legend__text__separater```| [Data](../options/#data) |

### Value

Allow A-Z, a-b and 0-9 as value.

| **Default**| **Validation**| **Type** |
| ```"_"```| ```^[a-zA-Z0-9]*$```| String |



## Example A.

Replace character "```_```" to " " in the legend text label

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "showLegend" : true, "self" : "_", "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataLegendTextSeparater--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/dataLegendTextSeparater.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "showLegend" : true, "self" : "_" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "showLegend" : true, "self" : "_" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataLegendTextSeparater</title>
    <meta content="text/html;charset=utf-8" http-equiv="Content-Type">
    <meta content="utf-8" http-equiv="encoding">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/6.2.0/d3.js"></script>
    <script src="../libs/statosio.js"></script>
</head>
<body>
    <script>
        d3.json( "../data/1-json-durstexpress.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile",  "desktop" ], 
                    { "showLegend" : true, "self" : "_" }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/data__legend__text__separater.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Replace character "```_```" to " " in the legend text label</div>
</body>
```
