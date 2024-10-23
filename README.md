# eslint-config-akero

## Install
```bash
npm install --save-dev git+https://github.com/akerotwo/eslint-config-akero.git @eslint/js@9.13.0 eslint@9.13.0 prettier@3.2.5
```

## Use
In the root of your project create a file with the name `eslint.config.mjs` and copy in the following
```js
import eslint from 'eslint-config-akero';
export default [...eslint];
```