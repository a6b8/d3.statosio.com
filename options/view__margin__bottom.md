---
sort: 10
title: B.5. viewMarginBottom
---
# viewMarginBottom

Set margin bottom


## Specification

Default implementation: ```{ viewMarginBottom : 100 }```

### Key

| **Name**| **Alias**| **Category** |
| ```viewMarginBottom```| ```view__margin__bottom```| [View](../options/#view) |

### Value

Allow positive integers and 0 as value

| **Default**| **Validation**| **Type** |
| ```100```| ```^(?:[0-9]+(?:.[0-9]+)?)?$```| Integer |



## Example A.

Set bottom margin to: ```0```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "viewMarginBottom" : 0, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewMarginBottom--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/viewMarginBottom.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "viewMarginBottom" : 0 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "viewMarginBottom" : 0 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewMarginBottom</title>
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
                    { "viewMarginBottom" : 0 }
                )
            } )
    </script>
</body>
```
## Example B.

Set bottom margin to: ```200```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "viewMarginBottom" : 200, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewMarginBottom--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/viewMarginBottom.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "viewMarginBottom" : 200 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "viewMarginBottom" : 200 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewMarginBottom</title>
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
                    { "viewMarginBottom" : 200 }
                )
            } )
    </script>
</body>
```
