# preact-tsc-template

## Documentation

-   This is a forked version of typescript template for
    [preact-cli](https://github.com/developit/preact-cli).
-   [For Preact](https://preactjs.com/): General information about how to work
    with Preact, not specific to this template

## Usage

```bash
$ npm install -g preact-cli
$ preact create kencyke/preact-tsc-template my-project
$ cd my-project
$ npm run start
```

Development server runs on port `8080`. If the default port is already in use on
your machine it will start the development server on a random port.

## Commands

-   `npm run dev`: Run a development, HMR server

-   `npm run build`: Production-ready build

-   `npm run lint`: Pass TypeScript files using TSLint

-   `npm run test`: Run Jest and
    [`preact-render-spy`](https://github.com/mzgoddard/preact-render-spy) for
    your tests

### How to Test

The `typescript` template provides a basic test setup with Jest and
[`preact-render-spy`](https://github.com/mzgoddard/preact-render-spy). You are
free to change preact-render-spy with any other assertion library. The advantage
of it is that it supports a similiar terminology and feature set as the Enzyme
library for testing React applications.
