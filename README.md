---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: e3f20544f50ffbec6278317e895e4aed_2e880a4aba9311f189c8525400393706
    ReservedCode1: VlebTJdSxPeVIwH+K21mG2bm3saOdJ3HdRcMh9hXiSVJZh5+6f1QUFbFCD65JtOmpCuQydCfu0TwI0uQS+vbWwZprR0KVVOSB4SSYkN1b7P4e+uLw1cRH5yqLHxYAG+p/4mQtjZ9Ygh1r1k768G2Yny/Ka29RRNnMNaE4CHh/3eEpfc2um2u87wiws0=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: e3f20544f50ffbec6278317e895e4aed_2e880a4aba9311f189c8525400393706
    ReservedCode2: VlebTJdSxPeVIwH+K21mG2bm3saOdJ3HdRcMh9hXiSVJZh5+6f1QUFbFCD65JtOmpCuQydCfu0TwI0uQS+vbWwZprR0KVVOSB4SSYkN1b7P4e+uLw1cRH5yqLHxYAG+p/4mQtjZ9Ygh1r1k768G2Yny/Ka29RRNnMNaE4CHh/3eEpfc2um2u87wiws0=
---

# Horizon 地平线人工智能

> 看见未来，陪你走向未来。

Horizon 是一个面向学生的 AI 未来规划与成长陪伴平台。

## 项目简介

- 平台类型：Web 单页应用
- 核心定位：AI 未来规划与成长陪伴
- 功能模块：成长指数面板、AI 规划、成长陪伴等

## 应用方案

HORIZON 是一套以 AI 为核心的完整未来成长系统，围绕「规划 → 执行 → 反馈 → 优化」闭环运行，包含八大功能模块：未来路线图、人生岔路模拟、AI 成长伙伴、简历中心、成长档案、今日计划、求职追踪、成长数据舱。

核心创新点：成长树可视化规划、引导式 AI 成长伙伴、规划执行闭环、职业规划与简历联动。

- 完整方案文档：[应用方案](docs/应用方案.md)
- 图文介绍原稿：[应用方案.pdf](docs/应用方案.pdf)

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
*（内容由AI生成，仅供参考）*
