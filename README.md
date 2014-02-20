*This repository is a mirror of the [component](http://component.io) module [chrisbuttery/luhn](http://github.com/chrisbuttery/luhn). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/chrisbuttery-luhn`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# luhn

  A [Luhn (mod 10) algorithm](http://en.wikipedia.org/wiki/Luhn_algorithm) component for credit card number validation.

  Returns a boolean value.

## Installation

    $ component install chrisbuttery/luhn

## API

	var luhn = require('luhn');

	luhn.validate('4111111111111111'); // it's soooo valid right now

## License

  MIT
