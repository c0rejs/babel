# Introduction

Optimal `babel` config for parsing and transformations.

## Install

```sh
npm install @corejslib/babel
```

## Usage

```javascript
import { createConfig, parseAsync, transformAsync } from "@corejslib/babel";

// parse
const ast = await parseAsync( code, createConfig() );

// transform
const { code, map } = await transformAsync( code, createConfig() );
```
