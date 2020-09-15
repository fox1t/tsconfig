# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```
$ npm install --save-dev fox1t-tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "fox1t-tsconfig",
  "compilerOptions": {
    "outDir": "build",
    "target": "es2018",
    "lib": ["es2018"]
  }
}
```

**This project is inspired by**: [sindresorhus/tsconfig](https://github.com/sindresorhus/tsconfig)

## License

MIT © [Maksim Sinik](https://maksim.dev)
