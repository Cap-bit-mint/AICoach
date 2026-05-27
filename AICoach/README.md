# AICoach - 你的顶级AI学习私教

<div align="center">

![AICoach Banner](https://img.shields.io/badge/AICoach-AI学习私教-4F46E5?style=for-the-badge&logo=sparkles)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**结合费曼学习法，为用户提供个性化学习路径规划、概念讲解、项目练习和进度追踪**

</div>

---

## 核心功能

- **学习路径可视化** - 生成动态知识树，追踪学习进度 (To Do / Doing / Done)
- **费曼学习法** - 用简单话解释复杂概念，确保真正"学会"而非"听懂"
- **自动学习资料管理** - 自动创建主题文件夹，保存学习笔记、练习记录
- **个性化教学** - 根据你的水平、目标、偏好定制学习路径
- **项目实践** - 设计小项目、练习题、应用场景
- **温柔鼓励风格** - 像一位耐心又风趣的大学导师

---

## 自动激活关键词

当你说以下内容时，AICoach会自动激活：
- "教我XX"、"学习XX"
- "帮我规划学习路径"
- "费曼学习法"
- "coach"、"tutor"、"私教"

---

## 一键安装

### Claude Code

```bash
# 方法1: 使用 claude code skills install 命令
/claude code skills install https://github.com/Cap-bit-mint/AICoach

# 方法2: 克隆到本地
git clone https://github.com/Cap-bit-mint/AICoach.git
# 然后在 Claude Code 中加载 skill
```

### OpenClaw

在 OpenClaw 中搜索 "AICoach" 或使用一键安装功能。

### 手动安装

1. 克隆本仓库
2. 将 `SKILL.md` 的内容复制到你的AI助手的系统提示/自定义指令中
3. 保存并重新加载

---

## 使用示例

```
用户: 我想学习 LLM
AICoach: 好的！我们一起来把 LLM 变成你的拿手技能 😊
        为了给你量身定制最适合的学习路径，可以先告诉我...
        ...
        我先为你生成一份 LLM 的知识树...
```

```
用户: 教我费曼学习法
AICoach: 费曼学习法是诺贝尔物理学奖得主理查德·费曼发明的学习方法...
        核心是四个字："以教促学"...
```

---

## 项目结构

```
AICoach/
├── README.md          # 本文件
├── SKILL.md           # 技能定义文件（Claude Code/OpenClaw 格式）
└── .claude/
    └── settings.json  # Claude Code 配置
```

---

## 工作流程

```
1️⃣ 诊断起点 → 了解你的水平、目标、偏好
2️⃣ 制定计划 → 拆解成小步、可执行阶段
3️⃣ 概念讲解 → 清晰结构 + 例子 + 类比
4️⃣ 项目练习 → 设计小项目、练习题
5️⃣ 检查掌握 → 提问、mini-quiz、复述
6️⃣ 迭代鼓励 → 庆祝进步、调整计划
```

---

## 许可证

MIT License - 随意使用、修改、分享

---

<div align="center">

**不只让你走对路，更让你清楚整张地图。** 🗺️

</div>
