# preval.macro

This is a [`babel-macros`][babel-macros] macro for
[`babel-plugin-preval`][babel-plugin-preval].

Please see those projects for more information.

## Installation

This module is distributed via [npm][npm] which is bundled with [node][node] and
should be installed as one of your project's `devDependencies`:

```
npm install --save-dev babel-plugin-preval
```

You'll also need to install and configure [`babel-macros`][babel-macros] if you
haven't already.

## Usage

Once you've [configured `babel-macros`](https://github.com/kentcdodds/babel-macros/blob/master/other/docs/user.md)
you can import/require `preval.macro`. For example:

```source-js
import preval from 'preval.macro'

const one = preval`module.exports = 1 + 2 - 1 - 1`
```

**Note**:

[`babel-plugin-preval`][babel-plugin-preval] allows you to have a few more APIs
than you have with this macro, but this macro comes with all the benefits of using
[`babel-macros`][babel-macros] (which you can read about in the `babel-macros` docs).

[npm]: https://www.npmjs.com/
[node]: https://nodejs.org
[babel-macros]: https://github.com/kentcdodds/babel-macros
[babel-plugin-preval]: https://github.com/kentcdodds/babel-plugin-preval

