# 🚀 Local Prompt Tuner (Standalone) | 本地 Prompt 调优平台

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Pure Frontend](https://img.shields.io/badge/Tech-Pure%20Frontend-green.svg)
![Data Privacy](https://img.shields.io/badge/Privacy-Local%20First-blue.svg)

[English](#english) | [中文](#chinese)

---

<a name="english"></a>
## 🇬🇧 English Description

### 📖 Introduction
**Local Prompt Tuner** is a lightweight, **single-file** tool designed for LLM Prompt Engineering and batch testing. 

It is a **pure frontend application** (HTML + JS) with no backend server required. All your prompt configurations, test datasets, and evaluation results are stored strictly in your browser's local storage (`localStorage`). This ensures your data privacy while providing a powerful workspace for tuning prompts against OpenAI-compatible APIs (like OpenAI, vLLM, DeepSeek, Ollama, etc.).

### ✨ Key Features

* **⚡ Zero Deployment:** Just download the `index_standalone.html` file and open it in your browser. No Python, Node.js, or Docker required.
* **🔒 Privacy First:** Uses a "Local-First" architecture. Your API keys and prompt data never leave your browser (except when sending requests directly to your specified LLM API endpoint).
* **🧪 Batch Testing:** Supports batch generation with variable injection (Mustache syntax `{{variable}}`).
* **📊 Data Management:** * Import/Export test cases via **Excel (.xlsx)**.
    * Built-in manual scoring and review system (1-5 stars).
* **🔌 Flexible API Support:** Compatible with any OpenAI-format API endpoint (supports custom Base URLs for local models).

### 🚀 Quick Start
1. Download `index_standalone.html`.
2. Open it in Chrome, Edge, or Safari.
3. Go to the **"Settings"** tab, enter your API Key and Model URL.
4. Start tuning your prompts!

---

<a name="chinese"></a>
## 🇨🇳 中文介绍

### 📖 项目简介
**Local Prompt Tuner** 是一个轻量级的、**单文件**的 LLM Prompt 调试与批量测试工具。

这是一个**纯前端应用**（HTML + JS），无需任何后端服务器支持。所有的 Prompt 配置、测试数据集以及评测结果都完全存储在您的浏览器本地缓存（`localStorage`）中。在提供强大的 Prompt 调优功能（支持 OpenAI、vLLM、DeepSeek、Ollama 等兼容接口）的同时，最大程度地保护了您的数据隐私。

### ✨ 核心功能

* **⚡ 零部署成本：** 只需下载 `index_standalone.html` 文件并在浏览器打开即可使用。无需安装 Python、Node.js 或 Docker 环境。
* **🔒 隐私优先：** 采用“本地优先”架构。除了向您指定的 LLM API 发送推理请求外，您的 API Key 和数据永远不会离开浏览器上传到第三方服务器。
* **🧪 批量测试：** 支持基于变量注入的批量生成测试（使用 `{{变量名}}` 语法）。
* **📊 数据管理：** * 支持通过 **Excel (.xlsx)** 导入/导出测试用例。
    * 内置人工评分与审阅系统（1-5 星打分机制）。
* **🔌 灵活的接口支持：** 兼容所有 OpenAI 格式的 API 接口（支持自定义 Base URL，完美适配本地部署的模型）。

### 🚀 快速开始
1. 下载 `index_standalone.html` 文件。
2. 直接使用 Chrome、Edge 或 Safari 浏览器打开。
3. 进入 **“设置”** 标签页，填入您的 API Key 和模型地址。
4. 开始您的 Prompt 调优之旅！

---

### 📄 License / 许可协议
This project is licensed under the **MIT License**. You are free to use, modify, and distribute it.
本项目采用 **MIT 许可协议**。您可以自由地使用、修改及分发代码。

---

### 📷 Screenshots / 截图

![1768210711428](images/1768210711428.png)
