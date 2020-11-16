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
    { "self" : "georgia", "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontFamily--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontFamily.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : "georgia" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "georgia" }
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
        d3.json( "../data/1-json-durstexpress.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile" ], 
                    { "self" : "georgia" }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__font__family.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set default font family to: ```georgia```</div>
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
    { "self" : "verdana", "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontFamily--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontFamily.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : "verdana" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "verdana" }
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
        d3.json( "../data/1-json-durstexpress.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile" ], 
                    { "self" : "verdana" }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__font__family.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set default font family to: ```verdana```</div>
</body>
```
