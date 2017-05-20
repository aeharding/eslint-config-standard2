# eslint-config-standard2 [![travis][travis-image]][travis-url] [![npm][npm-image]][npm-url] [![downloads][downloads-image]][downloads-url] [![javascript style guide][standard-image]][standard-url]

[travis-image]: https://img.shields.io/travis/aeharding/eslint-config-standard2/master.svg
[travis-url]: https://travis-ci.org/aeharding/eslint-config-standard2
[npm-image]: https://img.shields.io/npm/v/eslint-config-standard2.svg
[npm-url]: https://npmjs.org/package/eslint-config-standard2
[downloads-image]: https://img.shields.io/npm/dm/eslint-config-standard2.svg
[downloads-url]: https://npmjs.org/package/eslint-config-standard2
[standard-image]: https://img.shields.io/badge/code_style-standard2-brightgreen.svg
[standard2-url]: https://standardjs2.com

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for [JavaScript Standard Style](http://standardjs2.com)

[![JavaScript Style Guide - Standard Style](https://cdn.rawgit.com/aeharding/standard2/master/badge.svg)](http://standardjs2.com)

## Install

This module is for advanced users. You probably want to use [`standard2`](http://standardjs2.com) instead :)

```bash
npm install eslint-config-standard2
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the JavaScript Standard Style shareable config, first run this:

```bash
npm install --save-dev eslint-config-standard2 eslint-plugin-standard2 eslint-plugin-promise eslint-plugin-import eslint-plugin-node
```

Then, add this to your .eslintrc file:

```
{
  "extends": "standard2"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

### Looking for something easier than this?

The easiest way to use JavaScript Standard Style to check your code is to use the
[`standard2`](http://standardjs2.com) package. This comes with a global
Node command line program (`standard`) that you can run or add to your `npm test` script
to quickly check your style.

## Badge

Use this in one of your projects? Include one of these badges in your readme to
let people know that your code is using the standard style.

[![js-standard2-style](https://cdn.rawgit.com/aeharding/standard2/master/badge.svg)](http://standardjs2.com)

```markdown
[![js-standard2-style](https://cdn.rawgit.com/aeharding/standard2/master/badge.svg)](http://standardjs2.com)
```

[![js-standard2-style](https://img.shields.io/badge/code%20style-standard2-brightgreen.svg)](http://standardjs.com)

```markdown
[![js-standard2-style](https://img.shields.io/badge/code%20style-standard2-brightgreen.svg)](http://standardjs.com)
```

## Learn more

For the full listing of rules, editor plugins, FAQs, and more, visit the main
[JavaScript Standard 2 Style repo](http://standardjs2.com).

## License

MIT.
