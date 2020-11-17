---
sort: 24
title: C.10. dataSortSelection
---
# dataSortSelection

Change position of your selection. You can choose between "start", "end" and "none"

```note
The sequence is based on your selection sequence.
```


## Specification

Default implementation: ```{ dataSortSelection : none }```

### Key

| **Name**| **Alias**| **Category** |
| ```dataSortSelection```| ```data__sort__selection```| [Data](../options/#data) |

### Value

Allow "start" or "end" as value.

| **Default**| **Validation**| **Type** |
| ```"none"```| ```^(?:start|end)```| String |



## Example A.

Set selection to: ```start```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataSortSelection" : "start", "dataXSelectors" : ["orange"], "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataSortSelection--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/dataSortSelection.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "dataSortSelection" : "start", "dataXSelectors" : ["orange"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataSortSelection" : "start", "dataXSelectors" : ["orange"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataSortSelection</title>
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
                    { "dataSortSelection" : "start", "dataXSelectors" : ["orange"] }
                )
            } )
    </script>
</body>
```
## Example B.

Set selection to: ```end```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataSortSelection" : "end", "dataXSelectors" : ["orange"], "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataSortSelection--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/dataSortSelection.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "dataSortSelection" : "end", "dataXSelectors" : ["orange"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataSortSelection" : "end", "dataXSelectors" : ["orange"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataSortSelection</title>
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
                    { "dataSortSelection" : "end", "dataXSelectors" : ["orange"] }
                )
            } )
    </script>
</body>
```
