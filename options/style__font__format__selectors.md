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
    "domain", 
    [ "mobile" ], 
    { "self" : ["normal", "bold"], "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontFormatSelectors--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontFormatSelectors.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : ["normal", "bold"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : ["normal", "bold"] }
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
        d3.json( "../data/1-json-durstexpress.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile" ], 
                    { "self" : ["normal", "bold"] }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__font__format__selectors.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set font format of selection x range text labels to: ```["normal", "bold"]```</div>
</body>
```
## Example B.

Set font format of selection x range text labels to: ```["bold", "normal"]```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : ["bold", "normal"], "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontFormatSelectors--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontFormatSelectors.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : ["bold", "normal"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : ["bold", "normal"] }
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
        d3.json( "../data/1-json-durstexpress.json" )
            .then( ( file ) => {
                d3.statosio( 
                    file, 
                    "domain", 
                    [ "mobile" ], 
                    { "self" : ["bold", "normal"] }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__font__format__selectors.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set font format of selection x range text labels to: ```["bold", "normal"]```</div>
</body>
```
