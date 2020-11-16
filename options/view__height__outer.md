---
sort: 13
title: B.8. viewHeightOuter
---
# viewHeightOuter

Set height of the "canvas" including margin.


## Specification

Default implementation: ```{ viewHeightOuter : 300 }```

### Key

| **Name**| **Alias**| **Category** |
| ```viewHeightOuter```| ```view__height__outer```| [View](../options/#view) |

### Value

Allow positive integers beginning from 1 as value.

| **Default**| **Validation**| **Type** |
| ```300```| ```^[1-9]d*$```| Integer |



## Example A.

Set total height to: ```100```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "viewHeightOuter" : 100, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewHeightOuter--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/viewHeightOuter.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "viewHeightOuter" : 100 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "viewHeightOuter" : 100 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewHeightOuter</title>
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
                    { "viewHeightOuter" : 100 }
                )
            } )
    </script>
</body>
```
## Example B.

Set total height to: ```600```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "viewHeightOuter" : 600, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewHeightOuter--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/viewHeightOuter.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "viewHeightOuter" : 600 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "viewHeightOuter" : 600 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewHeightOuter</title>
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
                    { "viewHeightOuter" : 600 }
                )
            } )
    </script>
</body>
```
