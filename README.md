# Horizon 地平线人工智能

> 看见未来，陪你走向未来。

Horizon 是一个面向学生的 AI 未来规划与成长陪伴平台。

## 项目简介

- 平台类型：Web 单页应用
- 核心定位：AI 未来规划与成长陪伴
- 功能模块：成长指数面板、AI 规划、成长陪伴等

## 技术栈

- 原生 HTML / CSS（Tailwind 风格内联样式）
- JavaScript（单文件应用，业务逻辑全部内联）
- ECharts 5.5.1（图表可视化，CDN 引入）
- Supabase JS 2.45.4（数据后端，CDN 引入）

## 本地运行

项目为单文件应用，所有样式、脚本、图片均内联于 `index.html`。

直接使用浏览器打开 `index.html` 即可运行，或通过任意静态服务器托管：

```bash
# 方式一：直接打开
open index.html

# 方式二：本地静态服务器（推荐）
python -m http.server 8080
# 然后访问 http://localhost:8080
```

## 开源说明

- 本项目由 [秒哒](https://miaoda.online) 平台创建，页面源码为单文件导出。
- 外部依赖通过 CDN 加载：ECharts（npmmirror / jsdelivr）、Supabase JS（jsdelivr）、思源等宽字体与小米字体（百度 BCE 静态资源）。
- 后端数据接口使用秒哒托管的 Supabase 服务，脱离秒哒环境后注册登录、数据存储等功能可能不可用；如需完整功能，请自行部署 Supabase 后端并替换源码中的 `SUPABASE_URL` 与 `SUPABASE_ANON_KEY` 配置。

## 在线预览

https://app-ec0c85v4jksh.miaoda.online/

## License

MIT
