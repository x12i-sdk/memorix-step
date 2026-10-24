# @x12i/memorix-step usage example

Run one step. Code and model calls share the same context and outcome. The caller supplies the model callback.

This consuming application demonstrates **run a model-assisted step with an explicit local callback** using the published npm package, pinned to `0.1.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Run code through the common Memorix step context.
- Run a model step using a callback supplied by the caller.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/memorix-step)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
