# TradeZap

[![npm version][npm-badge]][npm-url]
[![npm downloads][downloads-badge]][npm-url]
[![CI][ci-badge]][ci-url]
[![TypeScript][typescript-badge]][typescript-url]

_⚡ Get trading data in a zap_

TradeZap CLI tool keeps your trading data easily up to date.

## Usage

- `npm i -D tradezap` or `bun add -D tradezap`
- Define which trading data you want in `tradezap.config.ts` file ([example](example/binance/tradezap.config.ts))
- Run `npx tradezap` or `bunx tradezap`
- Trading data are ready to use 📈

## Data Providers

Currently supported data providers:

- [Binance](https://www.binance.com/)

## Development

Requirement - [Bun v1.0.2+](https://bun.sh)

_Easily set up a local development environment!_

- clone
- `bun i`
- `bun run dev`

_Start coding!_

## Contributing

All contributions are welcome!

[npm-url]: https://www.npmjs.com/package/tradezap
[npm-badge]: https://img.shields.io/npm/v/tradezap.svg
[downloads-badge]: https://img.shields.io/npm/dm/tradezap.svg?color=blue
[ci-badge]: https://github.com/ocignis/tradezap/actions/workflows/CI.yml/badge.svg
[ci-url]: https://github.com/ocignis/tradezap/actions/workflows/CI.yml
[typescript-badge]: https://badges.frapsoft.com/typescript/code/typescript.svg?v=101
[typescript-url]: https://github.com/microsoft/TypeScript
