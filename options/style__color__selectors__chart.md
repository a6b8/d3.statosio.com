---
sort: 31
title: D.6. styleColorSelectorsChart
---
# styleColorSelectorsChart

Colorize the chart of the selection. Use "hex" values or "html" color-names.


## Specification

Default implementation: ```{ styleColorSelectorsChart : ["#EE752F", "#5186EC"] }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleColorSelectorsChart```| ```style__color__selectors__chart```| [Style](../options/#style) |

### Value

Allow hex values including short writing needs to with starting with #.

| **Default**| **Validation**| **Type** |
| ```["#EE752F", "#5186EC"]```| ```^#([A-Fa-f0-9]{6}|[A-Fa-f0-9]{3})$```| Array |



## Example A.

Set palette to: ```["yellow", "red", "green"]```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "self" : ["yellow", "red", "green"], "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorSelectorsChart--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorSelectorsChart.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "self" : ["yellow", "red", "green"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "self" : ["yellow", "red", "green"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorSelectorsChart</title>
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
                    { "self" : ["yellow", "red", "green"] }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__color__selectors__chart.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set palette to: ```["yellow", "red", "green"]```</div>
</body>
```
## Example B.

Set palette to: ```["#f59351", "#c9504a", "#12514c"]```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "self" : ["#f59351", "#c9504a", "#12514c"], "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorSelectorsChart--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorSelectorsChart.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "self" : ["#f59351", "#c9504a", "#12514c"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "self" : ["#f59351", "#c9504a", "#12514c"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorSelectorsChart</title>
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
                    { "self" : ["#f59351", "#c9504a", "#12514c"] }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__color__selectors__chart.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set palette to: ```["#f59351", "#c9504a", "#12514c"]```</div>
</body>
```
