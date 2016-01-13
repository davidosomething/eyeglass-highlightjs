# eyeglass-highlightjs

Shim repository for [Highlight.js](http://highlightjs.org/).

This package does not follow the Highlight.js version number for NPM
consistency/semver reasons. See the changelog for what version of Highlight.js
was last added.

## Install

Install this with `npm install --save eyeglass-highlightjs`

## Usage

This module is for use with [sass-eyeglass].

`@import highlightjs-themes/THEME_FILE` where `THEME_FILE` is any one the files
in the `style/` directory of this module.

Do not include the `.css` extension -- both libsass (node-sass) and ruby sass
know how to import `.css` files and including the extension may cause them to
leave it as a regular CSS `@import` instead of inlining the contents.

You can preview the themes on the [Highlight.js demo page]

## Credit

Styles are directly from the [Highlight.js] NPM package.

## Changelog

```
v0.0.1 (2016-01-13)
    Highlight.js themes from version 9.1.0
    Initial commit and npm publish
```


[Highlight.js]: http://highlightjs.org/
[Highlight.js demo page]: https://highlightjs.org/static/demo/
[sass-eyeglass]: https://github.com/sass-eyeglass/eyeglass

