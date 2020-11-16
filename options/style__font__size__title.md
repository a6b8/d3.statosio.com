---
sort: 34
title: D.9. styleFontSizeTitle
---
# styleFontSizeTitle

Set font size of title


## Specification

Default implementation: ```{ styleFontSizeTitle : 18 }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleFontSizeTitle```| ```style__font__size__title```| [Style](../options/#style) |

### Value

Allow positive integers beginning from 1 as value.

| **Default**| **Validation**| **Type** |
| ```18```| ```^[1-9]d*$```| Integer |



## Example A.

Set title font size to: ```20```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleFontSizeTitle" : 20, "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontSizeTitle--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontSizeTitle.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleFontSizeTitle" : 20 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleFontSizeTitle" : 20 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleFontSizeTitle</title>
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
                    [ "mobile" ], 
                    { "styleFontSizeTitle" : 20 }
                )
            } )
    </script>
</body>
```
## Example B.

Set title font size to: ```5```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleFontSizeTitle" : 5, "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleFontSizeTitle--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleFontSizeTitle.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleFontSizeTitle" : 5 }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleFontSizeTitle" : 5 }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleFontSizeTitle</title>
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
                    [ "mobile" ], 
                    { "styleFontSizeTitle" : 5 }
                )
            } )
    </script>
</body>
```
