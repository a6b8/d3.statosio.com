---
sort: 9
title: B.4. viewMarginRight
---
# viewMarginRight

Set margin right


## Specification

Default implementation: ```{ viewMarginRight : 40 }```

### Key

| **Name**| **Alias**| **Category** |
| ```viewMarginRight```| ```view__margin__right```| [View](../options/#view) |

### Value

Allow positive integers and 0 as value

| **Default**| **Validation**| **Type** |
| ```40```| ```^(?:[0-9]+(?:.[0-9]+)?)?$```| Integer |



## Example A.

Set right margin to: ```0```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "viewMarginRight" : 0, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewMarginRight--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/viewMarginRight.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "viewMarginRight" : 0 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "viewMarginRight" : 0 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewMarginRight</title>
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
                    { "viewMarginRight" : 0 }
                )
            } )
    </script>
</body>
```
## Example B.

Set right margin to: ```200```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "viewMarginRight" : 200, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewMarginRight--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/viewMarginRight.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "viewMarginRight" : 200 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "viewMarginRight" : 200 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewMarginRight</title>
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
                    { "viewMarginRight" : 200 }
                )
            } )
    </script>
</body>
```
