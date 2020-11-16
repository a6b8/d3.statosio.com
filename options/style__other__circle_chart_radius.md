---
sort: 40
title: D.15. styleOtherCircleChartRadius
---
# styleOtherCircleChartRadius

Set radius of circle.

```note
To show circles you need to switch to circle chart mode.
```


## Specification

Default implementation: ```{ styleOtherCircleChartRadius : 4 }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleOtherCircleChartRadius```| ```style__other__circle_chart_radius```| [Style](../options/#style) |

### Value

Allow positive integers beginning from 1 as value.

| **Default**| **Validation**| **Type** |
| ```4```| ```^[1-9]d*$```| Integer |



## Example A.

Set circle radius to: ```4```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "showDataAsCircle" : true, "styleOtherCircleChartRadius" : 4, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleOtherCircleChartRadius--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleOtherCircleChartRadius.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "showDataAsCircle" : true, "styleOtherCircleChartRadius" : 4 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "showDataAsCircle" : true, "styleOtherCircleChartRadius" : 4 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleOtherCircleChartRadius</title>
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
                    [ "mobile" ], 
                    { "showDataAsCircle" : true, "styleOtherCircleChartRadius" : 4 }
                )
            } )
    </script>
</body>
```
## Example B.

Set circle radius to: ```14```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "showDataAsCircle" : true, "styleOtherCircleChartRadius" : 14, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleOtherCircleChartRadius--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleOtherCircleChartRadius.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "showDataAsCircle" : true, "styleOtherCircleChartRadius" : 14 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "showDataAsCircle" : true, "styleOtherCircleChartRadius" : 14 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleOtherCircleChartRadius</title>
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
                    [ "mobile" ], 
                    { "showDataAsCircle" : true, "styleOtherCircleChartRadius" : 14 }
                )
            } )
    </script>
</body>
```
