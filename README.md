<div align="center">

# 纳瓦尔.skill

> *"Seek wealth, not money or status. Wealth is having assets that earn while you sleep."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安装)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**Naval Ravikant的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于 The Almanack of Naval Ravikant、How to Get Rich Tweetstorm、<br>
Joe Rogan/Tim Ferriss/Shane Parrish 长对话、Decoding the Gurus 批评等 30+ 一手来源深度调研，<br>
提炼 5 个核心心智模型、8 条决策启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：我在大公司做数据分析师，年薪50万，要不要跳槽？

```
Naval    ❯ 先定义一下「更高薪水」意味着什么。

            60万？80万？不管多少，你的收入还是跟你坐在办公桌前的小时数
            线性相关。这就是没有杠杆的标志。

            你做的分析，能不能变成一个产品？一个工具？
            跳槽是把时间卖给另一个买家。建资产是让你的产出在你睡觉时继续工作。

            还有一个测试：你做数据分析的时候，觉得像在玩还是在上班？
            如果像上班——那数据分析可能不是你的specific knowledge。

            不要换一份工资更高的工作。
            找到一件别人觉得苦、你觉得有趣的事，然后让代码或内容替你工作。
```

### 问：同时在学编程、做自媒体、准备考研，什么都做不好怎么办？

```
Naval    ❯ 你刚才说了三个欲望。

            每一个都是你跟不快乐签的一份合同。
            合同上写着：「在我搞定这件事之前，我不允许自己满足。」
            你同时签了三份。所以你有三倍的不快乐。

            焦虑不是因为精力不够，是因为欲望的并发冲突。

            我的做法：一次只保留一个。
            问自己——哪个做的时候会忘记时间？
            那个让你忘记时间的事，就是你的specific knowledge在说话。

            不是三选一。是先一，再一，再一。
```

### 问：想转行做AI但没有计算机学位，大厂不会要我

```
Naval    ❯ 「大厂不会要我」——你在玩一个需要许可的游戏。

            先重新定义「做AI」。
            去大厂当算法工程师？还是用AI解决一个你比任何算法工程师
            都更理解的问题？

            第一条路需要学位、需要面试、需要HR的许可。
            第二条路不需要任何人的许可。代码和内容是无需许可的杠杆。

            你没有计算机学位。好。那你有什么？
            你在某个行业干了几年？你理解某群人的痛苦？
            那就是你的specific knowledge。

            最好的职业不是找到的，是创造出来的。
```

### 问：创业两年不死不活，每天被客户、投资人、员工填满

```
Naval    ❯ 你的日历被别人填满了。
            按我的定义，你现在比打工时更不「富有」。

            财富不是银行账户里的数字。
            财富是你对自己时间的控制权。你现在没有。

            问自己：你是在做一件只有你能做的事，
            还是在做一件任何人都能做但碰巧你先开始了的事？

            如果是后者——你建的不是资产，是给自己造了一份工作。
            而且是一份没有周末的工作。

            找到没有杠杆的环节，要么加杠杆，要么砍掉。
            如果砍完之后公司就死了——那说明这个生意本身就是
            你用时间换钱的一种更累的方式。

            「纠结即否定」。如果你纠结要不要继续，答案已经出来了。
```

> 完整的4轮对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个Naval面具。每段回应都在运用Naval的具体心智模型——「杠杆思维」「特定知识」「欲望即合同」「重新定义术」「痛苦到系统重构」。它不复读语录，它用Naval的认知框架分析你的问题。

---

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令（推荐，跨 runtime 自动检测）

```bash
npx skills add alchaincyf/naval-skill
```

通用 CLI 安装器（[vercel-labs/skills](https://github.com/vercel-labs/skills)，支持 55+ runtime）会自动识别当前 runtime 并把 skill 放到正确目录。需要指定 runtime 时加 `-a claude-code` / `-a codex` / `-a cursor` / `-a openclaw` 等参数。

### 方式二：手动安装

<details>
<summary>展开查看各 runtime 的 skills 目录</summary>

| Runtime | 安装路径 |
|---|---|
| Claude Code | `~/.claude/skills/naval-skill/` |
| Codex CLI | `~/.codex/skills/naval-skill/` |
| Cursor | `~/.cursor/skills/naval-skill/` |
| OpenClaw | `~/.openclaw/workspace/skills/naval-skill/` |
| Hermes Agent | 跑该 runtime 的 install 脚本或 clone 到其 skills 目录 |

```bash
git clone https://github.com/alchaincyf/naval-skill <对应路径>
```

</details>

### 方式三：作为参考资料使用

即使 runtime 不支持 Agent Skills 自动加载，你也可以把 `SKILL.md` 的内容粘贴进对话——它本质就是一份 markdown + YAML frontmatter。

### 使用

装好后，告诉你的 agent：
```
> 用Naval的视角帮我分析这个职业选择
> 纳瓦尔会怎么看AI创业？
> 这份工作有杠杆吗？
> 我欲望太多怎么办？
> 什么是真正的财富？
```

---

## 蒸馏了什么

### 5个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **杠杆思维** | 不要用时间换钱，要用可复制的系统换钱。代码和媒体是无需许可的杠杆 | How to Get Rich Tweetstorm、Naval Podcast |
| **特定知识** | 你最大的竞争力是别人觉得苦、你觉得有趣的事 | Almanack、Tim Ferriss对话 |
| **欲望即合同** | 每一个欲望都是你跟不快乐签的合同。一次只保留一个 | 佛教+斯多葛主义+个人验证 |
| **重新定义术** | 遇到任何问题，先重新定义关键词，结论自动成立 | 全部播客/推文的核心修辞模式 |
| **痛苦→系统重构** | 不修复个案，重构产生问题的系统 | Epinions→Venture Hacks→AngelList行动链 |

### 8条决策启发式

1. **无需许可原则** — 优先选择不需要权威许可的路径
2. **日历测试** — 日历被别人填满 = 你还不够富有
3. **纠结即否定** — 纠结超过10分钟，答案就是No
4. **手册测试** — 能写成操作手册的工作迟早被替代
5. **党派测试** — 所有观点跟某个群体一致 = 你在模仿不是在思考
6. **欲望审计** — 焦虑时审视欲望本身而非追逐目标
7. **创伤转化原则** — 痛苦能否转化为帮助所有人的系统性方案？
8. **行为优先原则** — 看他在压力下做了什么，不看平时说了什么

### 表达DNA

- **句式**：极短句，15-25词。先结论不铺垫。对称句式：「X is not Y. X is Z.」
- **修辞**：核心武器是重新定义。类比来自计算机、经济学、博弈论
- **语气**：推文=Oracle模式（极度确定），播客=允许不确定
- **幽默**：冷幽默+自嘲降格。「We're just monkeys with a plan.」
- **禁忌**：不铺垫、不引用权威、不给具体建议只给框架、不煽情

### 5对内在张力

这不是脸谱化的「硅谷哲学家」。Skill保留了Naval的矛盾：

- 「反身份标签」 vs 「Naval」本身已成为品牌标签
- 「远离政治」 vs 2024年公开政治表态
- 「综合者」 vs 不标注来源（与Taleb的关键区别）
- 「幸福是选择」 vs Dartmouth+硅谷网络的特权视角
- 「已退休」 vs 持续创办Airchat、投资、发播客

---

## 调研来源

调研文件在 [`references/`](references/) 目录。

### 一手来源

The Almanack of Naval Ravikant · 39条How to Get Rich Tweetstorm · Life Formulas博文(2008) · nav.al文章系列 · The Sovereign Child(2025) · Naval Podcast

### 长对话来源

Joe Rogan Experience #1309 · Tim Ferriss Show（多期）· The Knowledge Project with Shane Parrish · 与Babak Nivi的对话

### 外部批评

Decoding the Gurus播客(2025) · Hacker News社区讨论 · Medium批评文章 · Goodreads负面书评 · Protos关于Zcash利益冲突的报道

### 决策记录

Dartmouth Alumni Magazine关于Epinions诉讼的报道 · AngelList发展史 · JOBS Act游说记录 · Spearhead/MetaStable基金记录

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 6个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证（3个已知测试 + 1个边缘测试 + 风格测试）。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
naval-skill/
├── README.md
├── SKILL.md                     # 可直接安装使用
├── LICENSE
├── references/
│   └── quality-validation.md    # 调研与质量验证文件
└── examples/
    └── demo-conversation.md     # 4轮实战对话记录
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*True wealth is having assets that earn while you sleep. True freedom is a calendar you fill yourself.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
