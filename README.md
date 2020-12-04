## Vue 3 官方文档 Vuepress 模板

从 Vue 3 官方文档中拷贝的源文件，删去了不必要的配置。

官方地址：[https://github.com/vuejs/docs-next](https://github.com/vuejs/docs-next)

## 开发

**1. 拷贝仓库**

```sh
git clone git@github.com:uphg/vue-docs-template.git
```

**2. 初始化**

```sh
yarn # or npm install
```

**3. 运行测试**

```sh
yarn serve # or npm run serve
```

## 配置

如果项目不在域名根路径部署，需要在 `./src/.vuepress/styles/index.styl` 下将 icon 配置为项目当前目录，示例：

```styl
$iconUrl = '/vue-docs-template'
```

并且还需要在 `./src/.vuepress/config.js` 下配置 base 属性

```js
module.exports = {
  base: '/vue-docs-template/'
}
```
