*This repository is a mirror of the [component](http://component.io) module [yields/reduce](http://github.com/yields/reduce). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-reduce`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# reduce

  reduce anything

## Installation

  Install with [component(1)](http://component.io):

    $ component install yields/reduce

## Example

```js
assert(3 == reduce({ a: 1, b: 2 }, sum, 0));
assert(3 == reduce([1, 2], sum, 0));
assert(198 == reduce('abc', sum, 0));
```

## License

  MIT
