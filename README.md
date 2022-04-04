## eslint-plugin-vitest

![npm](https://img.shields.io/npm/v/eslint-plugin-vitest)

Eslint plugin for vitest

### Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-vitest`:

```sh
npm install eslint-plugin-vitest --save-dev
```

### Usage

Add `vitest` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": ["vitest"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "vitest/no-skipped-tests": 2
  }
}
```

### Supported Rules

- No Skipped tests 
- Lower case title


### Licence 

[MIT](https://github.com/veritem/eslint-plugin-vitest/blob/main/LICENSE) Licence &copy; 2022 - present [veritem](https://github.com/veritem)
