---
sort: 7
title: B.2. viewDomId
---
# viewDomId

Set id from the <div> Element which holds the d3 content inside.


## Specification

Default implementation: ```{ viewDomId : d3_statosio }```

### Key

| **Name**| **Alias**| **Category** |
| ```viewDomId```| ```view__dom_id```| [View](../options/#view) |

### Value

Allow A-Z, a-b and 0-9 as value, use _ for space.

| **Default**| **Validation**| **Type** |
| ```"d3_statosio"```| ```^[a-zA-Z0-9_]*$```| String |



## Example A.

Insert SVG into the DOM Element with the id: "```findMe```"

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "viewDomId" : "findMe", "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewDomId--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/viewDomId.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"name"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "viewDomId" : "findMe" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "name", 
    [ "mobile" ], 
    { "viewDomId" : "findMe" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewDomId</title>
    <meta content="text/html;charset=utf-8" http-equiv="Content-Type">
    <meta content="utf-8" http-equiv="encoding">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/6.2.0/d3.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/statosio/0.9/statosio.js"></script>
</head>
<body>
    <script>
        d3.json( "../data/performance.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "name", 
                    [ "mobile" ], 
                    { "viewDomId" : "findMe" }
                )
            } )
    </script>
</body>
```
