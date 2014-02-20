*This repository is a mirror of the [component](http://component.io) module [jkroso/viewport](http://github.com/jkroso/viewport). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jkroso-viewport`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# viewport

represents the browsers viewport in a more useful way

## API

```javascript
var viewport = require('viewport')

viewport.on('resize', function(){
	console.log('width: %dpx, height: %dpx', viewport.width, viewport.height)
})

viewport.on('scroll', function(){
	console.log('x: %dpx, y: %dpx', viewport.left, viewport.top)
})
```
## demo

To run the demo just download the repo run `$ make`