# Vector2d.js

Another vector library

All functions prefixed with `_` are mutators and will alter the vector in place.

All fucntions not prefixed with an `_` will return a new vector or a scalar value.


## Creating a Vector

This object can be created in two ways:

### Cartesian coordinates

```js

var v2d = require( "vector2d.js" );
// x, y values to instatiate
var vec = v2d.xy( 20, 30 );
```

### Polar coordinates

```js

var v2d = require( "vector2d.js" );
// magnitude, angle of rotation
var vec = v2d.polar( 30, 87 );
```

Both methods for creating the object will produce the same object.