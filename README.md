# TSLint Config Semi-Standard

[![Build Status](https://travis-ci.org/bukalapak/tslint-config-semistandard.svg?branch=master)](https://travis-ci.org/bukalapak/tslint-config-semistandard)
[![NPM version](https://img.shields.io/npm/v/tslint-config-semistandard.svg?style=flat)](https://npmjs.org/package/tslint-config-semistandard)
[![NPM downloads](https://img.shields.io/npm/dm/tslint-config-semistandard.svg?style=flat)](https://npmjs.org/package/tslint-config-semistandard)
[![js-semistandard-style](https://img.shields.io/badge/code%20style-semistandard-brightgreen.svg)](https://github.com/bukalapak/tslint-config-semistandard)

A [TSLint config](https://palantir.github.io/tslint/usage/tslint-json/) for [JavaScript Standard Style](http://standardjs.com/) with semicolons.

## Installation

```sh
npm install tslint-config-semistandard --save-dev
```

## Usage

In `tslint.json`:

```json
{
  "extends": "tslint-config-semistandard"
}
```

**P.S.** Some TSLint rules may require the use of `--type-check` (and `--project`).

### Rules

* Semicolons
* [TSLint Config Standard](https://www.npmjs.com/package/tslint-config-standard)

