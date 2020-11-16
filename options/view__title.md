---
sort: 6
title: B.1. viewTitle
---
# viewTitle

Set title content.

```note
Html styling is supported use "style" category instead for changing the look.
```


## Specification

Default implementation: ```{ viewTitle : Statosio Demo }```

### Key

| **Name**| **Alias**| **Category** |
| ```viewTitle```| ```view__title```| [View](../options/#view) |

### Value

Allow A-Z, a-b and 0-9 as value.

| **Default**| **Validation**| **Type** |
| ```"Statosio Demo"```| ```^[a-zA-Z0-9]*$```| String |



## Example A.

Change title to: "```42```"

### Output

  <div id="a">
      <script> 
          d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "42", "view__dom_id" : "a" }
)

      </script>
  </div>

Open output in a [blank window](../sources/viewTitle--example-a.html){:target="_self"}. 
Download examples [as zip](../sources/viewTitle.zip){:target="_blank"}. 

### Parameters

This dataset shows the mobile google pagerank performance score for a certain website.

| | **Value** | **Type** |
|------:|:------|:------|
| **Source** | ["../data/1-json-durstexpress.json"](../data/1-json-durstexpress.json) | String |
| **X** | ```"domain"``` | String |
| **Y** | ```[ "mobile" ]``` | Array |
| **Options** | ```{ "self" : "42" }``` | Object |


### Source Code

* Invoke Function

```javascript
d3.statosio( 
    file, 
    "domain", 
    [ "mobile" ], 
    { "self" : "42" }
)
```

* HTML Implementation

```html
<!DOCTYPE html>
<head>
    <title>d3.statosio - viewTitle</title>
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
                    { "self" : "42" }
                )
                h = document.createElement("a")
                h.setAttribute("href", "../options/view__title.html#example-a")
                h.innerText = "BACK"
                document.body.append(h)
            } )
    </script>
    <div style="display:none;">Change title to: "```42```"</div>
</body>
```