---
sort: 0 # follow a certain sequence of letters or numbers
title: Client-side (.js)
---

# Client-side (.js)

## Steps

### 1: Load D3
Load d3.js
```html
<script src="../d3.js"></script>
```

### 2: Load Statosio
Load statosio.js after d3.
```html
<script src="../statosio.js"></script>
```

### 3: Load Dataset
d3.js expect a json array with object in it: [{},{}...]
```javascript
d3.json( "./dataset.json" )
    .then( ( file ) => {

    } 
)
```

### 4: Create Diagram
Load diagram
```javascript
d3.statosio( dataset, xRange, yRange, options = {} )
```

## Full Example

<div id="bar">
    <script> 
        d3.statosio( 
            file, 
            "name", 
            [ "mobile" ], 
            { "showAverage" : false, "viewDomId" : "bar" }
        )
    </script>
</div>


```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - showAverage</title>
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
                    "name", 
                    [ "mobile" ], 
                    { "showAverage" : false }
                )
            } )
    </script>
</body>
```
[Download Source Code as .zip](../sources/showAverage.zip)
