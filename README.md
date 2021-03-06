# an-array-of-spanish-words

An array of ~250,000 Spanish words. Works with Node and Browserify.

I found the list in this repo: https://github.com/ManiacDC/TypingAid. I'm not
sure of it's origin, but it's the most extensive Spanish word list I could find.

## Programmatic Usage

To use the module in Javascript code, install it locally:

```sh
npm install an-array-of-spanish-words --save
```

Then:

```js
var words = require("an-array-of-spanish-words")
var funWords = words.filter(word => !!word.match(/^fun/i))
console.log(funWords)
```

## Command Line Usage

There's a CLI that prints all words to STDOUT. Install it globally:

```sh
npm i -g an-array-of-spanish-words
palabras | grep queso
```

## See Also

- [an-array-of-english-words](https://github.com/zeke/an-array-of-english-words)
- [an-array-of-french-words](https://github.com/zeke/an-array-of-french-words)

## Dependencies

None

## Dev Dependencies

- [byline](https://github.com/jahewson/node-byline): simple line-by-line stream reader
- [lodash.uniq](https://github.com/lodash/lodash): The lodash method `_.uniq` exported as a module.


## License

MIT

_Generated by [package-json-to-readme](https://github.com/zeke/package-json-to-readme)_
