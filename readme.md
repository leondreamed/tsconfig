<!-- This readme is totally not copied from https://github.com/sindresorhus/tsconfig -->

# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```sh
npm install --save-dev @leondreamed/tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@leondreamed/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "baseUrl": ".",
    "rootDir": "src",
    "paths": {
      "~/*": ["./src/*"]
    }
  }
}
```
