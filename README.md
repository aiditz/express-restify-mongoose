# express-restify-mongoose

Easily create a flexible REST interface for mongoose models.

[![Build Status](https://travis-ci.org/florianholzapfel/express-restify-mongoose.png)](https://travis-ci.org/florianholzapfel/express-restify-mongoose)
[![Coverage Status](https://coveralls.io/repos/florianholzapfel/express-restify-mongoose/badge.svg?branch=master&service=github)](https://coveralls.io/github/florianholzapfel/express-restify-mongoose?branch=master)
[![NPM version](https://badge.fury.io/js/express-restify-mongoose.png)](http://badge.fury.io/js/express-restify-mongoose)
[![Dependencies](https://david-dm.org/florianholzapfel/express-restify-mongoose.png)](https://david-dm.org/florianholzapfel/express-restify-mongoose)

## Getting started

> **From 1.0.0 onwards, the library is only compatible with mongoose >= 4. For mongoose 3.x compatibility, use the 0.7.x branch.**

```sh
npm install express-restify-mongoose --save
```

## Documentation

[https://florianholzapfel.github.io/express-restify-mongoose/](https://florianholzapfel.github.io/express-restify-mongoose/)


## Changed by Aiditz

1. Removed deprecated `POST /Model/:id`, `PUT /Model/:id` endpoints.

1. Pass model-related options via `model.restifyOptions` instead of `serve()` function's argument.

1. Added an option `autoGenerateUrlPrefixes`. Defaults - `true`.