# Aleph1-Layout &middot; [Demo Page](https://avrahamcool.github.io/aleph1-layout/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Issues](https://img.shields.io/github/issues/avrahamcool/aleph1-layout.svg?style=flat)](https://github.com/avrahamcool/aleph1-layout/issues)
[![NPMVersion](https://img.shields.io/npm/v/aleph1-layout.svg?style=flat)](https://www.npmjs.com/package/aleph1-layout)
[![NPMDownloads](https://img.shields.io/npm/dt/aleph1-layout.svg?style=flat)](https://www.npmjs.com/package/aleph1-layout) 
[![NPMSize](https://img.shields.io/bundlephobia/min/aleph1-layout.svg?style=flat)](https://www.npmjs.com/package/aleph1-layout)
[![DeepScan grade](https://deepscan.io/api/teams/5394/projects/7207/branches/68617/badge/grade.svg)](https://deepscan.io/dashboard#view=project&tid=5394&pid=7207&bid=68617)

Aleph1-Layout is a minimalist responsive layout framework (written in SASS) that provides helpful, browser-consistent helper class for flex layout.


## Installing / Getting started

```shell
yarn add aleph1-layout
```
or
```shell
npm install aleph1-layout
```
now you can use the output from `dist\main.min.css`, or use the `src\scss\main.scss` directly.

in an aurelia app just use `import 'aleph1-layout';` in your `app.ts` file.

every [variable listed here](https://github.com/avrahamcool/aleph1-layout/blob/master/src/scss/base/_variables.scss) can be overridden.

## Developing & Prerequisites

make sure you have `http-server` installed globally.
```shell
yarn global add http-server
```
or
```shell
npm install -g http-server
```

```shell
git clone https://github.com/avrahamcool/aleph1-layout.git
cd aleph1-layout/
yarn
```

then simply run `yarn test` or `npm test` to compile the sass and run the demo page.

run `yarn watch` or `npm watch` to run sass watch on the entire project.

## Licensing

The code is open source and available under the [MIT License](LICENSE.md).

Built and maintained by [Essoudry Avraham](https://github.com/avrahamcool)