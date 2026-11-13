# AI × 量化交易前沿日报 — 2026-11-13

> 共收录 **20** 条 | 信息源成功 **7** 个 / 失败 **5** 个

## ⭐ Top 3 亮点

1. **[Point-in-Time Encoders for Earnings Calls](https://arxiv.org/abs/2611.14325v1)** — `arXiv q-fin` · score 11
2. **[Are Value and Momentum Still Everywhere?](https://alphaarchitect.com/value-momentum-everywhere/)** — `Alpha Architect` · score 11
3. **[Conformal Risk Control for QoT-Aware Lightpath Feasibility Under Technology-Driven Domain Shift](https://arxiv.org/abs/2611.13893v1)** — `arXiv AI+Finance 搜索` · score 9

---

## 【量化精选】

### 1. [Tabular Foundation Models in Financial Predictions](https://arxiv.org/abs/2611.13550v1)

- **来源**: arXiv q-fin | **评分**: 8 | **时间**: 2026-11-10 04:09 UTC
- **摘要**: 技术简报将表格基础模型（TFM）引入会计与金融预测：这类模型在合成表格数据上预训练，可上下文学习、无需微调即输出数值预测，且天然避免了记忆真实公司结果导致的前视偏差。在预测企业次年盈利变化的基准任务上，作者将Google的TabFM与微调的LLM及传统方法做了对比。
- 💡 **为何关注**: 免微调、无前视偏差的表格基础模型可能大幅降低基本面量化中「小样本表格预测」的建模门槛。

### 2. [Diversified-Risk-Perception Risk Measures and Portfolio Selection](https://arxiv.org/abs/2611.11803v1)

- **来源**: arXiv q-fin | **评分**: 8 | **时间**: 2026-11-09 03:06 UTC
- **摘要**: 论文指出传统风险度量依赖单一概率模型，仅靠资产分散无法消除模型误设带来的偏差。作者提出「风险感知分散化」（DRP）框架，用灵活的指数聚合函数把多个风险模型的评估整合起来，并给出相应的投资组合选择方法，实现资产分散与模型分散的双重分散。
- 💡 **为何关注**: 模型风险是实盘中被低估的尾部来源，DRP为「多模型集成风控」提供了可落地的数学框架。

### 3. [Deep Learning for Operator Maps in Optimal Liquidation](https://arxiv.org/abs/2611.14245v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-11-10 15:56 UTC
- **摘要**: 论文研究带一般瞬态冲击核的最优清算问题：证明最优交易策略对临时/瞬态冲击参数与标的价格过程具有局部Lipschitz连续性，从而为「以模型参数为输入」的神经网络近似提供了理论依据。作者提出用深度学习直接学习参数到最优策略的算子映射，避免每次重新求解。
- 💡 **为何关注**: 执行算法每次重算最优策略成本高，「学一个参数到策略的算子」是让最优执行实时化的关键思路。

### 4. [Fine-Tuning an Order-Flow Foundation Model for Sub-Second Forecasting](https://arxiv.org/abs/2611.14117v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-11-10 14:07 UTC
- **摘要**: 作者在Bitstamp和Bitfinex的Level-3订单流数据上预训练了一个3亿参数的自回归生成模型，并首次将其微调到下游任务：预测亚秒级的微观价格收益与已实现波动率。实验展示了订单流基础模型「预训练—微调」范式的可行性。
- 💡 **为何关注**: 订单流基础模型的微调首秀，为高频/做市策略提供了类似LLM微调的迁移学习路径。

### 5. [Deceleration without identification: testing a power-law trend in Bitcoin prices under persistent noise](https://arxiv.org/abs/2611.13962v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-11-10 11:56 UTC
- **摘要**: 比特币价格在对数时间轴上近似一条直线，「幂律趋势」因此被广泛传播；但论文指出，当偏离项像随机游走一样持续时，对时间回归会虚假地报出高R²的趋势。作者先界定15年周度数据能回答什么，再用对噪声尺度不变、按含四年周期的持续偏离族校准的低频统计量做严格检验。
- 💡 **为何关注**: 这是一堂「伪趋势识别」方法论课：任何在长期趋势上做回归的策略（不止加密）都该先过这种持续性噪声检验。

### 6. [Nonzero-Sum Stochastic Exit Games with Singular Belief Dynamics](https://arxiv.org/abs/2611.13841v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-11-10 10:03 UTC
- **摘要**: 论文构建了一个非零和随机退出博弈：两家双寡头企业各自持有私人退出价值信息，需选择退出双寡头乃至退出垄断市场的时机，利润流由一维扩散驱动。允许垄断阶段退出使信念过程产生奇异动态，无法用常规SDE系统刻画，作者以正则逼近极限构造信念过程并给出对称均衡。
- 💡 **为何关注**: 不对称信息下的退出时机博弈是理解市场退出、流动性枯竭与竞争策略的高级博弈论工具。

### 7. [Optimal Trading Speed on Blockchain](https://arxiv.org/abs/2611.13616v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-11-10 05:52 UTC
- **摘要**: 论文从理论与实证两端研究区块链出块速度对市场微观结构的影响：更快的出块削弱套利者间的优先费竞争，把租金从区块生产者转移给套利者；均衡流动性在某个内部出块速度达到峰值。Base链Flashblocks升级（出块提速十倍）的自然实验证实了预测——优先费骤降、套利者净收益上升、主动做市商更快再平衡并规避毒性流，但池深下降、有效点差变化复杂。
- 💡 **为何关注**: 对链上做市与MEV策略而言，出块速度是直接影响利润分配的底层参数，该文给出了罕见的理论+自然实验证据。

### 8. [Making sense of rule 605](https://arxiv.org/abs/2611.13365v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-11-09 23:38 UTC
- **摘要**: 论文分析美国Rule 605监管报告数据（做市商Virtu与券商SoHo，2021年1月至2024年3月的月度披露），考察26个股票交易参数构成的16个数据集。结果显示线性回归与LSTM对订单分布的预测力都很差，尽管分布本身相对稳定；但月际相关性高度稳定且可预测。
- 💡 **为何关注**: 用真实监管披露数据度量执行质量的稳定性，对评估券商路由与交易成本建模很有价值，也警示「稳定分布≠可预测」。

### 9. [Diversification Across Predictors: Heterogeneous Ensemble Learning for Cross-Sectional Return Prediction](https://arxiv.org/abs/2611.12389v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-11-09 13:28 UTC
- **摘要**: 针对截面收益预测中低信噪比、高维因子与预测子非平稳的难题，论文把「分散化」从资产层面推广到预测模型层面：线性模型高偏差、神经网络高方差，失败模式互补。作者提出异构集成的bagging框架，将线性与非线性预测器组合，每个模型在自身擅长的子空间发挥作用，从而提升整体稳健性。
- 💡 **为何关注**: 「预测器分散化」直接回应多模型实盘中该信哪个的痛点，思路简单且可立即接入现有因子流水线。

### 10. [Adjoint Kernel Sensitivity of the Rough Heston Characteristic Exponent](https://arxiv.org/abs/2611.11652v1)

- **来源**: arXiv q-fin | **评分**: 7 | **时间**: 2026-11-08 22:19 UTC
- **摘要**: 粗糙波动率模型的多因子近似会影响傅里叶定价所用的特征指数。论文推导了粗糙Heston特征指数对记忆核的一阶灵敏度的伴随表示：在参数与输入方差曲线固定下，Volterra–Riccati泛函允许对核扰动与变换参量联合实解析延拓，并给出其Fréchet导数。
- 💡 **为何关注**: 为期权定价与校准提供核函数灵敏度的解析工具，可加速粗糙波动率模型的参数估计与误差量化。

### 11. [Retrospective Analysis of Team-Following Trading Profitability in Pumpfun Meme Coins Using Funding Networks](https://arxiv.org/abs/2611.11436v1)

- **来源**: arXiv q-fin | **评分**: 6 | **时间**: 2026-11-08 14:58 UTC
- **摘要**: 论文对Pumpfun模因币做回测式复盘：用资金网络识别「代币发行团队」（有向资金群组），考察若跟随正确团队能赚多少、以及只用发行前可得信息时还剩多少。基于2024年4月至2026年9月十个独立重建的窗口、真实SOL储备状态和1 SOL起步的有限资金账户，结果显示即使后验最优退出，主账户在8个窗口中能保住1 SOL以上。
- 💡 **为何关注**: 「后验视角 vs 事前可得信息」的对比设计，是评估链上跟单/聪明钱策略真实可赚性的教科书式方法论。

## 【AI 前沿】

### 1. [Last Week (Month) in AI #347 - Nvidia's spy, Anthropic's $1.4T IPO, AI's blue wave](https://lastweekin.ai/p/last-week-month-in-ai-347-nvidias)

- **来源**: Last Week in AI (替代 The Batch) | **评分**: 4 | **时间**: 2026-11-11 14:21 UTC
- **摘要**: Last Week in AI第347期汇总五周要闻：黄仁勋涉「间谍」调查风波；Anthropic与OpenAI分别被定价1.4万亿与1.25万亿美元、而AI开支增速放缓；Anthropic警告可能逼近递归自我改进；谷歌Gemini 4（Carbon）动态等。是一期信息密度较高的AI行业全景回顾。
- 💡 **为何关注**: AI算力与模型格局的变化直接影响AI主题交易与算力链定价，该刊是快速补齐行业背景的高效读物。

## 【交叉热点（quant×ai）】

### 1. [Point-in-Time Encoders for Earnings Calls](https://arxiv.org/abs/2611.14325v1)

- **来源**: arXiv q-fin | **评分**: 11 | **时间**: 2026-11-10 16:49 UTC
- **摘要**: 论文针对金融文本回测中的前视偏差问题，基于41万余场财报电话会议，训练了2010—2024年按年份截断的「时点」文本编码器，每个版本只读过截止日期之前的文本。随后在问答对上微调，系统比较四种预训练配方下不同时点编码器对检索与预测任务的影响。这是把NLP工具严谨嵌入历史回测框架的基础设施建设。
- 💡 **为何关注**: 做文本因子或财报情绪策略的人最忌前视偏差，时点编码器让基于LLM/检索的信号终于可以干净地回测。
- **标签**: quant x ai 交叉

### 2. [Are Value and Momentum Still Everywhere?](https://alphaarchitect.com/value-momentum-everywhere/)

- **来源**: Alpha Architect | **评分**: 11 | **时间**: 2026-11-06 16:57 UTC
- **摘要**: Alpha Architect用AQR公开数据复刻了Asness等人的经典论文「价值与动量无处不在」，检验其发表13年后的样本外表现。结果显示两大因子在股票、股指、债券、货币和商品上的收益均出现不同程度衰减，文章探讨了衰减幅度及其对因子配置的含义。
- 💡 **为何关注**: 价值与动量是绝大多数量化多因子组合的基石，其样本外衰减幅度直接决定因子权重与拥挤度管理。
- **标签**: quant x ai 交叉

### 3. [Conformal Risk Control for QoT-Aware Lightpath Feasibility Under Technology-Driven Domain Shift](https://arxiv.org/abs/2611.13893v1)

- **来源**: arXiv AI+Finance 搜索 | **评分**: 9 | **时间**: 2026-11-10 10:53 UTC
- **摘要**: 论文提出一种事后（post-hoc）共形风险控制框架：冻结预训练好的AI/ML回归模型，为其预测构造具有有限样本保证的不确定性区间，再通过策略规则把区间映射为可操作的决策。该方法以光网络传输质量（QoT）预测为场景，保证区间覆盖率的同时实证评估决策错误率。
- 💡 **为何关注**: 共形预测的「有限样本覆盖率保证」同样适用于交易信号置信区间构建，是把ML点预测变成可控风险决策的通用范式。
- **标签**: quant x ai 交叉

### 4. [PARDIG: Global Precipitation Estimates Learned from Sparse Satellite Observations](https://arxiv.org/abs/2611.13941v1)

- **来源**: arXiv AI+Finance 搜索 | **评分**: 6 | **时间**: 2026-11-10 11:28 UTC
- **摘要**: PARDIG是一个基于球形图-网格Transformer的AI框架，从稀疏卫星观测中学习生成近实时的全球降水估计。相比现有方案在精度、时延、覆盖范围与时空分辨率之间的权衡，PARDIG在稠密多源数据上训练，兼顾全球覆盖与近实时输出。
- 💡 **为何关注**: 降水等气象数据是农产品与天气衍生品交易的核心输入，近实时全球估计能力直接影响相关策略的信号时效。

### 5. [Discrete Model-Based Diffusion for Combinatorial Optimization in Multi-Robot Task Allocation](https://arxiv.org/abs/2611.13382v1)

- **来源**: arXiv AI+Finance 搜索 | **评分**: 6 | **时间**: 2026-11-09 23:59 UTC
- **摘要**: 论文提出离散模型基扩散方法用于多机器人任务分配等NP-hard组合优化问题。现有方法面临两难：模型基扩散无需训练但只适用于连续空间，而离散扩散求解器又需专门训练；该工作把扩散采样嵌入无训练的基于采样的优化框架并扩展到离散变量，可在秒级内给出近似解。
- 💡 **为何关注**: 组合优化在组合构建、订单拆单中无处不在，「免训练+离散扩散」的秒级求解器值得移植到交易优化场景。

### 6. [A Margin Perspective on LoRA: Robustness to Catastrophic Forgetting and Adapter Merging (MaLoRA)](https://arxiv.org/abs/2611.14397v1)

- **来源**: arXiv AI+Finance 搜索 | **评分**: 5 | **时间**: 2026-11-10 17:44 UTC
- **摘要**: 论文从间隔（margin）视角解释LoRA的两个经验现象：抗灾难性遗忘、以及独立训练的适配器可合并为一个多任务模型（MaLoRA）。作者给出理论刻画，说明低秩适配为何在持续学习与多任务场景中表现稳健，而这两点此前缺乏系统理解。
- 💡 **为何关注**: 对需要持续迭代的金融LLM（如研报/公告模型），LoRA抗遗忘与适配器合并能力意味着更低成本的模型版本管理。

### 7. [Blurring the Block Boundaries: Overlapping Block Denoising for Efficient Diffusion Language Models](https://arxiv.org/abs/2611.14387v1)

- **来源**: arXiv AI+Finance 搜索 | **评分**: 5 | **时间**: 2026-11-10 17:40 UTC
- **摘要**: 扩散语言模型（DLM）以块为单位迭代去噪，但每块速度受最慢token拖累、下一块无法提前开始。论文提出B3（Blurring the Block Boundaries）：两个块在共享前向传播中并行细化，通过重叠块去噪打破块边界串行瓶颈，在保持生成质量的同时显著降低延迟。
- 💡 **为何关注**: 低延迟文本生成对实时新闻解读、盘中快讯分析等场景有直接意义，B3是加速DLM推理的实用技巧。

## 【开源项目动态】

### 1. [[TauricResearch/TradingAgents] PR: Added architecture files and selected requirement for this draft](https://github.com/TauricResearch/TradingAgents/pull/1692)

- **来源**: GitHub 项目动态 | **评分**: 9 | **时间**: 2026-11-12 16:11 UTC
- **摘要**: 多智能体交易框架TradingAgents提交了一份架构草案PR，新增架构蓝图、ADR（组合感知的CLI设计）、接口契约、内存设计、权限模型与运行时策略目录等文档。这标志着该项目从脚本集合走向有明确边界与不变式约束的工程化架构。
- 💡 **为何关注**: TradingAgents是LLM多智能体交易方向最受关注的开源项目之一，架构文档是理解并二次开发其代理协作机制的最佳入口。
- **标签**: quant x ai 交叉

---

## 信息源抓取状态

| 信息源 | 类型 | 侧别 | 状态 | 条数 | 备注 |
| --- | --- | --- | --- | --- | --- |
| [Quantocracy](https://quantocracy.com/feed/) | rss | quant | ❌ 失败 | 0 | 连接超时 |
| [Hugging Face Daily Papers](https://huggingface.co/papers/rss) | rss | ai | ❌ 失败 | 0 | 连接超时 |
| [r/algotrading](https://www.reddit.com/r/algotrading/) | reddit | quant | ❌ 失败 | 0 | HTTPSConnectionPool(host='www.reddit.com', port=443): Max retries exceeded with url: /r/algotrading/hot.json?limit=25 (C |
| [r/quant](https://www.reddit.com/r/quant/) | reddit | quant | ❌ 失败 | 0 | 连接超时 |
| [r/MachineLearning](https://www.reddit.com/r/MachineLearning/) | reddit | ai | ❌ 失败 | 0 | 连接超时 |
| arXiv q-fin | arxiv | quant | ✅ 成功 | 12 | — |
| arXiv AI+Finance 搜索 | arxiv | both | ✅ 成功 | 10 | — |
| Alpha Architect | rss | quant | ✅ 成功 | 5 | — |
| Quantitativo | rss | quant | ✅ 成功 | 10 | — |
| Last Week in AI (替代 The Batch) | rss | ai | ✅ 成功 | 10 | — |
| Import AI | rss | ai | ✅ 成功 | 10 | — |
| GitHub 项目动态 | github | both | ✅ 成功 | 1 | — |

*由 ai-quant-daily 自动生成。*