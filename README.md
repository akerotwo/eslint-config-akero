# eslint-config-akero

## Install
```bash
npm install --save-dev git+https://github.com/akerotwo/eslint-config-akero.git @eslint/js@9.13.0 eslint@9.13.0 prettier@3.2.5
```

## Create Files

### eslint.config.js
```js
import eslint from 'eslint-config-akero';
export default [...eslint];
```

### .prettierrc.json
```json
{
  "semi": true,
  "printWidth": 120,
  "useTabs": false,
  "arrowParens": "always",
  "singleQuote": true
}
```

### .prettierignore
```
node_modules
package.lock.json
build
```