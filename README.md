<h1 align="center">
  <samp>xxx's ESLint Config</samp>
</h1>

## Usage

### Install

```bash
pnpm add -D eslint @ohxxx/eslint-config
```

### Configure 

`.eslintrc.json`

```json5
{
  "extends": "@ohxxx",
  "rules": {
    // ...overrides
  }
}
```

`package.json`

```json5
{
  "scripts": {
    "lint": "eslint . --fix"
  }
}
```

## Refs

This package is based on [@antfu/eslint-config](https://github.com/antfu/eslint-config) configuration and configured according to personal preferences