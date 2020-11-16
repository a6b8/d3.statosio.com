---
sort: 11
title: B.6. viewMarginLeft
---
# viewMarginLeft

Set margin left


## Specification

Default implementation: ```{ viewMarginLeft : 60 }```

### Key

| **Name**| **Alias**| **Category** |
| ```viewMarginLeft```| ```view__margin__left```| [View](../options/#view) |

### Value

Allow positive integers and 0 as value

| **Default**| **Validation**| **Type** |
| ```60```| ```^(?:[0-9]+(?:.[0-9]+)?)?$```| Integer |



## Example A.

Set left margin to: ```0```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 0, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewMarginLeft--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/viewMarginLeft.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : 0 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 0 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewMarginLeft</title>
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
                    { "self" : 0 }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/view__margin__left.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set left margin to: ```0```</div>
</body>
```
## Example B.

Set left margin to: ```200```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 200, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewMarginLeft--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/viewMarginLeft.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : 200 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 200 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewMarginLeft</title>
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
                    { "self" : 200 }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/view__margin__left.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set left margin to: ```200```</div>
</body>
```
