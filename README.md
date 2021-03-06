# eyeglass-highlightjs

Shim repository for [Highlight.js](http://highlightjs.org/).

This package does not follow the Highlight.js version number for NPM
consistency/semver reasons. See the changelog for what version of Highlight.js
was last added.

## Install

Install this with `npm install --save eyeglass-highlightjs`

## Usage

This module is for use with [sass-eyeglass].

You can preview the themes on the [Highlight.js demo page]

`@import highlightjs-themes/THEME_FILE` where `THEME_FILE` is any one the file
names (without `.css` extension) in the [styles/] directory of this module.

Do not include the `.css` extension -- both libsass (node-sass) and ruby sass
know how to import `.css` files and including the extension may cause them to
leave it as a regular CSS `@import` instead of inlining the contents.

## Credit

Styles are directly from the [Highlight.js] NPM package.

## Changelog

```markdown
v1.0.0 (2016-05-23)
    Updated for eyeglass 0.8.3

v0.0.1 (2016-01-13)
    Highlight.js themes from version 9.1.0
    Initial commit and npm publish
```


[Highlight.js]: http://highlightjs.org/
[Highlight.js demo page]: https://highlightjs.org/static/demo/
[sass-eyeglass]: https://github.com/sass-eyeglass/eyeglass
[styles/]: https://github.com/davidosomething/eyeglass-highlightjs/tree/master/styles
