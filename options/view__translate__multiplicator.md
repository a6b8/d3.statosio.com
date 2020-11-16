---
sort: 14
title: B.9. viewTranslateMultiplicator
---
# viewTranslateMultiplicator

Between title, legend and diagram are spaces. These spaces gets calculated through this multiplicator.


## Specification

Default implementation: ```{ viewTranslateMultiplicator : 1.5 }```

### Key

| **Name**| **Alias**| **Category** |
| ```viewTranslateMultiplicator```| ```view__translate__multiplicator```| [View](../options/#view) |

### Value

Allow float numbers from 1.0 to 3.99.. as value.

| **Default**| **Validation**| **Type** |
| ```1.5```| ```^[1-3](.[0-9]+)?$```| Float |



## Example A.

Change distance between title, legend and diagram to: ```0.42```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 0.42, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewTranslateMultiplicator--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/viewTranslateMultiplicator.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : 0.42 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 0.42 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewTranslateMultiplicator</title>
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
                    { "self" : 0.42 }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/view__translate__multiplicator.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Change distance between title, legend and diagram to: ```0.42```</div>
</body>
```
## Example B.

Change distance between title, legend and diagram to: ```2.42```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 2.42, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewTranslateMultiplicator--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/viewTranslateMultiplicator.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : 2.42 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : 2.42 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewTranslateMultiplicator</title>
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
                    { "self" : 2.42 }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/view__translate__multiplicator.html#example-b")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Change distance between title, legend and diagram to: ```2.42```</div>
</body>
```
