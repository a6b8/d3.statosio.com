---
sort: 36
title: D.11. styleFontFormatSelectors
---
# styleFontFormatSelectors

Set format of content use "Html" Syntax ("bold", "underline", "normal" etc.). 


## Specification

Default implementation: ```{ styleFontFormatSelectors : ["bold", "normal"] }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleFontFormatSelectors```| ```style__font__format__selectors```| [Style](../options/#style) |

### Value

Allow "bold", "normal" and "underline" as value.

| **Default**| **Validation**| **Type** |
| ```["bold", "normal"]```| ```^(?:bold|normal|underline)```| Array |



## Example A.

Set font format of selection x range text labels to: ```["normal", "bold"]```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "styleFontFormatSelectors" : ["normal", "bold"], "dataXSelectors" : ["orange"], "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontFormatSelectors--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontFormatSelectors.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleFontFormatSelectors" : ["normal", "bold"], "dataXSelectors" : ["orange"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "styleFontFormatSelectors" : ["normal", "bold"], "dataXSelectors" : ["orange"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleFontFormatSelectors</title>
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
                    { "styleFontFormatSelectors" : ["normal", "bold"], "dataXSelectors" : ["orange"] }
                )
            } )
    </script>
</body>
```
## Example B.

Set font format of selection x range text labels to: ```["bold", "normal"]```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "styleFontFormatSelectors" : ["bold", "normal"], "dataXSelectors" : ["orange"], "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontFormatSelectors--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontFormatSelectors.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleFontFormatSelectors" : ["bold", "normal"], "dataXSelectors" : ["orange"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "styleFontFormatSelectors" : ["bold", "normal"], "dataXSelectors" : ["orange"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleFontFormatSelectors</title>
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
                    { "styleFontFormatSelectors" : ["bold", "normal"], "dataXSelectors" : ["orange"] }
                )
            } )
    </script>
</body>
```
