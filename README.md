# 🗡️ Founder Diagnostics Toolkit

> 27 个诊断 Skill + 4 个垂直 Agent — 来自 5 本经典商业书，帮创始人系统诊断经营问题。

## ⚡ 四个垂直诊断 Agent

**不需要记 Skill 名字。** 描述问题，Agent 自动选武器。

| Agent | 一句话 | 专攻 |
|:---|:---|:---|
| `/founder-dx` | 创始人诊断师 | 全科——任何经营问题 |
| `/growth-dx` | 增长引擎诊断师 | 增长停了、方向不清、产品推不动 |
| `/finance-dx` | 财务罗盘诊断师 | 不赚钱、现金流紧、成本失控 |
| `/review-dx` | 战略复盘师 | 复盘、目标达不成、组织变革推不动 |

```
/founder-dx 我的 SaaS 增长连续三个月停滞，核心转化率从 8% 降到 3%
```

→ AI 自动选择四大追问 + 针尖聚焦 + 第一性原理三个 Skill，输出结构化诊断报告。

**调用方式：** 安装后输入 `/founder-dx` 或直接描述你的经营困扰。

---

## 快速安装

```bash
npx skills add https://github.com/tangsongtao80/founder-diagnostics-toolkit
```

安装后在 OpenClaw / Claude Code 中即可调用。

---

## 全部 27 个诊断 Skill

> 也需要单独使用某个诊断工具？以下按书籍分类列出。

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

### 《ROE预算管理》— 4 个财务经营诊断 Skill

| Skill | 斜杠命令 | 一句话用途 |
|:---|:---|:---|
| ROE Diagnostic | `/roe-diagnostic` | 杜邦分析拆解 ROE，定位短板因子 |
| Three Compare Five Look | `/three-compare-five-look` | 三比五看——系统性经营数据分析 |
| Cashflow Triangle | `/cashflow-triangle` | 经营/投资/融资三现金流健康诊断 |
| ROE Budget Target | `/roe-budget-target` | 以 ROE 为原点倒推预算目标 |

### 《复盘》— 5 个复盘诊断 Skill

| Skill | 斜杠命令 | 一句话用途 |
|:---|:---|:---|
| Fupan Five Steps | `/fupan-five-steps` | 联想五步复盘——结构化的项目/决策复盘 |
| Goal Alignment | `/goal-alignment` | 目的/目标/策略/指标四层一致性诊断 |
| Dual Dimension Review | `/dual-dimension-review` | 逻辑维度（数字）+ 行动维度（动作）双线复盘 |
| Feedback Analysis | `/feedback-analysis` | 德鲁克反馈分析法——发现真正长处和盲区 |
| Five Reflections | `/five-reflections` | 五反机制——让复盘走完深度学习的五层循环 |

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
| 《复盘》 | 沈磊 | 5 |
| 《ROE 预算管理》 | 付小平 | 4 |

持续更新中。每周拆一本书。

## 关注更多

- 📕 小红书：人车家增长案例集
- 📖 公众号：经营兵器库（每周日更新，Skill 实战案例）

## License

MIT
