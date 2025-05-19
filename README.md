<div align="center">
  <a href="https://github.com/anncwb/vue-vben-admin">
    <img alt="VbenAdmin Logo" width="215" src="https://unpkg.com/@vbenjs/static-source@0.1.7/source/logo-v1.webp">
  </a>
  <br>
  <br>

[![license](https://img.shields.io/github/license/anncwb/vue-vben-admin.svg)](LICENSE)

  <h1>Vue Vben Admin</h1>
</div>

## 简介

Vue Vben Admin 是 Vue Vben Admin 的升级版本。作为一个免费开源的中后台模板，它采用了最新的 Vue 3、Vite、TypeScript 等主流技术开发，开箱即用，可用于中后台前端开发，也适合学习参考。

## 升级提示

该版本为最新版本 `5.0`，与其他版本不兼容，如果你是新项目，建议使用最新版本。如果你想查看旧版本，请使用 [v2 分支](https://github.com/vbenjs/vue-vben-admin/tree/v2)

## 特性

- **最新技术栈**：使用 Vue3/vite 等前端前沿技术开发
- **TypeScript**：应用程序级 JavaScript 的语言
- **主题**：提供多套主题色彩，可配置自定义主题
- **国际化**：内置完善的国际化方案
- **权限**：内置完善的动态路由权限生成方案

## 预览

- [Vben Admin](https://vben.pro/) - 完整版中文站点

测试账号：vben/123456

<div align="center">
  <img alt="VbenAdmin Logo" width="100%" src="https://anncwb.github.io/anncwb/images/preview1.png">
  <img alt="VbenAdmin Logo" width="100%" src="https://anncwb.github.io/anncwb/images/preview2.png">
  <img alt="VbenAdmin Logo" width="100%" src="https://anncwb.github.io/anncwb/images/preview3.png">
</div>

## 文档

[文档地址](https://doc.vben.pro/)

# 快速开始 {#quick-start}

## 前置准备

::: info 环境要求

在启动项目前，你需要确保你的环境满足以下要求：

- [Node.js](https://nodejs.org/en) 20.15.0 及以上版本，推荐使用 [fnm](https://github.com/Schniz/fnm) 、 [nvm](https://github.com/nvm-sh/nvm) 或者直接使用[pnpm](https://pnpm.io/cli/env) 进行版本管理。
- [Git](https://git-scm.com/) 任意版本。

验证你的环境是否满足以上要求，你可以通过以下命令查看版本：

```bash
# 出现相应 node LTS版本即可
node -v
# 出现相应 git 版本即可
git -v
```

:::

## 安装使用

1. 获取项目代码

```bash
git clone https://github.com/vbenjs/vue-vben-admin.git
```

2. 安装依赖

```bash
cd vue-vben-admin
npm i -g corepack
pnpm install
```

3. 运行

```bash
pnpm dev
```

4. 打包

```bash
pnpm build
```
