<p align="center">
  <big><strong>Cardano REST</strong></big>
</p>

<p align="center">
  <img width="200" src=".github/images/cardano-logo.png"/>
</p>

<p align="center">
  <!--
  <a href="https://github.com/input-output-hk/cardano-rest/releases"><img src="https://img.shields.io/github/release-pre/input-output-hk/cardano-rest.svg?style=for-the-badge" /></a>
  <a href="https://buildkite.com/input-output-hk/cardano-rest"><img src="https://img.shields.io/buildkite/7ea3dac7a16f066d8dfc8f426a9a9f7a2131e899cd96c444cf/master?label=BUILD&style=for-the-badge"/></a>
  <a href="https://buildkite.com/input-output-hk/cardano-rest-nightly"><img src="https://img.shields.io/buildkite/59ea9363b8526e867005ca8839db47715bc5f661f36e490143/master?label=BENCHMARK&style=for-the-badge" /></a>
  <a href="https://travis-ci.org/input-output-hk/cardano-rest"><img src="https://img.shields.io/travis/input-output-hk/cardano-rest.svg?label=DOCS&style=for-the-badge" /></a>
  <a href="https://coveralls.io/github/input-output-hk/cardano-rest?branch=HEAD"><img src="https://img.shields.io/coveralls/github/input-output-hk/cardano-rest/HEAD?style=for-the-badge" /></a>
  -->
</p>

<hr/>

## Overview

Cardano REST provides a set of APIs for interacting with on-chain data
through JSON over HTTP.

:warning: These APIs are now considered **legacy** and new users should instead
look into [cardano-graphql](https://github.com/input-output-hk/cardano-graphql).

## Getting Started

1. Clone the repository.

```
$ git clone git@github.com:input-output-hk/cardano-rest.git
$ cd cardano-rest
```

2. Start a `cardano-node`, `cardano-db-sync`, `postgresql` and `cardano-rest` components using Docker:

```
$ NETWORK=testnet docker-compose up
```

3. Query the API :tada:

```
$ curl http://localhost:8100/api/txs/last 
```

For more information, have a look at the [Wiki :book:](https://github.com/input-output-hk/cardano-rest/wiki).

## How to install (Linux / Mac OS / Docker)

See **Installation Instructions** for each available [release](https://github.com/input-output-hk/cardano-rest/releases).

For Docker users, jump directly to [Using Docker](https://github.com/input-output-hk/cardano-rest/wiki/Docker).

## How to build from sources

See [Wiki - Building](https://github.com/input-output-hk/cardano-rest/wiki/Building)

## How to test

See [Wiki - Testing](https://github.com/input-output-hk/cardano-rest/wiki/Testing)

## API Documentations

- [API Documentation (cardano-explorer-api)](https://input-output-hk.github.io/cardano-rest/explorer-api)
- [API Documentation (cardano-submit-api)](https://input-output-hk.github.io/cardano-rest/submit-api)

<hr/>

<p align="center">
  <a href="https://github.com/input-output-hk/cardano-rest/blob/master/LICENSE"><img src="https://img.shields.io/github/license/input-output-hk/cardano-rest.svg?style=for-the-badge" /></a>
</p>
