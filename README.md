# Finance Toolkit · 金融投资 Skill 与资料库

> 一个聚焦**金融投资**的 Claude Code / AI Agent Skill 与资料集合。内容按 `01`、`02`、`03`… 编号目录依次组织，便于持续扩充。
> A curated collection of finance & investment skills and materials for Claude Code / AI agents, organized into numbered folders (`01`, `02`, `03`, …) that grow over time.

---

## ⚠️ 免责声明（请先读）

本仓库内容**仅用于 AI / 研究 / 教育**与投资方法观察，**不构成任何投资建议**。其中部分投资风格（如卡脖子小盘、短线游资）**极度激进、高风险，不可照搬**。任何真实投资决策风险自负。涉及具体人物的内容均为基于**公开信息**的**第三方提炼**，**非本人授权或确认**；A股流派一律以**风格档**呈现（不指向具体在世人物）。

---

## 🗂 目录结构

仓库按编号目录依次存放不同主题的内容：

| 目录 | 内容 |
|------|------|
| `01_投资大师Skills/` | 投资大师 / 流派认知蒸馏 Skill（23 位大师/流派，美股 + A股） |
| `02_投资研究团队/` | 投资查询用的「五人团队」框架（CLAUDE.md + skill 两种用法） |
| `03_…` | （待补充） |

> 后续新增的金融投资相关 Skill 与材料，将继续以 `02`、`03`… 编号目录追加。

---

## 01 · 投资大师认知蒸馏 Skills

把投资大师的**认知操作系统**（心智模型 + 决策启发式，而非语录堆砌）蒸馏成可复用的 AI Agent Skill。23 位大师/流派，每个都是一份结构统一、可直接喂给 AI Agent 的投资方法论底座。

### 美股 `01_投资大师Skills/us/`（11 位真人 + 1 位新锐）

| Skill | 原型 | 风格内核 |
|------|------|------|
| `buffett_value` | Warren Buffett | 宽护城河 + 安全边际 + 永久持有 |
| `munger_quality` | Charlie Munger | 多元思维模型 + 逆向 + 质量优先 |
| `lynch_growth` | Peter Lynch | 六类公司分类 + PEG + tenbagger |
| `graham_deepvalue` | Benjamin Graham | 深度低估 + 烟蒂 + NCAV + 安全边际 |
| `soros_macro` | George Soros | 反身性 + 盛衰循环 + 不对称下注 |
| `dalio_allweather` | Ray Dalio | 全天候 + 风险平价 + 分散圣杯 |
| `druckenmiller_macro` | Stanley Druckenmiller | 流动性驱动 + 高确信集中重仓 |
| `marks_contrarian` | Howard Marks | 第二层思维 + 周期定位 + 防御 |
| `livermore_trend` | Jesse Livermore | 顺势 + 关键点突破 + 金字塔加仓 |
| `simons_quant` | Jim Simons | 数据驱动 + 多因子 + 去情绪纪律 |
| `wood_disruption` | Cathie Wood | 颠覆性创新 + Wright's Law + 5年视角 |
| `serenity_chokepoint` | Serenity（白毛股神）| 卡脖子 + AI 半导体上游小盘隐形冠军 |

### A股 `01_投资大师Skills/cn/`（2 位真人 + 9 个风格档）

| Skill | 原型 | 风格内核 |
|------|------|------|
| `duanyongping_value` | 段永平（大道无形我有形）| 本分 + 买股票就是买公司 + 能力圈 |
| `liyien_aihardware` | 李一恩 | AI 硬件主线龙头 + 确定业绩爆发 + 拿着别动 |
| `baima_quality` | 风格档 | 核心资产白马龙头 + 高 ROE + 长期持有 |
| `track_growth` | 风格档 | 高景气赛道 + 自上而下选赛道选龙头 |
| `macro_cycle` | 风格档 | 宏观周期 + 美林时钟 + 板块轮动 |
| `youzi_trend` | 风格档 | 短线情绪 + 龙头战法 + 量价（高风险）|
| `rotation` | 风格档 | 行业比较 + 景气切换 + 相对强弱 |
| `factor_quant_cn` | 风格档 | 多因子打分 + 分散 + 纪律调仓 |
| `dividend_yield` | 风格档 | 高股息 + 派息可持续 + 防御 |
| `lowval_dividend` | 风格档 | 低 PE/PB + 安全边际 + 价值回归 |
| `contrarian_left` | 风格档 | 弱者体系 + 赔率思维 + 左侧逆向 |

> `01_投资大师Skills/results/` 存放对应 Skill 的示例产出（如 `serenity_cn_top10.md`）。

### 蒸馏方法论（每个 Skill 的统一结构）

借鉴业界优秀实践（提取认知 OS、承认内在张力、来源分级、证伪前置），每个 skill 含 12 节：

1. **世界观 / 投资信仰** — 第一性的底层信念
2. **心智模型** — 该大师的核心 mental models（表格化）
3. **决策启发式** — 可执行的判断规则
4. **分析框架 / 检查清单** — 选股/分析的具体步骤
5. **选股筛选器** — ✅ 正向命中 + 🚩 风险红旗
6. **仓位 / 风控 / 持有纪律**
7. **卖出 / 退出逻辑**
8. **内在张力 / 边界** — 诚实写出矛盾，拒绝脸谱化
9. **表达风格 DNA**
10. **输出契约** — 结论分档 → 事实基底 → 判据 → 风险 → 估值/情景档 → **证伪条件** → 来源分级
11. **与 Agent 系统集成**
12. **免责声明**

**核心原则**：提取**可复用的认知框架**，不是语录；**承认大师的内在矛盾**（如巴菲特"永久持有"却清仓航空、木头姐 ARKK 的巨幅回撤），避免理想化失真；关键数据**来源分级**（一手/管理层声称/推断/推测）；每个结论都给**证伪条件**。

---

## 02 · 投资研究团队

用于**投资 / 理财 / 标的查询**的协作框架：以「五人团队」方式工作，保证**充分调研 + 多空双方观点 + 严格校验 + 清晰总结**。

| 角色 | 职责 |
|------|------|
| **领导** | 统筹流程 + 最终总结 |
| **规划师** | 调研搜索、取证、标注来源 |
| **正方投顾** | 看多逻辑 |
| **反方投顾** | 看空逻辑 |
| **审核师** | 校验数据与观点合理性；不过关则**驳回重修，循环至全部通过才出结论** |

**工作流**：`问题 → 规划师调研取证 → 正方/反方分别立论 → 审核师校验（驳回重修，循环至通过）→ 领导总结`

提供两种用法（内核一致，按环境二选一）：

- [`02_投资研究团队/CLAUDE.md`](02_投资研究团队/CLAUDE.md) —— 放进项目根目录或 `~/.claude/CLAUDE.md`，Claude 默认自动以五人团队工作。
- [`02_投资研究团队/investment-research-team/`](02_投资研究团队/investment-research-team/) —— 把文件夹放进 `.claude/skills/`，按需触发的 skill 版本。

---

## 🚀 用法

- **01 · 大师 Skill**：把对应 `.md` 放进你的 skills 目录，在对话里触发"用 XX 的视角分析……"；也可作为投资 Agent 的方法论 prompt 注入调研/决策环节，或用于不同流派的风格对照。
- **02 · 研究团队**：能用 CLAUDE.md 就放 `CLAUDE.md`（自动常驻），否则用 `investment-research-team/` skill（按需触发）。

---

## 📄 License

[MIT](LICENSE) · 代码/文本可自由使用，但请保留免责声明，且**不得作为投资建议传播**。
