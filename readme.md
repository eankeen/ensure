# ensure

![github ci](https://github.com/eankeen/ensure/workflows/Test%20CI/badge.svg?branch=master) ![github badge](https://img.shields.io/github/license/eankeen/ensure) ![gitHub issues](https://img.shields.io/github/issues/eankeen/ensure)

Ensure you are running a minimum version of Deno, Typescript, or V8

## Usage

Note that it hasn't been tested with `rc-1` type release versions _yet_

```ts
import { ensure } from 'https://deno.land/x/ensure/mod.ts'

ensure({
  denoVersion: "1.0.0",
  typeScriptVersion: "3.8"
})
```

### Versions

You can ping to a specific version. Here are some examples:

```sh
# deno 1.0.3 and std v0.53.0
https://raw.githubusercontent.com/eankeen/ensure/v1.0.3/mod.ts
```

