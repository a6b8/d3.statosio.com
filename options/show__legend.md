---
sort: 2
title: A.2. showLegend
---
# showLegend

Show or hide legend. Recommended for stacked diagrams.

```note
The size of the diagramm gets higher inside of the canvas without an legend.
```


## Specification

Default implementation: ```{ showLegend : false }```

### Key

| **Name**| **Alias**| **Category** |
| ```showLegend```| ```show__legend```| [Show](../options/#show) |

### Value

Allow true or false as value.

| **Default**| **Validation**| **Type** |
| ```false```| ```^(?:true|false)```| Boolean |



## Example A.

Show legend

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "showLegend" : true, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/showLegend--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/showLegend.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "showLegend" : true }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "showLegend" : true }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - showLegend</title>
    <meta content="text/html;charset=utf-8" http-equiv="Content-Type">
    <meta content="utf-8" http-equiv="encoding">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/6.2.0/d3.js"></script>
    <script src="../libs/statosio.js"></script>
</head>
<body>
    <script>
        d3.json( "../data/performance.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile",  "desktop" ], 
                    { "showLegend" : true }
                )
            } )
    </script>
</body>
```
## Example B.

Hide legend

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "showLegend" : false, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/showLegend--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/showLegend.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "showLegend" : false }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "showLegend" : false }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - showLegend</title>
    <meta content="text/html;charset=utf-8" http-equiv="Content-Type">
    <meta content="utf-8" http-equiv="encoding">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/6.2.0/d3.js"></script>
    <script src="../libs/statosio.js"></script>
</head>
<body>
    <script>
        d3.json( "../data/performance.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile",  "desktop" ], 
                    { "showLegend" : false }
                )
            } )
    </script>
</body>
```
