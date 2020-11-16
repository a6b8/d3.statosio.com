---
sort: 30
title: D.5. styleColorGridline
---
# styleColorGridline

Set the gridline color. Use "hex" value or "html" color-names.


## Specification

Default implementation: ```{ styleColorGridline : #E5E5E5 }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleColorGridline```| ```style__color__gridline```| [Style](../options/#style) |

### Value

Allow hex values including short writing needs to with starting with #.

| **Default**| **Validation**| **Type** |
| ```"#E5E5E5"```| ```^#([A-Fa-f0-9]{6}|[A-Fa-f0-9]{3})$```| String |



## Example A.

Set gridline value to: ```yellow```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "yellow", "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorGridline--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorGridline.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : "yellow" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "yellow" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorGridline</title>
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
                    { "self" : "yellow" }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__color__gridline.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set gridline value to: ```yellow```</div>
</body>
```
## Example B.

Set gridline value to: ```#f59351```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "#f59351", "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorGridline--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorGridline.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : "#f59351" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "#f59351" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorGridline</title>
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
                    { "self" : "#f59351" }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__color__gridline.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set gridline value to: ```#f59351```</div>
</body>
```