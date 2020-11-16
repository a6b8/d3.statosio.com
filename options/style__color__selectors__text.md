---
sort: 32
title: D.7. styleColorSelectorsText
---
# styleColorSelectorsText

Colorize the font of the selection. Use "hex" values or "html" color-names.


## Specification

Default implementation: ```{ styleColorSelectorsText : ["#000000", "#000000"] }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleColorSelectorsText```| ```style__color__selectors__text```| [Style](../options/#style) |

### Value

Allow hex values including short writing needs to with starting with #.

| **Default**| **Validation**| **Type** |
| ```["#000000", "#000000"]```| ```^#([A-Fa-f0-9]{6}|[A-Fa-f0-9]{3})$```| Array |



## Example A.

Set font color of selection and others to: ```["yellow", "grey"]```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "styleColorSelectorsText" : ["yellow", "grey"], "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorSelectorsText--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorSelectorsText.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "styleColorSelectorsText" : ["yellow", "grey"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "styleColorSelectorsText" : ["yellow", "grey"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorSelectorsText</title>
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
                    [ "mobile",  "desktop" ], 
                    { "styleColorSelectorsText" : ["yellow", "grey"] }
                )
            } )
    </script>
</body>
```
## Example B.

Set font color of selection and others to: ```["#f59351", "#a6b797"]```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "styleColorSelectorsText" : ["#f59351", "#a6b797"], "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorSelectorsText--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorSelectorsText.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "styleColorSelectorsText" : ["#f59351", "#a6b797"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "styleColorSelectorsText" : ["#f59351", "#a6b797"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorSelectorsText</title>
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
                    [ "mobile",  "desktop" ], 
                    { "styleColorSelectorsText" : ["#f59351", "#a6b797"] }
                )
            } )
    </script>
</body>
```
