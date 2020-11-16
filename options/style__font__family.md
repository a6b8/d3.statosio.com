---
sort: 35
title: D.10. styleFontFamily
---
# styleFontFamily

Set default font family


## Specification

Default implementation: ```{ styleFontFamily : arial }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleFontFamily```| ```style__font__family```| [Style](../options/#style) |

### Value

Allow "arial", "times" and "helvetica" as value

| **Default**| **Validation**| **Type** |
| ```"arial"```| ```^(?:arial|times|helvetica)```| String |



## Example A.

Set default font family to: ```georgia```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleFontFamily" : "georgia", "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontFamily--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontFamily.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleFontFamily" : "georgia" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleFontFamily" : "georgia" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleFontFamily</title>
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
                    { "styleFontFamily" : "georgia" }
                )
            } )
    </script>
</body>
```
## Example B.

Set default font family to: ```verdana```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleFontFamily" : "verdana", "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontFamily--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontFamily.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleFontFamily" : "verdana" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleFontFamily" : "verdana" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleFontFamily</title>
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
                    { "styleFontFamily" : "verdana" }
                )
            } )
    </script>
</body>
```
