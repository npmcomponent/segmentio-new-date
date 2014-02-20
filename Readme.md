*This repository is a mirror of the [component](http://component.io) module [segmentio/new-date](http://github.com/segmentio/new-date). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-new-date`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# new-date

  Create a new Date, accepting more input types than normal, like Unix timestamps.

## Installation

    $ component install segmentio/new-date

## API

### newDate(Date|String|Number)

  Returns a new Date object created from the input. The input can be:

  * Date objects
  * [date strings](https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Global_Objects/Date/parse)
  * millisecond numbers
  * second numbers
  * millisecond strings
  * second strings

```js
var newDate = require('new-date');

newDate(new Date);
newDate('Wed, 09 Aug 1995 00:00:00 GMT');
newDate('Aug 9, 1995');
newDate('2011-10-10T14:48:00');
newDate(1363288923637);
newDate(1363288923);
newDate('1363288923637');
newDate('1363288923');
```

## License

  MIT
