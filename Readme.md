*This repository is a mirror of the [component](http://component.io) module [component/touchaction-property](http://github.com/component/touchaction-property). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-touchaction-property`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# touchaction-property

  Returns &quot;touchAction&quot;, &quot;msTouchAction&quot;, or null.
  See: http://msdn.microsoft.com/en-us/library/windows/apps/hh767313.aspx

## Installation

  Install with [component(1)](http://component.io):

    $ component install component/touchaction-property

## API

``` js
var touchAction = require('touchaction-property');

if (touchAction) {
  document.body.style[touchAction] = 'none';
}
```

## License

  MIT
