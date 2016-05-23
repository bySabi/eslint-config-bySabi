# bySabi ESLint configuration

## Install

```sh
npm install --save-dev https://github.com/bySabi/eslint-config-bySabi.git#master
```

## Use

In your project's `.eslintrc`, use the `extends` feature:

```js
{
  'extends': 'eslint-config-bySabi'
}
```

If you are using this in a project with React, extend the React configuration
instead:

```js
{
  'extends': 'eslint-config-bySabi/react'
}
```
