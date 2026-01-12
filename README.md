🚀 Local Prompt Tuner (Standalone) | 本地 Prompt 调优平台
English | 中文

<a name="english"></a>

🇬🇧 English Description
📖 Introduction
Local Prompt Tuner is a lightweight, single-file tool designed for LLM Prompt Engineering and batch testing.

It is a pure frontend application (HTML + JS) with no backend server required. All your prompt configurations, test datasets, and evaluation results are stored strictly in your browser's local storage (localStorage). This ensures your data privacy while providing a powerful workspace for tuning prompts against OpenAI-compatible APIs (like OpenAI, vLLM, DeepSeek, etc.).

✨ Key Features
⚡ Zero Deployment: Just download the index.html file and open it in your browser. No Python, Node.js, or Docker required.

🔒 Privacy First: Uses a "Local-First" architecture. Your API keys and prompt data never leave your browser (except when sending requests directly to your specified LLM API endpoint).

🧪 Batch Testing: Supports batch generation with variable injection (Mustache syntax {{variable}}).

📊 Data Management:

Import/Export test cases via Excel (.xlsx).

Built-in manual scoring and review system (1-5 stars).

🔌 Flexible API Support: Compatible with any OpenAI-format API endpoint (supports custom Base URLs for local models like vLLM/Ollama).

🛠️ Developer Friendly: Built with vanilla JavaScript and Tailwind CSS (via CDN). Easy to hack and modify.

🚀 Quick Start
Download index_standalone.html.

Open it in Chrome, Edge, or Safari.

Go to the "Settings" tab, enter your API Key and Model URL (e.g., http://localhost:8000/v1 or https://api.openai.com/v1).

Start tuning your prompts!
