## element-plus 私有库

## 开发

对组件做修改，play中测试，测试无误后更新package/element-plus/package.json的version版本号，然后提交。

提交之后`pnpm run build`编译，编译后在dist目录下执行`npm publish`发布到仓库

项目中`npm update`更新到最新版本
