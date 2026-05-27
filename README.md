# AICoach - 你的顶级AI学习私教

<div align="center">

![AICoach](https://img.shields.io/badge/AICoach-AI学习私教-4F46E5?style=for-the-badge&logo=sparkles&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/Cap-bit-mint/AICoach?style=flat-square)](https://github.com/Cap-bit-mint/AICoach/stargazers)

**结合费曼学习法，为用户提供个性化学习路径规划、概念讲解、项目练习和进度追踪**

</div>

---

## 🚀 快速安装

### OpenClaw（强烈推荐）

```bash
# 方法一：Git 一键安装（推荐）
openclaw skills install git:https://github.com/Cap-bit-mint/AICoach.git

# 方法二：指定路径安装
openclaw skills install git:https://github.com/Cap-bit-mint/AICoach.git --path AICoach

# 方法三：手动安装
git clone https://github.com/Cap-bit-mint/AICoach.git
# 将 AICoach/AICoach/SKILL.md 复制到你的 skills 目录
openclaw skills reload
```

### Claude Code / Claude.ai

```bash
# Claude Code 命令
/claude code skills install https://github.com/Cap-bit-mint/AICoach

# 手动方式：
# 1. 打开 SKILL.md 文件
# 2. 复制全部内容
# 3. 在 Claude 设置 → Skills → 新建 Skill 并粘贴
```

### 其他平台（Codex、Open Interpreter 等）

```bash
git clone https://github.com/Cap-bit-mint/AICoach.git

复制 AICoach/AICoach/SKILL.md 的全部内容到对应平台的 Skill 或 Custom Instruction 中，然后重新加载工具。
```

---

## 使用示例

- 「我想学习大模型」
- 「教我提示词工程」
- 「用 AICoach 帮我学 Transformer 架构」
- 「基于这个资料教我 RAG」

AI 会自动触发**个性化诊断流程**并生成知识树。

---

## 核心功能

- **4维度诊断**：当前水平、学习目标、偏好风格、时间投入
- **动态知识树**：自动生成并追踪学习进度（To Do / Doing / Done）
- **费曼学习法**：大白话生活比喻 + 主动输出练习
- **智能资料管理**：自动创建学习文件夹与 Markdown 文件（支持文件操作环境）
- **支持用户素材**：可基于笔记、PDF、链接进行针对性教学
- **温柔陪伴式教学**：专业幽默 + 持续鼓励

---

## 自动激活关键词

当你说以下内容时，AICoach 会自动激活：

> "教我XX"、"学习XX"、"帮我规划学习路径"、"费曼学习法"、"coach"、"私教"...

---

## 工作流程

```
诊断起点 → 制定计划 → 概念讲解 → 项目练习 → 检查掌握 → 迭代鼓励
```

---

## 项目结构

```
AICoach/
├── SKILL.md              # 技能定义文件（支持 Claude Code / OpenClaw）
├── README.md             # 本文件
├── .claude/
│   └── settings.json     # Claude Code 配置
├── .gitignore
└── docs/
    ├── CONTRIBUTING.md   # 贡献指南
    └── CHANGELOG.md      # 更新日志
```

---

## 贡献与反馈

欢迎提交 Issue 和 Pull Request！

- 🐛 报告 Bug：[GitHub Issues](https://github.com/Cap-bit-mint/AICoach/issues)
- 💡 提出建议：[GitHub Discussions](https://github.com/Cap-bit-mint/AICoach/discussions)
- 📖 贡献代码：参见 [CONTRIBUTING.md](docs/CONTRIBUTING.md)

---

## 版本更新

参见 [CHANGELOG.md](docs/CHANGELOG.md)

当前版本：**v1.7**

---

## 许可证

MIT License - 随意使用、修改、分享

---

<div align="center">

**不只让你走对路，更让你清楚整张地图。** 🗺️

</div>
