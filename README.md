<h1 align="center">conventional-changelog-semf-config</h1>

> This preset extends the [conventional-changelog-angular](https://github.com/conventional-changelog/conventional-changelog/blob/master/packages/conventional-changelog-angular/README.md) preset

### Differences to [conventional-changelog-angular](https://github.com/conventional-changelog/conventional-changelog/blob/master/packages/conventional-changelog-angular/README.md)

- 使用 **禅道** 或者其他工具管理项目，可以将 GitHub/GitLab 的 **issues** 地址替换成 **bugsUrl** 中的地址
- 显示 commit 对应的**提交人**及**邮箱地址**
- 使用 **emojis**

前置插件准备

- [commitizen](https://github.com/commitizen/cz-cli) 针对开发者简单的 commit 规范
- [cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog) 使用 cz-conventional-changelog 的构建标准
- [conventional-changelog-cli](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-cli#readme) conventional-changelog 核心模块
- 这里我使用 [release-it](https://github.com/release-it/release-it#readme) 作为发布版本插件，也可以选择 [standard-version](https://github.com/conventional-changelog/standard-version)

```sh
npm i commitizen cz-conventional-changelog conventional-changelog-cli --save-dev

npm install --save-dev release-it
```

```sh
npm install conventional-changelog-custom-config --save-dev
```
