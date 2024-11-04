[![codecov](https://codecov.io/github/LilyHmg/ssy-ui-vite/graph/badge.svg?token=NOAVO0C3PD)](https://codecov.io/github/LilyHmg/ssy-ui-vite)
<a href="https://codecov.io/github/LilyHmg/ssy-ui-vite" > 
 <img src="https://codecov.io/github/LilyHmg/ssy-ui-vite/graph/badge.svg?token=NOAVO0C3PD"/> 
 </a>
<p align="center">
<img src = "https://cdn.vuetifyjs.com/docs/images/brand-kit/v-logo.png" style="width:200px;"/>
</p>
<h1 align="center">SSY-UI-VITE</h1>
<p align="center">
  基于 Vite 栈的前端工程化实践
</p>
<p align="center">
<img src="https://img.shields.io/github/license/Nagnahs-1/Web-SSY-UI-VITE?color=red"/>
<img src="https://img.shields.io/npm/v/ssy-ui-vite?color=red" />
<img src="https://img.shields.io/npm/dm/ssy-ui-vite?color=red" />
</p>

## Features
- 基于 Vue 框架
- 支持 JSX与 Vue 单文件组件
- Jest + Vue3 plugins实现单元测试
- Eslint + Prettier + Husky 语法检查
- 采用 Rollup 构建
- Vitepress + Vercel 文档网站搭建
- 基于Action CI 实现持续集成与交付

## Install

```bash
npm i ssy-ui-vite
```

## Quick Start

```vue
import Vue from 'vue'
import SSYUI from 'ssy-ui-vite'
const App = { template: `
<SButton  color="blue">
主要按钮
</SButton>
`, };
createApp(App)
.use(SSYUI)
.mount("#app");
```

## Browser Support

支持大多数现代浏览器和 IE10+

# Join Us

如果希望尽快上手，可以访问[Getting Started](https://web-ssy-ui-vite.vercel.app/)
