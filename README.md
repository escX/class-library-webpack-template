# js-library-webpack-template
A template of js library built with webpack, devDependencies:

- `webpack`, `webpack-cli` 使用 `webpack` 编译，打包文件

- `clean-webpack-plugin` 用于 `webpack` 编译或打包过程中清理文件或文件夹

- `html-webpack-plugin` 用于生成一个可以引入编译后 `js` 文件的 `html`

- `webpack-dev-server` 用于生成开发环境的本地服务器

- `webpack-merge` 用于 `webpack` 配置文件的合并

- `@babel/core`, `@babel/preset-env`, `babel-loader` 使用 `babel` 将最新版本的`Javascript`语法转换为浏览器可以解析的语法

- `change-case` 将项目名称转换为 `PascalCase` 的命名方式，以便用于库名，或者暴露给全局