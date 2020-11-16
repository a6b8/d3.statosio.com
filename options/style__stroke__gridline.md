---
sort: 38
title: D.13. styleStrokeGridline
---
# styleStrokeGridline

Set stroke weight of gridline.


## Specification

Default implementation: ```{ styleStrokeGridline : 2 }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleStrokeGridline```| ```style__stroke__gridline```| [Style](../options/#style) |

### Value

Allow positive integers beginning from 1 as value.

| **Default**| **Validation**| **Type** |
| ```2```| ```^[1-9]d*$```| Integer |



## Example A.

Set stroke weight of gridline to: ```2```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 2, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleStrokeGridline--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleStrokeGridline.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : 2 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 2 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleStrokeGridline</title>
    <meta content="text/html;charset=utf-8" http-equiv="Content-Type">
    <meta content="utf-8" http-equiv="encoding">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/6.2.0/d3.js"></script>
    <script src="../libs/statosio.js"></script>
</head>
<body>
    <script>
        d3.json( "../data/1-json-durstexpress.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile" ], 
                    { "self" : 2 }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__stroke__gridline.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set stroke weight of gridline to: ```2```</div>
</body>
```
## Example B.

Set stroke weight of gridline to: ```14```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 14, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleStrokeGridline--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleStrokeGridline.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : 14 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 14 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleStrokeGridline</title>
    <meta content="text/html;charset=utf-8" http-equiv="Content-Type">
    <meta content="utf-8" http-equiv="encoding">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/6.2.0/d3.js"></script>
    <script src="../libs/statosio.js"></script>
</head>
<body>
    <script>
        d3.json( "../data/1-json-durstexpress.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile" ], 
                    { "self" : 14 }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__stroke__gridline.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set stroke weight of gridline to: ```14```</div>
</body>
```