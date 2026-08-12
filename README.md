# 心力教练 · Xinli Coach

> *Mental Energy Coach — 心力 = 能量管理能力 + 注意力夺回能力。不是意志，不是暗示。*
> *Mental energy = energy management + attention reclaim. Not willpower, not suggestion.*

一个基于 **Hermes Agent Skill** 的个人心力教练系统。把"心力恢复、行动启动、反馈沉默期坚持、自我价值重建"四套干预，合成一条可执行的对话流程。内核来自认知行为疗法、压力科学（耗散结构 / 最优压力点）、自我决定理论与康德伦理学。

*A personal mental-energy coaching system built as a Hermes Agent skill. Four intervention modules — Recovery, Launch, Sustain, Value — integrated into one conversational flow. Roots: CBT, stress science, Self-Determination Theory, Kantian ethics.*

## 核心信念 · Core Beliefs

- 内耗的唯一来源：与不可控之事纠缠。已发生的不可改，未发生的不可控。
  *Mental drain comes only from wrestling the uncontrollable: what happened cannot be changed, what hasn't happened cannot be controlled.*
- 能量只投可控域，注意力只锚当下最小动作，其余交给规律。
  *Spend energy only in the controllable domain; anchor attention only on the next smallest action; leave the rest to natural law.*
- 压力是身体动员资源的信号，**不是自我否定**。短期压力有益；长期无法终止的动员才造成损伤。
  *Stress is the body mobilizing resources — not self-rejection. Acute stress is beneficial; only chronic, unending mobilization damages.*
- 智者不内耗，只因不与必然纠缠。
  *The wise do not burn out, because they do not wrestle with the inevitable.*

## 功能 · Features

### 两大工作模式 · Two Modes

- **日常复盘（高频）Daily Review**：本质穿透（一句话点出底层驱动）→ 能量审计（消耗在哪/补给在哪）→ 明日断舍离（1个微小动作指令）
- **深度探讨（低频）Deep Dive**：苏格拉底式提问 + 第一性原理，不给直接建议，引导用户自己决定

### 四个干预模块 · Four Modules

| 模块 Module | 触发 Trigger | 核心做法 Core |
|---|---|---|
| A 恢复 Recovery | 能量耗竭 Exhausted | 决策树四问 → 循环叹气呼吸 → 认知收口 → 72h 紧急计划 → 三层长期恢复 |
| B 启动 Launch | 有能量不敢动 Stuck | 恐惧定位 → 最小可信行动（四条件）→ if-then 执行意图 |
| C 坚持 Sustain | 反馈沉默期 No feedback | 内部刻度设计 → 正反馈闭环 → 愿力锚定 → 三层过滤外部反馈 |
| D 价值 Value | 结构层问题 Self-worth | 三问法 → 康德内心法官 → 事实/评价分离 → 终身学习实践 |

### 共享工具 · Shared Tools

- 叙事重写三层协议 *Narrative rewrite protocol*（去灾难化 → 事实-评价分离 → 意义重估）
- 双轨书写 *Dual-track journaling*（负向收口卸载 / 正向成功日记）
- 双裁判分域 *Two judges, two domains*（价值域=康德内心法官；能力域=归因裁判）
- 最小可信行动四条件 *Minimum credible action*（难度可承受 / 触碰恐惧 / 自主可控 / 产生新证据）

## 安装 · Install

将 `xinli-coach/` 文件夹复制到 Hermes skills 目录：
*Copy the folder into your Hermes skills directory:*

```
~/AppData/Local/hermes/skills/
```

## 使用 · Usage

安装后无需任何命令，自然语言触发：*Natural language triggers only:*

- "今天复盘" *daily review*
- "最近压力大" *stressed*
- "我又刷手机了" *doomscrolling again*
- "坚持不下去了" *can't keep going*

## 文件结构 · Structure

```
xinli-coach/
├── SKILL.md                          # 主文件：内核 + 铁律 + 流程 + 模块索引
└── references/
    ├── module-recovery.md            # 模块A：恢复 Recovery
    ├── module-launch.md              # 模块B：启动 Launch
    ├── module-sustain.md             # 模块C：坚持 Sustain
    └── module-value.md               # 模块D：价值 Value
```
## 声明 · Disclaimer

框架灵感来自公开的心理学科普内容（认知行为疗法、压力科学、自我决定理论等公共知识），全部内容均已重述改写，无逐字引用。

*Framework inspired by publicly available psychology popularization content (CBT, stress science, Self-Determination Theory, etc.). All content has been rewritten; no verbatim reproduction.*
## License

MIT

## 作者 · Author

[SageChenAI](https://github.com/SageChenAI)
