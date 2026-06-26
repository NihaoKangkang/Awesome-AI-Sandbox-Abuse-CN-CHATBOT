# AI-Sandbox-KeepAlive-Automation

`🤖 Automatic Conversation Script for Maintaining AI Sandbox Sessions`

通过自动发送对话消息，维持 AI 沙盒环境（Code Interpreter / Agent Sandbox）的活跃状态，用于研究沙盒生命周期、会话保持机制以及自动化交互场景。

## 📖 Overview
许多 AI Agent 或 Code Interpreter 产品会为用户创建临时沙盒环境（Sandbox）。

这些沙盒通常具有：

- 空闲超时（Idle Timeout）
- 最大生命周期（Max Lifetime）
- 会话回收（Session Recycle）
- 网络或资源限制

当用户长时间不进行交互时，沙盒实例往往会被自动销毁。

本项目通过自动发送对话消息，模拟持续交互状态，以便：

- 研究沙盒生命周期
- 观察回收策略
- 进行长时间实验
- 维持自动化测试环境

## ✨ Features
- 自动发送对话消息
- 自定义发送时间间隔
- 支持长时间循环运行
- 自定义消息模板
- 简单轻量，方便二次开发
- 可用于 Sandbox 生命周期研究

## 🚀 Quick Start (建议使用virtual environment进行使用)
```
git clone https://github.com/NihaoKangkang/AI-Sandbox-KeepAlive-Automation.git
cd AI-Sandbox-KeepAlive-Automation
pip install -r requirements.txt
playweight install
python3 main.py
```

## 免责声明

本项目仅用于学习、测试和研究。

使用者应自行确保行为符合目标平台的使用规则与法律法规。项目作者不对滥用行为负责。
