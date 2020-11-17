---
sort: 17
title: C.3. dataXTextLength
---
# dataXTextLength

This value counts the length of the x range names an cut of the rest.

```note
Use the "placeholder" option for changing the cut of add-on
```


## Specification

Default implementation: ```{ dataXTextLength : 25 }```

### Key

| **Name**| **Alias**| **Category** |
| ```dataXTextLength```| ```data__x__text__length```| [Data](../options/#data) |

### Value

Allow positive integers and 0 as value

| **Default**| **Validation**| **Type** |
| ```25```| ```^(?:[0-9]+(?:.[0-9]+)?)?$```| Integer |



## Example A.

Set the maximum text label length for x range values to: ```5```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataXTextLength" : 5, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataXTextLength--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/dataXTextLength.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "dataXTextLength" : 5 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataXTextLength" : 5 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataXTextLength</title>
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
                    { "dataXTextLength" : 5 }
                )
            } )
    </script>
</body>
```
## Example B.

Set the maximum text label length for x range values to: ```18```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataXTextLength" : 18, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataXTextLength--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/dataXTextLength.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "dataXTextLength" : 18 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "dataXTextLength" : 18 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataXTextLength</title>
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
                    { "dataXTextLength" : 18 }
                )
            } )
    </script>
</body>
```
