# 使用说明
## 初始化
```sh
lerna bootstrap
```
## 组件自动编译
```sh
cd packages/v-act-jgbutton
yarn vact:dev
```
## 启动项目测试环境
新建终端，然后执行以下命令：
```sh
cd packages/v-act-project
yarn vact:start
```
## 编辑组件
打开packages/v-act-jgbutton/src/components/JGButton/Index.tsx进行编辑，保存后，项目测试环境自动刷新。

# 监听开发系统业务构件
详细步骤请参考插件 [@v-act/v3dev-component-watcher](https://www.npmjs.com/package/@v-act/v3dev-component-watcher) 说明。