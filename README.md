# 📦 PM Chest (产品经理百宝箱)

> 你的 AI 产品搭档，从需求分析到 UI 原型，一气呵成。

**PM Chest** 是一个专为 Trae IDE 设计的自定义 Skill。它不仅仅是一个工具，更像是一位经验丰富的产品经理助手，能够通过对话引导你理清思路，生成专业的 PRD 文档，并直接输出可交互的 HTML 原型。

---

## ✨ 核心功能

### 1. 🕵️‍♀️ 智能需求澄清 (Requirement Clarification)
- **主动引导**：不再需要你一次性把需求想清楚。PM Chest 会像真人 PM 一样，通过关键问题反问，帮你挖掘潜在需求。
- **自动决策**：遇到拿不准的细节？选择“直接帮我决定”，它会基于行业最佳实践为你提供方案。

### 2. 📝 标准化 PRD 生成 (PRD Writing)
- **专业结构**：自动生成包含版本历史、背景痛点、业务流程、功能列表、详细交互规则的 Markdown 文档。
- **数据埋点**：自动规划核心数据指标和埋点需求，不遗漏任何数据价值。

### 3. 🎨 即时 UI 设计与原型 (UI Design & Prototyping)
- **风格可选**：极简风、商务风、科技风...多种风格任你挑选。
- **交互原型**：不仅仅是图片，而是生成真实的 HTML/CSS/JS 代码。你可以直接在浏览器中点击、交互，验证产品逻辑。

## 🚀 如何安装

1.  打开你的 Trae 项目。
2.  进入项目根目录下的 `.trae/skills/` 文件夹。（如果不存在，请手动创建）
3.  将本项目文件夹 `pm-chest` 完整克隆或复制到 `.trae/skills/` 目录下。
    ```bash
    # 在 .trae/skills/ 目录下执行
    git clone https://github.com/Kejin-LI/pm-chest.git
    ```
4.  **重启 Trae** 或在命令面板执行 `Developer: Reload Window`。

## 💡 如何使用

在 Trae 的对话框（Chat）中，输入以下任意自然语言指令即可唤醒：

- "启动 PM Chest"
- "我想做一个待办事项 App，帮我设计一下"
- "帮我写一个宠物社区小程序的 PRD"

接下来，只需要跟随它的引导，一步步完成产品的孵化！

## 📂 项目结构

```text
pm-chest/
├── README.md           # 项目说明文档
├── SKILL.md            # Skill 核心定义与提示词工程
└── ...
```

---
*Created with ❤️ by Trae Assistant*
