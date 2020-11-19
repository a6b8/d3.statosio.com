---
sort: 16
title: C.2. dataXSelectors
---
# dataXSelectors

Expect one or more names which are included in the x range.

```note
The selection can get formatted in the "style" category.
```


## Specification

Default implementation: ```{ dataXSelectors : [] }```

### Key

| **Name**| **Alias**| **Category** |
| ```dataXSelectors```| ```data__x__selectors```| [Data](../options/#data) |

### Value

Allow A-Z, a-b and 0-9 as value.

| **Default**| **Validation**| **Type** |
| ```[]```| ```^[a-zA-Z0-9]*$```| Array |



## Example A.

Selection is set to: ```["Data"]```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataXSelectors" : ["Data"], "showAverage" : false, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataXSelectors--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/dataXSelectors.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "dataXSelectors" : ["Data"], "showAverage" : false }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataXSelectors" : ["Data"], "showAverage" : false }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataXSelectors</title>
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
                    { "dataXSelectors" : ["Data"], "showAverage" : false }
                )
            } )
    </script>
</body>
```
## Example B.

Multiple selections are set: ```["Spock", "Data"]```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataXSelectors" : ["Spock", "Data"], "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataXSelectors--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/dataXSelectors.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "dataXSelectors" : ["Spock", "Data"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataXSelectors" : ["Spock", "Data"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataXSelectors</title>
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
                    { "dataXSelectors" : ["Spock", "Data"] }
                )
            } )
    </script>
</body>
```
