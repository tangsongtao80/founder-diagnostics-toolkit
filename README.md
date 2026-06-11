# 🗡️ Founder Diagnostics Toolkit

> 13 个 AI 诊断 Skill，来自经典商业书籍，帮创始人系统性地诊断和解决经营问题。

## 这是什么

把《精益创业》和《创新者的窘境》两本经典商业书的 13 个核心方法论，做成了可以一键安装、斜杠调用的 AI Skill。

每个 Skill 就是一个**诊断工具**——输入你公司的情况，输出结构化分析报告和行动建议。

## 快速安装

```bash
npx skills add https://github.com/tangsongtao80/founder-diagnostics-toolkit
```

安装后在 OpenClaw / Claude Code 中输入斜杠命令即可调用。

## Skill 清单

### 《精益创业》— 8 个产品迭代诊断 Skill

| Skill | 斜杠命令 | 一句话用途 |
|:---|:---|:---|
| MVP | `/mvp` | 用最低成本验证核心商业假设 |
| Build-Measure-Learn | `/build-measure-learn` | 建立快速迭代的反馈循环 |
| Pivot | `/pivot` | 假设证伪后系统性地调整方向 |
| Validated Learning | `/validated-learning` | 用实验而非直觉做商业决策 |
| Innovation Accounting | `/innovation-accounting` | 为新业务建立有意义的指标体系 |
| Actionable Metrics | `/actionable-metrics` | 区分真增长和虚荣指标 |
| Five Whys | `/five-whys` | 连续追问五层找到根本原因 |
| Small Batch | `/small-batch` | 小批量交付加速学习减少浪费 |

### 《创新者的窘境》— 5 个颠覆创新诊断 Skill

| Skill | 斜杠命令 | 一句话用途 |
|:---|:---|:---|
| Disruption Signal | `/disruption-signal` | 检测你的行业是否正在被颠覆 |
| Value Network | `/value-network` | 分析什么在系统性阻止你创新 |
| RPV Diagnostic | `/r-p-v` | 诊断组织的资源/流程/价值观瓶颈 |
| Performance Oversupply | `/performance-oversupply` | 判断竞争基础是否已经转移 |
| Disruption Strategy | `/disruption-strategy` | 基于五大原则制定颠覆应对策略 |

### 《极简增长》— 5 个聚焦增长诊断 Skill

| Skill | 斜杠命令 | 一句话用途 |
|:---|:---|:---|
| Core Four Questions | `/growth-core-four-questions` | 四大灵魂追问诊断增长方向 |
| Needle-Point Focus | `/needle-point-focus` | 针尖领域——选细分赛道的诊断 |
| Pressure Focus | `/pressure-focus` | 压强原则——资源集中度诊断 |
| Hidden Assets | `/hidden-assets` | 挖掘你没有充分利用的隐性资产 |
| First Principles Growth | `/first-principles-growth` | 用第一性原理推翻隐含假设 |

## 使用示例

### 场景 1：增长停滞，找根因

```
/five-whys 我们的用户增长连续3个月停滞，核心转化率从8%降到3%
```

→ AI 会引导你连续追问五层，找到系统层面的根本原因，并给修复建议。

### 场景 2：判断行业是否在被颠覆

```
/disruption-signal 我在做传统零售ERP，最近出现了几个免费的SaaS工具，虽然功能不如我们，但增长很快
```

→ AI 会扫描五大颠覆信号，判断风险等级和时间窗口。

### 场景 3：新产品第一版做什么

```
/mvp 我想做一个面向独立设计师的项目管理工具，不确定第一版该包含哪些功能
```

→ AI 会帮你定义核心假设、设计最小功能集、设定验证标准。

## 每个 Skill 包含

- ✅ 核心方法论来源（书名/作者/章节）
- ✅ 适用场景（3-4 个具体触发条件）
- ✅ 执行步骤（可操作流程）
- ✅ 输出格式（结构化模板）
- ✅ 注意事项（实战坑位提醒）

## 适用场景

- **创始人/CEO**：系统性诊断经营问题
- **产品经理**：验证想法、加速迭代
- **战略/商业分析**：判断行业格局变化
- **投资人**：快速评估被投企业健康度

## 方法论来源

| 书籍 | 作者 | Skill 数 |
|:---|:---|:---|
| 《精益创业》(The Lean Startup) | 埃里克·莱斯 | 8 |
| 《创新者的窘境》(The Innovator's Dilemma) | 克莱顿·克里斯坦森 | 5 |
| 《极简增长》 | 彭志强 | 5 |

持续更新中。下一批计划：《复盘》《ROE预算管理》《段永平问答录》。

## 关注更多

- 📕 小红书：人车家增长案例集
- 📖 公众号：经营兵器库（每周日更新，Skill 实战案例）

## License

MIT
