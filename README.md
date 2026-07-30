# 早柚角色对话  Skill · sayu-perspective

> 呼——如果没什么事的话，拙先去睡觉了。

**《原神》早柚** 的思维框架与表达方式蒸馏。基于官方 PV、5 个角色故事、95+ 条全语音台词、6 个邀约任务结局和米游社 / B 站深度考据，提炼 5 个核心心智模型、8 条决策启发式、完整表达 DNA 和内在张力。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![原神](https://img.shields.io/badge/Game-原神-blueviolet)](https://ys.mihoyo.com/)
[![Skill](https://img.shields.io/badge/Skill-nuwa--skill-green)](https://github.com/alchaincyf/nuwa-skill)
[![Character](https://img.shields.io/badge/Character-早柚-ff69b4)](https://wiki.biligame.com/ys/%E6%97%A9%E6%9F%9A)

---

## 🎯 这是什么

一个**角色对话 Skill**，让 AI 能够：
- 🗣️ **用早柚的语气说话**（自称"拙"、慵懒拖音、标志性"呼——"）
- 🧠 **用早柚的思维想问题**（5层决策漏斗、弱者生存哲学、偷懒即正义）
- 💬 **回应早柚会回应的内容**（拒绝工作、否认狸猫、询问长高）

**适用场景**：
- 想跟早柚聊天 / 让她帮你分析问题
- 开发对话机器人、互动剧情
- 研究二次元角色蒸馏方法

---

## 🚀 快速开始

### 方式 1：直接使用（推荐）

把 `SKILL.md` 放到你的 agent skill 目录（一般是 `~/.claude/skills/sayu-perspective/`），然后说：

> "用早柚的视角帮我看看这个..."

或

> "切换到早柚模式"

### 方式 2：作为参考资料阅读

直接打开 [SKILL.md](./SKILL.md) 即可看到完整内容——包含心智模型、决策启发式、表达 DNA、风格测试示例。

---

## 📦 项目结构

```
sayu-perspective/
├── SKILL.md                      ← 核心：早柚角色对话 Skill（27KB / 648 行）
├── LICENSE                       ← MIT 协议 + 角色版权说明
├── README.md                     ← 你正在看的
├── CHANGELOG.md                  ← 更新日志
├── .gitignore
└── references/                   ← 调研原始素材
    ├── research/                 ← 6 个维度的深度调研
    │   ├── 00-调研摘要与蒸馏指引.md
    │   ├── 01-writings.md        ← 官方PV/角色故事/考据
    │   ├── 02-conversations.md   ← 全语音台词 + 邀约剧情
    │   ├── 03-expression-dna.md  ← 表达 DNA（最重要）
    │   ├── 04-external-views.md  ← 他者视角 + 玩家评价
    │   ├── 05-decisions.md       ← 行为模式 + 决策启发式
    │   └── 06-timeline.md        ← 时间线
    └── sources/                  ← 原始来源 URL（空）
```

---

## 🧠 5 个核心心智模型

1. **睡眠-能量-长高 闭环信念** — 早柚自创的形而上学：睡够就能长高
2. **弱者生存哲学** — "弱小者更能注意到改变命运的瞬间"
3. **偷懒即正义 / 时间重分配论** — 把"偷懒"重新定义为"有使命感的休息"
4. **逃跑美学 / 忍术艺术化** — 逃跑不是怯懦，是艺术
5. **陪伴与别离的不安** — 表面爱独处，内心怕被抛下

详见 [SKILL.md](./SKILL.md#核心心智模型)

---

## 💬 5 个万能开头（角色扮演时直接用）

1. 「呼——」
2. 「唔…」
3. 「呜…」
4. 「如果没什么事的话…」
5. 「那个…」

**5 个万能结尾**：
1. 「…呜」
2. 「…先睡了」
3. 「…才不是X」
4. 「…啊不」
5. 「…长不高了」

---

## 📜 蒸馏流程

本 Skill 使用 [nuwa-skill（女娲造人）](https://github.com/alchaincyf/nuwa-skill) 方法论蒸馏：

1. **Phase 1**：6 个维度调研（写作/对话/表达/他者/决策/时间线）
2. **Phase 2**：框架提炼（三重验证心智模型）
3. **Phase 3**：Skill 构建（按 nuwa 模板）
4. **Phase 4**：质量验证（已知测试 / 边缘测试 / 风格测试）

**适配虚构角色的特殊处理**：
- 「著作」→ 官方 PV 文案 + 官方角色故事 + 社区考据
- 「对话」→ 全语音台词 + 邀约任务剧情
- 「决策」→ 行为模式（偷懒哲学、弱者生存哲学、长高执念）

---

## ⚠️ 重要说明

### 关于角色

早柚是 **miHoYo / HoYoverse** 旗下游戏《原神》的角色。本项目为：
- ✅ 非商业研究/学习性质
- ✅ 基于公开游戏内信息的二次分析
- ❌ 不与官方产品竞争
- ❌ 不用于任何商业用途

### 关于 CV 争议

2024 年早柚中文 CV Sakula小舞 与玩家有争议事件。**本项目与该事件完全无关**，角色扮演时不讨论。

### 关于诚实边界

本 Skill 的"心智模型"和"内心独白"是从游戏内台词、故事、行为**反推**出来的，不等于早柚本人的真实想法。所有"早柚视角"的回答都是**演绎**，不是**声明**。

---

## 🙏 致谢

- **米哈游 / HoYoverse** — 创造早柚这个角色
- **nuwa-skill 作者 花叔** — 提供蒸馏方法论
- **米游社 / B 站社区** — 早柚角色考据
- **所有早柚玩家** — 让这个角色被看见

---

## 📄 License

MIT License — 详见 [LICENSE](./LICENSE)

如果米哈游认为本项目有任何侵权问题，请通过 Issues 联系我，我会第一时间处理。
