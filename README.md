# SmsForwarder Web Plus (短信转发器 Web 客户端 · AI 美化增强版)

> 💡 **项目说明**：本项目的前端 UI 界面与交互体验基于开源项目 [CTCD/SmsForwarder-Web-Client](https://github.com/CTCD/SmsForwarder-Web-Client)，由作者在 AI 协助下进行重新设计、美化与功能增强。

这是一个基于开源项目 [CTCD/SmsForwarder-Web-Client](https://github.com/CTCD/SmsForwarder-Web-Client) 进行现代化 UI 美化与体验增强的单文件 Web 客户端程序。

## ✨ 主要特性与优化亮点

* **现代卡片式视觉设计**：引入精美的圆角卡片式布局，界面风格更加简洁、现代。
* **深色/浅色主题切换**：支持一键切换深色与浅色模式，夜间操作更加护眼舒适。
* **本地配置记忆**：服务地址与签名密钥自动保存在浏览器的 `localStorage` 中，并支持一键折叠顶部配置栏，让高频操作区域更加清爽。
* **快捷导航与交互升级**：顶部集成常用接口胶囊快捷标签，单选框全面升级为现代分段控制器（Segmented Control）。
* **结构化数据视图**：
  * **短信与通话**：查询结果自动渲染为带状态徽章的卡片列表，支持点击“[回复]”快捷联动。
  * **电量查询**：支持网格卡片化展示，并可随时一键切换回带语法高亮的原始 JSON 视图。
* **核心逻辑保持一致**：严格保留了原项目的所有 API 端点、动态表单生成以及基于 Web Crypto API 的 HMAC-SHA256 签名机制。

---

## 🚀 快速开始

本客户端采用纯前端单文件（HTML + CSS + JavaScript）实现，无需复杂的后端编译与部署：

1. 克隆或下载本仓库的 `index.html` 文件。
2. 直接在任意现代浏览器中双击打开，或将文件托管至任意静态网页服务器。
3. 输入你的“短信转发器”后台服务地址与签名密钥（Key），即可开始远程管理。

---

## 📄 鸣谢与开源协议

* **原始项目**：[CTCD/SmsForwarder-Web-Client](https://github.com/CTCD/SmsForwarder-Web-Client)
* **开源协议**：本项目延续原项目的开源精神，遵循 **GNU General Public License v3.0 (GPLv3)** 协议进行分发和开源。
