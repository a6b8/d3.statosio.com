---
sort: 18
title: C.4. dataXTextPlaceholder
---
# dataXTextPlaceholder

Set an suffix behind a string. As a signal to the viewer, that the text was cut of.


## Specification

Default implementation: ```{ dataXTextPlaceholder : ... }```

### Key

| **Name**| **Alias**| **Category** |
| ```dataXTextPlaceholder```| ```data__x__text__placeholder```| [Data](../options/#data) |

### Value

Allow A-Z, a-b and 0-9 as value.

| **Default**| **Validation**| **Type** |
| ```"..."```| ```^[a-zA-Z0-9]*$```| String |



## Example A.

Change suffix for cut of x range text labels to: ```-----```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "-----", "dataXTextLength" : 10, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataXTextPlaceholder--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/dataXTextPlaceholder.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : "-----", "dataXTextLength" : 10 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "-----", "dataXTextLength" : 10 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataXTextPlaceholder</title>
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
                    { "self" : "-----", "dataXTextLength" : 10 }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/data__x__text__placeholder.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Change suffix for cut of x range text labels to: ```-----```</div>
</body>
```
## Example B.

Change suffix for cut of x range text labels to: ``````

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "", "dataXTextLength" : 10, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/dataXTextPlaceholder--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/dataXTextPlaceholder.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : "", "dataXTextLength" : 10 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "", "dataXTextLength" : 10 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - dataXTextPlaceholder</title>
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
                    { "self" : "", "dataXTextLength" : 10 }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/data__x__text__placeholder.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Change suffix for cut of x range text labels to: ``````</div>
</body>
```
