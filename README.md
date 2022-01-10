> monorepo is use `lerna` and `yarn` workspace  
> please global add [lerna](https://www.npmjs.com/package/lerna) `npm i -g lerna`  
> 包管理执行 script 都使用 yarn，npm 不支持工作空间会导致有些包找不到

#### 创建一个包

```sh
lerna create [name] [location] #eg lerna create test-pkg ./packages
```
#### script

```sh
# 安装依赖 根目录
yarn start
```

#### 模块

> - 所有包包名都用`@laterly-js/`开头

- [ ] `@laterly-js/utils` 纯js工具库



