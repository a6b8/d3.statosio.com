---
sort: 41
title: D.16. styleOtherRangeXTextRotation
---
# styleOtherRangeXTextRotation

Set text rotation of the x axis.


## Specification

Default implementation: ```{ styleOtherRangeXTextRotation : -45 }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleOtherRangeXTextRotation```| ```style__other__range_x_text_rotation```| [Style](../options/#style) |

### Value

Allow negative integers from -90 to -1 including 0 as value.

| **Default**| **Validation**| **Type** |
| ```-45```| ```^0|-[1-9]d*```| Integer |



## Example A.

Set x range text label rotation to: ```-90```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "styleOtherRangeXTextRotation" : -90, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleOtherRangeXTextRotation--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleOtherRangeXTextRotation.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleOtherRangeXTextRotation" : -90 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "styleOtherRangeXTextRotation" : -90 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleOtherRangeXTextRotation</title>
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
                    "name", 
                    [ "mobile" ], 
                    { "styleOtherRangeXTextRotation" : -90 }
                )
            } )
    </script>
</body>
```
## Example B.

Set x range text label rotation to: ```-20```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "styleOtherRangeXTextRotation" : -20, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleOtherRangeXTextRotation--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleOtherRangeXTextRotation.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleOtherRangeXTextRotation" : -20 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "styleOtherRangeXTextRotation" : -20 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleOtherRangeXTextRotation</title>
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
                    "name", 
                    [ "mobile" ], 
                    { "styleOtherRangeXTextRotation" : -20 }
                )
            } )
    </script>
</body>
```
