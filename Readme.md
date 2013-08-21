
# redraw

  Force a redraw on an element. This can sometimes be useful to force transitions to run instead of letting the browser optimize them out. Obviously, this should be a last-ditch measure.

## Installation

    $ component install ianstormtaylor/redraw

## Example
  
```js
var redraw = require('redraw');
redraw(el);
```

## API

### redraw(el)
  Force a redraw on a given `el`.

## License

  MIT
