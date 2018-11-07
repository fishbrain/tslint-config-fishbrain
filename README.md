# TSLint config for Fishbrain TypeScript projects

[![npm version](https://badge.fury.io/js/tslint-config-fishbrain.svg)](https://badge.fury.io/js/tslint-config-fishbrain)
[![Build Status](https://travis-ci.com/fishbrain/tslint-config-fishbrain.svg?branch=master)](https://travis-ci.com/fishbrain/tslint-config-fishbrain)

Rule set based on [Airbnb JavaScript style guide](https://github.com/airbnb/javascript)
with some extra immutability rules from [tslint-immutable](https://www.npmjs.com/package/tslint-immutable).

## Usage

```bash
$ npm install -D tslint-config-fishbrain
```

tslint.json

```json
{
  "extends": ["tslint-config-fishbrain"]
}
```

### Recommended tsconfig.json settings

In addition to setting target, module, moduleResolution etc,
these strictness settings are recommended.

```json
{
  "compilerOptions": {
    "strict": true,
    "noFallthroughCasesInSwitch": true,
    "noImplicitReturns": true,
    "noUnusedLocals": true,
    "noUnusedParameters": true
  }
}
```
