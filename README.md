# CleverGo
[![Build Status](https://img.shields.io/travis/clevergo/clevergo?style=for-the-badge)](https://travis-ci.org/clevergo/clevergo)
[![Coverage Status](https://img.shields.io/coveralls/github/clevergo/clevergo?style=for-the-badge)](https://coveralls.io/github/clevergo/clevergo)
[![Go Report Card](https://goreportcard.com/badge/github.com/clevergo/clevergo?style=for-the-badge)](https://goreportcard.com/report/github.com/clevergo/clevergo)
[![Go.Dev reference](https://img.shields.io/badge/go.dev-reference-blue?logo=go&logoColor=white&style=for-the-badge)](https://pkg.go.dev/clevergo.tech/clevergo?tab=doc)
[![Release](https://img.shields.io/github/release/clevergo/clevergo.svg?style=for-the-badge)](https://github.com/clevergo/clevergo/releases)

CleverGo is a lightweight, feature rich and trie based high performance HTTP request router.

```shell
go get -u clevergo.tech/clevergo
```

![Benchmark](https://clevergo.tech/img/benchmark.png)

## Documentation

- [English](https://clevergo.tech/docs/)
- [简体中文](https://clevergo.tech/zh/docs/)
- [繁體中文](https://clevergo.tech/zh-hant/docs/)

## Features

- **High Performance:** extremely fast, see [Benchmark](https://clevergo.tech/docs/benchmark).
- **Gradual learning curve:** you can learn the entire usages by going through the [documentation](#documentation) in half an hour.
- **[Reverse Route Generation](https://clevergo.tech/docs/routing/url-generation):** allow generating URLs by named route or matched route.
- **[Route Group](https://clevergo.tech/docs/routing/route-group):** as known as subrouter.
- **Friendly to APIs:** it is easy to design RESTful APIs and versioning your APIs by route group.
- **[Middleware](https://clevergo.tech/docs/middleware):** plug middleware in route group or particular route, supports global middleware as well. Compatible with most of third-party middleware.

## Examples

Checkout [example](https://github.com/clevergo/examples) for details.

## Contribute

Contributions are welcome.

- Star it and spread the package.
- [File an issue](https://github.com/clevergo/clevergo/issues/new) to ask questions, request features or report bugs.
- Fork and make a pull request.
- Improve [documentations](https://github.com/clevergo/website).

## Credit

See [CREDIT.md](CREDIT.md).
