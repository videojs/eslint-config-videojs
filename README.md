# video.js ESLint Shareable Config

[![travis][travis-image]][travis-url]

An ESLint [Shareable Config][shareable-configs] for [video.js Standard Style][videojs-standard].

_This package is for advanced users. If you only want the [video.js Standard Style][videojs-standard] program to check your code, use that instead!_

## Install

```bash
npm install eslint-config-videojs
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.

You can learn more about [Shareable Configs][shareable-configs] on the official ESLint website.

To use the video.js Standard Style shareable config, first run this:

```bash
npm install eslint-config-videojs
```

Then, add this to your .eslintrc file:

```json
{
  "extends": "videojs"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your `.eslintrc` file.

## License

Apache-2.0. Copyright (c) [Brightcove, Inc.][bcov]

This project is based on [`eslint-config-standard`][eslint-config-standard], which is licensed under the MIT license and copyright (c) Feross Aboukhadijeh.

[bcov]: https://www.brightcove.com/
[eslint-config-standard]: https://github.com/feross/eslint-config-standard
[shareable-configs]: http://eslint.org/docs/developer-guide/shareable-configs
[travis-image]: https://img.shields.io/travis/videojs/eslint-config-videojs.svg?style=flat
[travis-url]: https://travis-ci.org/videojs/eslint-config-videojs
[videojs-standard]: https://github.com/videojs/standard
