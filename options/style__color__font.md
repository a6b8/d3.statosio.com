---
sort: 28
title: D.3. styleColorFont
---
# styleColorFont

Set default font color. Excluding non-selection content.


## Specification

Default implementation: ```{ styleColorFont : #000000 }```

### Key

| **Name**| **Alias**| **Category** |
| ```styleColorFont```| ```style__color__font```| [Style](../options/#style) |

### Value

Allow hex values including short writing needs to with starting with #.

| **Default**| **Validation**| **Type** |
| ```"#000000"```| ```^#([A-Fa-f0-9]{6}|[A-Fa-f0-9]{3})$```| String |



## Example A.

Set default font color to: ```red```

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleColorFont" : "red", "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorFont--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorFont.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleColorFont" : "red" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleColorFont" : "red" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorFont</title>
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
                    { "styleColorFont" : "red" }
                )
            } )
    </script>
</body>
```
## Example B.

Set default font color to: ```#f66504```

### Output

  <div id="b">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleColorFont" : "#f66504", "view__dom_id" : "b" }
)

      </script>
  </div>

Open output in a [blank window](../sources/styleColorFont--example-b.html){:target="_self"}. 
Download examples [as zip](../sources/styleColorFont.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/performance.json"](../data/performance.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "styleColorFont" : "#f66504" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "styleColorFont" : "#f66504" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - styleColorFont</title>
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
                    { "styleColorFont" : "#f66504" }
                )
            } )
    </script>
</body>
```
