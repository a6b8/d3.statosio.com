---
sort: 5
title: A.5. showDataAsCircle
---
# showDataAsCircle

Show data as circles instead of rectangles. Only for not stacked diagram available.


## Specification

Default implementation: ```{ showDataAsCircle : false }```

### Key

| **Name**| **Alias**| **Category** |
| ```showDataAsCircle```| ```show__data_as_circle```| [Show](../options/#show) |

### Value

Allow true or false as value.

| **Default**| **Validation**| **Type** |
| ```false```| ```^(?:true|false)```| Boolean |



## Example A.

Draw data with circles

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : true, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/showDataAsCircle--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/showDataAsCircle.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : true }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : true }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - showDataAsCircle</title>
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
                    { "self" : true }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/show__data_as_circle.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Draw data with circles</div>
</body>
```
## Example B.

Draw data with bars

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : false, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/showDataAsCircle--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/showDataAsCircle.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : false }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : false }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - showDataAsCircle</title>
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
                    { "self" : false }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/show__data_as_circle.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Draw data with bars</div>
</body>
```
