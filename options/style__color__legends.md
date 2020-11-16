---
sort: 29
title: D.4. styleColorLegends
---
# styleColorLegends

Set legend color palettes. Expect an array of "hex" values or "html" color-names.

```note
You can set as less as you want, if a color is missing it will filled with "#000000"
```


## Specification

Default implementation: ```{ styleColorLegends : ["#5186EC", "#D95040", "#F2BD42"] }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleColorLegends```| ```style__color__legends```| [Style](../options/#style) |

### Value

Allow hex values including short writing needs to with starting with #.

| **Default**| **Validation**| **Type** |
| ```["#5186EC", "#D95040", "#F2BD42"]```| ```^#([A-Fa-f0-9]{6}|[A-Fa-f0-9]{3})$```| Array |



## Example A.

Set color legend palette to: ```["yellow", "red", "green"]```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "self" : ["yellow", "red", "green"], "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorLegends--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorLegends.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "self" : ["yellow", "red", "green"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "self" : ["yellow", "red", "green"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorLegends</title>
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
                    [ "mobile",  "desktop" ], 
                    { "self" : ["yellow", "red", "green"] }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__color__legends.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Set color legend palette to: ```["yellow", "red", "green"]```</div>
</body>
```
## Example B.



### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "self" : ["#f59351", "#c9504a", "#12514c", "#2f7872", "#a6b797"], "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorLegends--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorLegends.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile **and** desktop google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile",  "desktop" ]``` | Array |
| **Options** | ```{ "self" : ["#f59351", "#c9504a", "#12514c", "#2f7872", "#a6b797"] }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile",  "desktop" ], 
    { "self" : ["#f59351", "#c9504a", "#12514c", "#2f7872", "#a6b797"] }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorLegends</title>
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
                    [ "mobile",  "desktop" ], 
                    { "self" : ["#f59351", "#c9504a", "#12514c", "#2f7872", "#a6b797"] }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/style__color__legends.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;"></div>
</body>
```
