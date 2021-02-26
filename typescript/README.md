### TS/ES-Lint
_ESLint:_
`npm install --save-dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin`

In your project package.json, lets add a lint script in order to lint all TypeScript code.
```
{
    "scripts": {
    ...
    "lint": "eslint . --ext .ts",
    }
}
```
