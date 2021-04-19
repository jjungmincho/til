# JavaScript Modules 

You can see an example of our shape drawing module rewritten with ES classes in our classes directory. As an example, the square.js file now contains all its functionality in a single class:

```
class Square {
  constructor(ctx, listId, length, x, y, color) {
    ...
  }

  draw() {
    ...
  }

  ...
}
```
which we then export:
```
export { Square };
Over in main.js, we import it like this:

import { Square } from './modules/square.js';
```
And then use the class to draw our square:
```
let square1 = new Square(myCanvas.ctx, myCanvas.listId, 50, 50, 100, 'blue');
square1.draw();
square1.reportArea();
square1.reportPerimeter();
```

## Reference
[JavaScript modules | JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)