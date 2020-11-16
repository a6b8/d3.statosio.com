---
sort: 1 # follow a certain sequence of letters or numbers
---

# Client-side (Browser)

```javascript
d3.jumpstart( 
    file, 
    'x_key', 
    [ y_keys, ... ], 
    {} 
) 
```


# Example

```html
<!DOCTYPE html>
<head>
    <meta content='text/html;charset=utf-8' http-equiv='Content-Type'>
    <meta content='utf-8' http-equiv='encoding'>
    	<script src='./libs/d3.js'></script>
<script src='./libs/jumpstart.js'></script>
</head>
<body>
    
    <script>
        d3.json( './data/1-json-durstexpress.json' )
            .then( ( file ) => {
                d3.jumpstart( 
                    file, 
                    'domain', 
                    [ 'mobile', 'desktop' ], 
                    {} 
                ) 
            } )

    </script>
</body>
```

