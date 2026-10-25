# AI × 量化交易前沿日报 — 2026-10-25

> 共收录 **20** 条 | 信息源成功 **9** 个 / 失败 **3** 个

## ⭐ Top 3 亮点

1. **[When News Gets Old: Portfolio Allocation with Reinforcement Learning and Large Language Models](https://arxiv.org/abs/2610.30564v1)** — `arXiv q-fin` · score 12
2. **[Governed Self-Evolution for Autonomous Investing: A Multi-Agent LLM System with an Invariant Core](https://arxiv.org/abs/2610.30557v1)** — `arXiv q-fin` · score 12
3. **[Lineage-Aware Search Control for LLM-Based Evolutionary Factor Mining](https://arxiv.org/abs/2610.29663v1)** — `arXiv q-fin` · score 12

---

## 【量化精选】

### 1. [Recent Quant Links from Quantocracy as of 10/18/2026](https://quantocracy.com/recent-quant-links-from-quantocracy-as-of-10182026/)

- **来源**: Quantocracy | **评分**: 8 | **时间**: 2026-10-19 05:15 UTC
- **摘要**: 这是 Quantocracy 截至 10 月 18 日的量化链接精选，汇集了策略研究、风险认知和市场评论等近期内容。其中包括 Quantitativo 对动量策略的“Less Wrong”讨论，以及 Jeff Yass 关于误把亏损策略当作盈利策略这一根本风险的提醒。
- 💡 **为何关注**: 它适合作为量化研究雷达，快速跟踪社区正在讨论的策略改进与过拟合风险。

### 2. [Recent Quant Links from Quantocracy as of 10/22/2026](https://quantocracy.com/recent-quant-links-from-quantocracy-as-of-10222026/)

- **来源**: Quantocracy | **评分**: 7 | **时间**: 2026-10-23 05:15 UTC
- **摘要**: 这是 Quantocracy 截至 10 月 22 日的量化链接精选，重点汇集了趋势、动量和策略评估方面的外部文章。被收录内容之一是用标普 500 最强趋势阶段的变化率来调节动量暴露，尝试改进这一历史悠久的交易思想。
- 💡 **为何关注**: 它提供了可快速扫描的策略研究入口，尤其适合寻找动量择时和趋势过滤的新变体。

### 3. [Directionally Correct Views in Portfolio Optimization](https://arxiv.org/abs/2610.31074v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-10-22 10:51 UTC
- **摘要**: 论文借鉴 Black-Litterman 框架，研究在 Markowitz 型组合优化中加入专家方向性观点是否能改善配置。结果显示，即使少量方向正确的信息也能显著改善投资决策，作者还讨论了如何用熵相关方法把专家观点纳入端到端组合模型。
- 💡 **为何关注**: 它为人工判断、LLM 观点或宏观信号如何规范地进入组合优化提供了清晰依据。

### 4. [Equilibria and Learning in Competitive Market Making](https://arxiv.org/abs/2610.30891v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-10-22 08:09 UTC
- **摘要**: 论文构建一个由多个策略性做市商和单一非策略代表交易者组成的连续报价做市博弈，并处理非凸、非连续收益带来的均衡与学习困难。作者证明在资产价值分布的最小假设下纯策略纳什均衡总存在，且均衡买卖价差会随资产价值波动率严格扩大。
- 💡 **为何关注**: 它把做市竞争、价差形成和波动率联系起来，对高频做市策略与多代理市场仿真都有直接参考价值。

### 5. [Multiple Stopping and Exercise Boundaries for American Put Options](https://arxiv.org/abs/2610.30637v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-10-22 02:57 UTC
- **摘要**: 文章研究有限期限内最多可行权 m 次、相邻行权之间必须有冷却期的美式看跌期权。作者证明在每种剩余行权次数下最优策略由单一行权边界刻画，这些边界随剩余权利数量有序排列，并满足局部 Lipschitz 连续性。
- 💡 **为何关注**: 它为多次行权、路径受限期权和对冲工具的定价与执行算法提供了可落地的边界结构。

### 6. [What Prediction-Market Contracts Reveal at Launch: Trading Volume and Dispute Risk](https://arxiv.org/abs/2610.29578v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-10-21 11:20 UTC
- **摘要**: 作者使用 2023 年 1 月至 2026 年 5 月 Polymarket 上 802,863 个已结算市场的近全量数据，仅用上线时的标题、描述、结算来源和合约元数据预测生命周期成交量与结算争议。模型对成交量预测表现很强，样本外对数成交量 R² 达 0.747，且主题、措辞和结算规则设计都提供可解释信号。
- 💡 **为何关注**: 它说明合约文本本身就能预测流动性和争议风险，对预测市场做市、事件交易和新合约筛选很有价值。

### 7. [A game-theoretic analysis of the market microstructure in decentralized exchanges with concentrated liquidity](https://arxiv.org/abs/2610.28863v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-10-20 19:34 UTC
- **摘要**: 论文把集中流动性去中心化交易所中的策略性流动性供给建模为平均场博弈，流动性提供者需要选择价格区间宽度和再平衡时机。模型以受控连续时间马尔可夫链刻画个体区间、交易成本、手续费分配和群体状态之间的相互作用。
- 💡 **为何关注**: 它为 Uniswap V3 类做市中的区间选择、调仓频率和费用收益权衡提供了博弈论基础。

### 8. [Intraday Forecasting Ability and Liquidity Provision of Institutional Traders](https://arxiv.org/abs/2610.31141v1)

- **来源**: arXiv q-fin | **评分**: 6 | **时间**: 2026-10-22 12:00 UTC
- **摘要**: 研究利用交易所高频数据分析机构交易者的日内预测能力、流动性供给与自营盈利之间的关系。作者发现部分交易者具有持续预测能力，基于这些熟练交易者执行流构建的假设跟随策略在不同频率下展现出极高年化 Sharpe，并把已实现盈亏与对应期限的预测代理变量相连接。
- 💡 **为何关注**: 它为识别聪明订单流、构造日内跟随信号以及评估流动性供给价值提供了实证依据。

### 9. [Multichoice Modeling: Exploring Decision Configuration Space under Uncertainty](https://arxiv.org/abs/2610.31038v1)

- **来源**: arXiv q-fin | **评分**: 6 | **时间**: 2026-10-22 10:16 UTC
- **摘要**: 论文提出“多选择建模”，把复杂决策的配置空间显式展开，而不是在分析不确定性前过早收窄备选架构。借助崎岖适应度景观的思想，该框架将决策问题视作情境化绩效景观，使不同选择组合及其交互能够被计算化探索。
- 💡 **为何关注**: 它可启发量化研究者把策略组件、组合约束和执行方案作为整体配置空间优化，而非孤立调参。

### 10. [Dynamics of the Liquidity Profile in Concentrated Liquidity Provision: An SPIDE Approach](https://arxiv.org/abs/2610.30539v1)

- **来源**: arXiv q-fin | **评分**: 6 | **时间**: 2026-10-21 23:53 UTC
- **摘要**: 作者用随机偏积分微分方程刻画 Uniswap V3 等集中流动性 AMM 的流动性剖面动态。模型用退化 Sturm-Liouville 算子描述流动性围绕市场价格的均值回复集中，并用 Hilbert-Schmidt 积分算子捕捉提供者重新定位造成的非局部再分配，同时证明弱解的存在唯一性。
- 💡 **为何关注**: 它为集中流动性池的流动性演化、冲击传播和 LP 风险建模提供了更严格的连续时间框架。

### 11. [Less Wrong](https://www.quantitativo.com/p/less-wrong)

- **来源**: Quantitativo | **评分**: 6 | **时间**: 2026-10-18 13:01 UTC
- **摘要**: Quantitativo 的这篇文章提出对经典动量进行一个基础但有价值的改造，并报告了 Sharpe 比率约 1.15 的策略结果。标题同时提醒读者，策略研究中最危险的情形是误以为自己拥有盈利策略，而实际上它可能只是回测偏差或错误的产物。
- 💡 **为何关注**: 它把可交易的动量改进与策略证伪意识结合起来，适合用来检查动量策略的稳健性和研究流程。

## 【AI 前沿】

### 1. [Import AI 476: Creativity and RSI; worse-than-China open weight models; AI goes to space](https://jack-clark.net/2026/10/12/import-ai-476-creativity-and-rsi-worse-than-china-open-weight-models-ai-goes-to-space/)

- **来源**: Import AI | **评分**: 3 | **时间**: 2026-10-12 12:30 UTC
- **摘要**: Import AI 第 476 期讨论了模型创造力与 RSI、开放权重模型竞争格局，以及 AI 进入太空应用等话题。本期还提到新的视觉推理基准显示当前 AI 系统仍缺乏直觉式空间理解能力。
- 💡 **为何关注**: 它帮助 AI 交易者跟踪基础模型能力边界与开源生态变化，避免把尚未具备的推理能力误用于研究和交易自动化。

## 【交叉热点（quant×ai）】

### 1. [When News Gets Old: Portfolio Allocation with Reinforcement Learning and Large Language Models](https://arxiv.org/abs/2610.30564v1)

- **来源**: arXiv q-fin | **评分**: 12 | **时间**: 2026-10-22 00:44 UTC
- **摘要**: 论文研究财经新闻信号随时间衰减后应如何进入组合决策：是保留旧信号并显式提供时间信息，还是在组合选择前过滤掉。作者用固定 LLM 从 SEC 公开披露中提取信号，并比较强化学习策略与直接选组合的 LLM，在计入交易费用的历史测试中评估效果。
- 💡 **为何关注**: 它直接触及量化交易中最常见却最容易被忽略的信号时效性，并给出了 LLM 信号与 RL 组合管理的可复现结合方式。
- **标签**: quant x ai 交叉

### 2. [Governed Self-Evolution for Autonomous Investing: A Multi-Agent LLM System with an Invariant Core](https://arxiv.org/abs/2610.30557v1)

- **来源**: arXiv q-fin | **评分**: 12 | **时间**: 2026-10-22 00:22 UTC
- **摘要**: Steward 是一个面向自主投资的九角色多智能体 LLM 系统，由分析新闻、SEC 文件、宏观序列和市场数据的代理输出带类型报告，再由组合经理生成目标仓位。其核心设计是在类型系统中划定自我进化边界，让系统能从结果中学习，同时不削弱安全约束。
- 💡 **为何关注**: 它为会真实下单的 AI 投资代理提供了兼顾自我改进、审计和风控边界的工程蓝图。
- **标签**: quant x ai 交叉

### 3. [Lineage-Aware Search Control for LLM-Based Evolutionary Factor Mining](https://arxiv.org/abs/2610.29663v1)

- **来源**: arXiv q-fin | **评分**: 12 | **时间**: 2026-10-21 12:40 UTC
- **摘要**: 论文指出传统 LLM 进化式因子挖掘过度依赖个体和种群层面的随机变异，容易使搜索方向薄弱并聚集在结构相似的因子上。作者提出在“谱系”层面进行搜索控制，以更系统地组织 LLM 作为语义变异算子的探索过程。
- 💡 **为何关注**: 它有望提升自动化 Alpha 因子挖掘的多样性、方向性和可解释性，减少无效因子冗余。
- **标签**: quant x ai 交叉

### 4. [Distributions or Quantiles? A Convex Variational Theory of Worst-Case Risk](https://arxiv.org/abs/2610.29652v1)

- **来源**: arXiv q-fin | **评分**: 11 | **时间**: 2026-10-21 12:34 UTC
- **摘要**: 文章以谱风险度量为基础，建立统一的最坏情形风险凸变分理论，并解释何时应使用分布或分位数表示以保持完整模糊集的凸性。该框架把原先分散在不同模糊集结构中的结果推广到更丰富的稳健风险模型，并给出识别最坏情形的系统条件。
- 💡 **为何关注**: 这为压力测试、尾部风险预算和分布不确定性下的组合风险控制提供了更统一的数学工具。
- **标签**: quant x ai 交叉

### 5. [Learning to Incentivise: Using Reinforcement Learning for Sustainable Urban Mobility](https://arxiv.org/abs/2610.30469v1)

- **来源**: arXiv AI+Finance 搜索 | **评分**: 7 | **时间**: 2026-10-21 21:40 UTC
- **摘要**: 论文把城市出行激励分配视为动态优化问题，用多智能体强化学习鼓励司机改道到更优替代路径。目标是在不依赖传统道路收费的情况下降低全网总出行时间和排放，从而支持可持续城市交通。
- 💡 **为何关注**: 虽然场景不在金融市场，其多智能体激励设计与强化学习机制可迁移到做市激励、交易路由和资源分配问题。

### 6. [Direct Pass@$k$ Optimization for Thought Pruning: Balancing Quality and Diversity in Test-Time Reasoning](https://arxiv.org/abs/2610.31667v1)

- **来源**: arXiv AI+Finance 搜索 | **评分**: 5 | **时间**: 2026-10-22 17:59 UTC
- **摘要**: 论文研究测试时推理扩展中的候选剪枝：模型先生成大量短前缀，再决定哪些候选值得继续消耗算力。作者提出直接优化 Pass@k 的思想剪枝方法，在候选最终质量与多样性之间取得更好的平衡。
- 💡 **为何关注**: 它能降低 AI 交易代理在研究、代码生成和复杂决策中的推理成本，同时保留多路径探索能力。

## 【开源项目动态】

### 1. [[TauricResearch/TradingAgents] PR: fix(portfolio): match held tickers under broker aliases](https://github.com/TauricResearch/TradingAgents/pull/1561)

- **来源**: GitHub 项目动态 | **评分**: 10 | **时间**: 2026-10-24 11:16 UTC
- **摘要**: 该 TradingAgents 修复解决券商交易代码与规范代码不一致的问题，例如持仓使用 BTCUSDT 而分析器使用 BTC-USD 时会被误判为无持仓。修复后，别名持仓能被正确识别，避免单位落入“其他持仓”并继续向交易和风控模块传递错误上下文。
- 💡 **为何关注**: 这类看似细小的符号归一化错误会直接污染仓位、风险和交易决策，是实盘 AI 代理必须消除的基础缺陷。
- **标签**: quant x ai 交叉

### 2. [[microsoft/RD-Agent] PR: fix: return each analyzed error once in analyze_error](https://github.com/microsoft/RD-Agent/pull/1502)

- **来源**: GitHub 项目动态 | **评分**: 10 | **时间**: 2026-10-23 02:06 UTC
- **摘要**: 微软 RD-Agent 的该 PR 修复了 CoSTEERRAGStrategyV2.analyze_error 在知识图谱同时包含匹配节点和其他错误节点时重复返回同一错误的问题。修改后，每个已分析错误只返回一次，避免节点对象与字符串混合造成重复诊断。
- 💡 **为何关注**: 更可靠的错误归因会提升自动化研发与量化实验代理的调试效率，减少重复修复和错误上下文累积。
- **标签**: quant x ai 交叉

---

## 信息源抓取状态

| 信息源 | 类型 | 侧别 | 状态 | 条数 | 备注 |
| --- | --- | --- | --- | --- | --- |
| Quantocracy | rss | quant | ✅ 成功 | 10 | — |
| Hugging Face Daily Papers | rss | ai | ✅ 成功 | 15 | — |
| [r/algotrading](https://www.reddit.com/r/algotrading/) | reddit | quant | ❌ 失败 | 0 | HTTP 403 |
| [r/quant](https://www.reddit.com/r/quant/) | reddit | quant | ❌ 失败 | 0 | HTTP 403 |
| [r/MachineLearning](https://www.reddit.com/r/MachineLearning/) | reddit | ai | ❌ 失败 | 0 | HTTP 403 |
| arXiv q-fin | arxiv | quant | ✅ 成功 | 12 | — |
| arXiv AI+Finance 搜索 | arxiv | both | ✅ 成功 | 10 | — |
| Alpha Architect | rss | quant | ✅ 成功 | 5 | — |
| Quantitativo | rss | quant | ✅ 成功 | 10 | — |
| Last Week in AI (替代 The Batch) | rss | ai | ✅ 成功 | 10 | — |
| Import AI | rss | ai | ✅ 成功 | 10 | — |
| GitHub 项目动态 | github | both | ✅ 成功 | 3 | — |

*由 ai-quant-daily 自动生成。*