A fork of [https://github.com/igghera/turn.js](https://github.com/igghera/turn.js)

## Usage

### JS

```js
const jQuery = ($ = require("jquery"));
const turnjs = require("turn.js");
$.extend($.fn, turnjs);

$(document).ready(() => {
  $("#flipbook").turn({
    width: "200px",
    height: "500px",
  });
});
```

### HTML

```html
<div id="flipbook">
  <div class="hard">Page 1</div>
  <div class="hard">Page 2</div>
  <div class="hard">Page 3</div>
  <div class="hard">Page 4</div>
  <div class="hard">Page 5</div>
  <div class="hard">Page 6</div>
</div>
```

For the full documentation on the library and all available options, please
refer to [https://github.com/blasten/turn.js](https://github.com/blasten/turn.js).
