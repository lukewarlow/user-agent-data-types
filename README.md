# User Agent Data Types

[![npm](https://img.shields.io/npm/v/user-agent-data-types.svg?style=flat-square)](https://www.npmjs.com/package/user-agent-data-types)

Type definition for [`navigator.userAgentData`](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/userAgentData)

### Install

```shell
$ npm i -D user-agent-data-types
```

### tsconfig.json

`user-agent-data-types` needs to be added to `types` because it uses _ambient_ types that modify the global `navigator` type.

```json
{
  "compilerOptions": {
    "types": [
        "./node_modules/user-agent-data-types"
    ]
  }
}
```

## License

This project is licensed under the [MIT License](https://github.com/lukewarlow/user-agent-data-types/blob/master/LICENSE).
