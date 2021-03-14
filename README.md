# console-master
### Allows colors and adds correct time-format to console logs

_console-master is node module console logger that supports colors and correct time-format built by @Refloow for OSL-works Github projects._

## Installation

Install it from [npm](https://www.npmjs.com/package/console-master):

    $ npm install console-master
    
## Usage examples

```js

// Import module
// Import the module under the name that you like, in the example Console with capital C is used
// Importing module under the name console, will cause an error in case of using standard console.log(".");


const Console = require("console-master");

// All ussage examples
// in case of a different name chosen under which module is imported use
// yourchosenname.false("Shows bold red text"); for example

// All variants
Console.false("Shows bold red text");
Console.true("Shows bold green text");
Console.new("Shows underline gray text");
Console.info("Shows yellow text");
Console.summary("Shows cyan text");

// Errors can be shown with .fail, .err, .error
Console.fail("Shows red text");
Console.err("Shows red text");
Console.error("Shows red text");
```

## Result looks like this:

<img src="https://github.com/OSL-Works/console-master/blob/main/.github/showcase/result.png" />
