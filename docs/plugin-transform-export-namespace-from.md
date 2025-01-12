---
id: babel-plugin-transform-export-namespace-from
title: "@babel/plugin-transform-export-namespace-from"
sidebar_label: export-namespace-from
---

> **NOTE**: This plugin is included in `@babel/preset-env`, in [ES2020](https://github.com/tc39/proposals/blob/master/finished-proposals.md)

## Example

```js title="JavaScript"
export * as ns from "mod";
```

## Installation

```shell npm2yarn
npm install --save-dev @babel/plugin-transform-export-namespace-from
```

## Usage

### With a configuration file (Recommended)

```json title="babel.config.json"
{
  "plugins": ["@babel/plugin-transform-export-namespace-from"]
}
```

### Via CLI

```sh title="Shell"
babel --plugins @babel/plugin-transform-export-namespace-from script.js
```

### Via Node API

```js title="JavaScript"
require("@babel/core").transformSync("code", {
  plugins: ["@babel/plugin-transform-export-namespace-from"],
});
```

## References

- ~~[Proposal: Additional export-from statements in ES7](https://github.com/leebyron/ecmascript-more-export-from)~~ (Withdrawn)
- [ECMAScript Proposal: export ns from](https://github.com/leebyron/ecmascript-export-ns-from)
