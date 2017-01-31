9de pull request
===

A small library providing utility methods to `escape` and `unescape` HTML entities

## Installation

  npm install 9de --save

## Usage

  var nodeUtil = require('9de');
      escape = nodeUtil.escape,
      unescape = nodeUtil.unescape;

  var html = '<h1>Hello World</h1>',
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);

## Tests

  npm test
