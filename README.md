# mymall

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### 本地 .eslintrc.js 文件配置
```
// https://eslint.org/docs/user-guide/configuring

module.exports = {
  root: true,
  parserOptions: {
    parser: 'babel-eslint'
  },
  env: {
    browser: true,
  },
  extends: [
    // https://github.com/vuejs/eslint-plugin-vue#priority-a-essential-error-prevention
    // consider switching to `plugin:vue/strongly-recommended` or `plugin:vue/recommended` for stricter rules.
    'plugin:vue/essential',
    // https://github.com/standard/standard/blob/master/docs/RULES-en.md
    'standard'
  ],
  // required to lint *.vue files
  plugins: [
    'vue'
  ],
  // add your custom rules here
  rules: {
    // allow async-await
    'generator-star-spacing': 'off',
    // allow debugger during development
    'no-debugger': process.env.NODE_ENV === 'production' ? 'error' : 'off',
    'quotes': 'off',
    'semi': 'off',
    'comma-dangle': 'off',
    'space-before-function-paren': 0,  // 函数名称或function关键字与开始参数之间不检查空格
    'padded-blocks': ["error", { "classes": "never" }]
  }
}
```

### 本地配置 .gitignore 文件
```
//.gitignore
 
.DS_Store
node_modules
/dist
 
# local env files
.env.local
.env.*.local
 
# Log files
npm-debug.log*
yarn-debug.log*
yarn-error.log*
 
# Editor directories and files
.idea
.vscode
*.suo
*.ntvs*
*.njsproj
*.sln
```
