---
sort: 23
title: C.9. dataSortByNames
---
# dataSortByNames

Here you can set type of sorting. You can choose between "ascending" and "decending"


## Specification

Default implementation: ```{ dataSortByNames : ascending }```

### Key

| **Name**| **Alias**| **Category** |
| ```dataSortByNames```| ```data__sort__by__names```| [Data](../options/#data) |

### Value

Allow "ascending" or "decending" as value.

| **Default**| **Validation**| **Type** |
| ```"ascending"```| ```^(?:ascending|decending)```| String |



## Example A.

Set sequence to: ```ascending```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile",  "desktop" ], 
    { "dataSortCurrent" : "names", "dataSortByNames" : "ascending", "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataSortByNames--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/dataSortByNames.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "dataSortCurrent" : "names", "dataSortByNames" : "ascending" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile",  "desktop" ], 
    { "dataSortCurrent" : "names", "dataSortByNames" : "ascending" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataSortByNames</title>
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
                    [ "mobile",  "desktop" ], 
                    { "dataSortCurrent" : "names", "dataSortByNames" : "ascending" }
                )
            } )
    </script>
</body>
```
## Example B.

Set sequence to: ```decending```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile",  "desktop" ], 
    { "dataSortCurrent" : "names", "dataSortByNames" : "decending", "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataSortByNames--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/dataSortByNames.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "dataSortCurrent" : "names", "dataSortByNames" : "decending" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile",  "desktop" ], 
    { "dataSortCurrent" : "names", "dataSortByNames" : "decending" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataSortByNames</title>
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
                    [ "mobile",  "desktop" ], 
                    { "dataSortCurrent" : "names", "dataSortByNames" : "decending" }
                )
            } )
    </script>
</body>
```
