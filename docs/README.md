# Introduction

Optimal `babel` config for parsing and transformations.

## Install

```sh
npm install @c0rejs/babel
```

## Usage

```javascript
import { createConfig, parseAsync, transformAsync } from "@c0rejs/babel";

// parse
const ast = await parseAsync( code, createConfig() );

// transform
const { code, map } = await transformAsync( code, createConfig() );
```
