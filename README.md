[![Build Status](https://secure.travis-ci.org/suisho/bespoke-comment-note.png?branch=master)](https://travis-ci.org/suisho/bespoke-comment-note)

# bespoke-comment-note

show comment as note

## Download

Download the [production version][min] or the [development version][max], or use a [package manager](#package-managers).

[min]: https://raw.github.com/suisho/bespoke-comment-note/master/dist/bespoke-comment-note.min.js
[max]: https://raw.github.com/suisho/bespoke-comment-note/master/dist/bespoke-comment-note.js

## Usage

First, include both `bespoke.js` and `bespoke-comment-note.js` in your page.

Then, simply include the plugin when instantiating your presentation.

```js
bespoke.from('article', {
  commentNote: true
});
```

## Package managers

### Bower

```bash
$ bower install bespoke-comment-note
```

### npm

```bash
$ npm install bespoke-comment-note
```

The bespoke-comment-note npm package is designed for use with [browserify](http://browserify.org/), e.g.

```js
require('bespoke');
require('bespoke-comment-note');
```

## Credits

This plugin was built with [generator-bespokeplugin](https://github.com/markdalgleish/generator-bespokeplugin).

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
