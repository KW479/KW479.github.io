# KW479 的个人主页

基于 GitHub Pages 的静态个人名片站。纯 HTML + CSS，无构建流程、无第三方依赖、无 JavaScript。

**访问地址：** <https://KW479.github.io/>

## 目录结构

```
.
├── index.html          # 网站本体（一屏式名片页）
├── README.md           # 本文件
└── github_homepage/    # 课程作业要求的网站文件副本
    ├── index.html
    └── README.md
```

## 页面内容

- 显示名：KW479
- 一句话介绍：嵌入式开发 / C++ / STM32
- 技术标签：STM32、C/C++、CMake、嵌入式系统
- GitHub 主页链接：<https://github.com/KW479>

页面不包含学号、真实姓名、邮箱、学校名称、私有仓库内容或任何未公开的个人信息。

## 本地预览

直接用浏览器打开 `index.html` 即可，不需要启动本地服务器。

## 技术说明

- 单文件页面，样式内联，不加载任何外部资源（字体、图标全部使用系统或内联 SVG）
- 响应式布局，手机与桌面均可正常显示
- 未使用 JavaScript，无脚本执行风险
- 提交身份使用 GitHub 的 noreply 隐私邮箱，不在公开仓库中暴露真实邮箱

## 部署

GitHub Pages 直接从 `main` 分支根目录发布，每次推送到 `main` 后自动重建站点。
