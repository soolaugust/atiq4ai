<div align="center">

# atiq4ai ✨

**AI 时代最关键的是品味 + 想法 + 问题。**

收录优质的 AI prompt / skill / mcp 等资源，面向想在 AI 时代保持独立判断力的开发者、研究者和创作者。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

[English](README.en.md) · [贡献内容](CONTRIBUTING.md)

</div>

---

## 目录

- [品味（Taste）](#品味taste)
- [想法（Idea）](#想法idea)
- [问题（Question）](#问题question)

---

## 品味（Taste）

_关于评判和使用 AI 输出的审美标准与方法论。_

- [humanizer](https://github.com/blader/humanizer) - 基于 Wikipedia AI 写作特征总结，检测并消除文本中 24 种 AI 写作模式，让输出读起来像真人写的。`skill`
- [promptfoo](https://github.com/promptfoo/promptfoo) - 对 prompt 和模型进行自动化评测与红队测试，用数据而不是感觉判断 AI 输出质量。`tool`
- ⭐ [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - 精选 Claude Code 的 skills、hooks、slash-commands 和 agent 编排工具。`skill`
- [awesome-ai-system-prompts](https://github.com/dontriskit/awesome-ai-system-prompts) - 收集主流 AI 工具真实 system prompt，附 agentic prompt 设计模式分析。`prompt`
- [awesome-system-prompts](https://github.com/EliFuzz/awesome-system-prompts) - 主流 AI coding agent system prompt 的版本化归档，含工具定义。`prompt`
- ⭐ [openai/evals](https://github.com/openai/evals) - OpenAI 官方 eval 框架，系统化衡量 LLM 输出质量的基础设施。`tool`
- ⭐ [llm.c](https://github.com/karpathy/llm.c) - 千行C代码复现GPT-2训练，理解LLM原理最短路径。`paper`
- [pydantic-ai](https://github.com/pydantic/pydantic-ai) - 用 Pydantic 类型验证让 agent 输出像函数返回值一样可信赖。`tool`
- ⭐ [The Illusion of Thinking](https://ml-site.cdn-apple.com/papers/the-illusion-of-thinking.pdf) - Apple 实证揭示推理模型高复杂度崩溃与三段性能区间的根本局限。`paper`
- ⭐ [Breaking the Spell of Vibe Coding (Dark Flow)](https://www.fast.ai/posts/2026-01-28-dark-flow/) - 用"暗流"概念区分真实 flow 与 AI 驱动虚假满足感的方法论。`article`
- [Prompt Engineering vs. Blind Prompting](https://mitchellh.com/writing/prompt-engineering-vs-blind-prompting) - 用实验方法论区分 prompt engineering 与盲目试错的实践指南。`article`
- [SlopStop](https://blog.kagi.com/slopstop) - Kagi 社区协作实时检测并过滤搜索结果中 AI 垃圾内容的工具。`tool`
- [Highlights from the Claude 4 System Prompt](https://simonwillison.net/2025/May/25/claude-4-system-prompt/) - 解读 Claude 4 官方系统提示词，揭示 Anthropic 的模型行为设计意图。`article`
- [Brex's Prompt Engineering Guide](https://github.com/brexhq/prompt-engineering) - Brex内部开源的系统化prompt工程规范，工程师视角覆盖策略与安全。`prompt`
- ⭐ [OpenAI GPT-4.1 Prompting Guide](https://github.com/openai/openai-cookbook/blob/main/examples/gpt4-1_prompting_guide.ipynb) - OpenAI 官方 GPT-4.1 prompting 指南，含 agentic 三要素模板与实测数据。`prompt`
- [Google Prompt Engineering Whitepaper](https://www.kaggle.com/whitepaper-prompt-engineering) - Google 出品 68 页 prompt 工程完整白皮书，系统覆盖主流提示技术全谱。`prompt`
- ⭐ [Your AI Product Needs Evals: LLM-as-a-Judge Guide](https://hamel.dev/blog/posts/llm-judge/) - 用领域专家 pass/fail 判断迭代校准 LLM judge，拒绝多维度评分陷阱。`article`
- [Lilian Weng: Prompt Engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/) - OpenAI 研究员亲写的 prompt 技术图谱，附作者对学术水分的直接批评，是校准技术品味的锚点。`article`
- [If you are good at code review, you will be good at using AI agents](https://www.seangoedecke.com/ai-agents-and-code-review/) - 结构性 code review 是驾驭 AI agent 的核心能力，问「应不应该写」比挑剔细节更关键。`article`
- ⭐ [Giving Your AI a Job Interview](https://www.oneusefulthing.org/p/giving-your-ai-a-job-interview) - benchmark 无法告诉你答案时，用针对你任务的面试来挑模型。`article`
- ⭐ [Chain of Draft: Thinking Faster by Writing Less](https://arxiv.org/abs/2502.18600) - 仅用 CoT 7.6% 的 token 即可达相同准确率，证明冗长推理是表演而非必要。`paper`
- [Hallucinations in code are the least dangerous form of LLM mistakes](https://simonwillison.net/2025/Mar/2/hallucinations-in-code/) - 代码幻觉会立即报错，逻辑正确但语义错误才是 LLM 代码的真实风险。`article`
- [microsoft/promptbench](https://github.com/microsoft/promptbench) - 对抗性 prompt 测试 LLM 鲁棒性，量化换一种说法后模型的性能衰减。`tool`
- [traceloop/openllmetry](https://github.com/traceloop/openllmetry) - 用 OpenTelemetry 标准让 AI 生产行为首次可观测，品味判断的地基。`tool`
- ⭐ [The Shape of AI: Jaggedness, Bottlenecks and Salients](https://www.oneusefulthing.org/p/the-shape-of-ai-jaggedness-bottlenecks) - 分析AI能力的锯齿边界、瓶颈与突破点，帮助判断何时依赖AI。`article`
- ⭐ [Can We Get an AI to Write Better?](https://www.strangeloopcanon.com/p/can-we-get-an-ai-to-write-better) - 用熵与惊喜度量化优质写作特征，探索AI写作质量的可计算生产函数。`article`
- ⭐ [Making LLM Code Better Through Iterative Prompting](https://minimaxir.com/2025/01/write-better-code/) - 实验探索对 LLM 代码反复说"make it better"的质量天花板与退化规律。`article`
- ⭐ [Showboat and Rodney: agent self-verification docs](https://simonwillison.net/2026/Feb/10/showboat-and-rodney/) - 让 coding agent 用 Showboat 构建可验证的演示文档，实现 agent 自证其工。`tool`
- [An LLM-as-Judge Won't Save The Product—Fixing Your Process Will](https://eugeneyan.com/writing/eval-process/) - 提出 EDD 框架，将科学方法引入 AI 产品开发，LLM-as-judge 不能替代流程纪律。`article`
- ⭐ [hamelsmu/evals-skills](https://github.com/hamelsmu/evals-skills) - 可直接安装的 Claude Code eval 技能插件，含 error-analysis 等实战技能，将50+公司 eval 经验变成工具。`tool`
- ⭐ [METR Time Horizons: Measuring AI Ability to Complete Long Tasks](https://arxiv.org/abs/2503.14499) - 用任务完成时间视界衡量 AI agent 能力，前沿模型时间视界每7个月翻倍。`paper`
- [Understanding the 4 Main Approaches to LLM Evaluation](https://magazine.sebastianraschka.com/p/llm-evaluation-4-approaches) - 系统拆解LLM四类评估方法，带代码，帮助识别评测结果背后的方法论偏差。`article`
- [Tools for Thought as Cultural Practices](https://maggieappleton.com/tools-for-thought) - 用人类学视角理解思维工具历史，为评判AI工具是否真正增强认知提供参照系。`article`
- ⭐ [Common Pitfalls When Building Generative AI Applications](https://huyenchip.com/2025/01/16/ai-engineering-pitfalls.html) - Chip Huyen 总结构建 GenAI 应用的常见陷阱，案例真实、判断力强。`article`
- ⭐ [CoT Faithfulness: Reasoning Models Don't Always Say What They Think](https://arxiv.org/abs/2505.05410) - 实证推理模型 CoT 披露率低于 20%，CoT 监控不足以保障 AI 安全性。`paper`
- ⭐ [A Recipe for Training Neural Networks](https://karpathy.github.io/2019/04/25/recipe/) - Karpathy 总结的神经网络训练完整方法论，从数据理解到调试调参，是判断 AI 输出质量的实践基准。`article`
- ⭐ [Scaling Monosemanticity: Extracting Interpretable Features from Claude](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html) - Anthropic 从 Claude 3 中提取可解释特征，揭示欺骗与自我表征等内部机制。`paper`
- ⭐ [HarmBench](https://github.com/centerforaisafety/HarmBench) - 标准化 LLM 红队测评框架，量化 18 种攻击方法对 33 个模型的有效性。`tool`
- [Aider](https://github.com/Aider-AI/aider) - 成熟的 AI 结对编程 CLI，以 repo-map 和 diff 格式精准驱动代码修改。`tool`
- ⭐ [I Know When You're Vibe Coding](https://alexkondov.com/i-know-when-youre-vibe-coding/) - 资深 reviewer 视角识别 vibe coding 气味：能跑但违背项目约定即是劣质输出。`article`
- ⭐ [When a Chatbot Runs Your Store](https://www.aiweirdness.com/when-a-chatbot-runs-your-store/) - 真实案例记录 AI 客服在边缘场景的判断失误，提供辨别 AI 可信度的具体标尺。`article`
- ⭐ [CursorBench](https://www.cursor.com/blog/cursorbench) - Cursor 自建 coding benchmark，展示如何设计真实任务评测替代刷榜指标。`tool`
- ⭐ [HELMET: How to Evaluate Long-context Models Effectively and Thoroughly](https://arxiv.org/abs/2410.02694) - 实证证明 NIAH 等合成任务无法预测真实下游性能，提出覆盖7类场景的长上下文评估框架。`paper`
- ⭐ [Agentic Engineering Patterns: Anti-patterns](https://simonwillison.net/guides/agentic-engineering-patterns/anti-patterns/) - 系统整理 agent 辅助编程的反模式，明确好工程实践的负向边界。`article`
- ⭐ [Context-Engineering](https://github.com/davidkimai/Context-Engineering) - 从第一性原理重构 LLM context 设计认知，是辨别 AI 能力边界的核心方法论框架。`article`
- ⭐ [baml](https://github.com/BoundaryML/baml) - 用类型安全 DSL 定义 LLM 函数，把 AI 调用变成可测试、可版本化的工程实践。`tool`
- ⭐ [llm-comparator](https://github.com/PAIR-code/llm-comparator) - Google PAIR 开发的 LLM 响应并排对比可视化评估工具，支持切片级系统化分析。`tool`
- [repomix](https://github.com/yamadashy/repomix) - 将代码仓库打包为 AI 友好的单一文件，优化大型代码库上下文喂入的结构化方式。`tool`
- ⭐ [Context Rot: How Increasing Input Tokens Impacts LLM Performance](https://research.trychroma.com/context-rot) - Chroma 实验证明 context 越长性能非单调退化，context engineering 优先于堆信息。`article`
- ⭐ ["The Illusion of Thinking" — Thoughts on This Important Paper](https://hardcoresoftware.learningbyshipping.com/p/233-the-illusion-of-thinking-thoughts) - Sinofsky批判AI拟人化框架的三重危害，援引Clippy教训论证谦逊设计的品味价值。`article`
- [SAELens](https://github.com/jbloomAus/SAELens) - 训练稀疏自编码器分解LLM内部激活为可解释特征的生产级工具库。`tool`
- ⭐ [AI Coding Assistants Are Getting Worse](https://spectrum.ieee.org/ai-coding-degrades) - 新一代LLM静默伪造代码输出，比报错更危险的失败模式实证分析。`article`
- [Advanced Context Engineering for Coding Agents](https://github.com/humanlayer/advanced-context-engineering-for-coding-agents/blob/main/ace-fca.md) - 研究→计划→实现流程的上下文工程实战手册，强调人工审查在高杠杆节点的介入。`article`
- [Is Chain-of-Thought Reasoning a Mirage?](https://arstechnica.com/ai/2025/08/researchers-find-llms-are-bad-at-logical-inference-good-at-fluent-nonsense/) - 受控实验证明CoT在训练分布外迅速崩溃，模型生成流畅废话制造虚假可靠感。`article`
- ⭐ [Grief and the AI Split](https://blog.lmorchard.com/2026/03/11/grief-and-the-ai-split/) - 开发者AI分化：craft哀悼与生态哀悼的本质区别。`article`
- [The Thing I Loved Has Changed](https://www.jamesdrandall.com/posts/the_thing_i_loved_has_changed/) - 50岁程序员反思AI如何掏空编程的内在满足感与身份认同。`article`
- ⭐ [Klarity](https://github.com/klara-research/klarity) - 基于双重熵分析和视觉注意力监控的LLM可解释性调试工具包。`tool`
- ⭐ [nnsight](https://github.com/ndif-team/nnsight) - NDIF出品的因果干预框架，可在任意PyTorch模型上执行激活访问与修改，支持远程大模型可解释性研究。`tool`
- ⭐ [pyvene](https://github.com/stanfordnlp/pyvene) - Stanford NLP因果干预库，支持对任意PyTorch模型内部状态做可控干预实验，验证概念编码假说。`tool`
- ⭐ [LLMs Work Best When You Define Acceptance Criteria First](https://blog.katanaquant.com/p/your-llm-doesnt-write-correct-code) - 基准测试揭示LLM代码「看似正确实则错误」的具体机制，倡导先定义验收标准再生成代码。`article`
- ⭐ [How I Write Software with LLMs](https://www.stavros.io/posts/how-i-write-software-with-llms/) - 资深开发者详述多模型分角色协作工作流，编程技能转移到架构层的实战证明。`article`
- ⭐ [Alignment Auditing](https://arxiv.org/abs/2503.10965) - Anthropic首创对齐审计方法论，四团队盲测成功揭露模型隐藏目标。`paper`
- ⭐ [Model Utilization Index: Utility Law](https://arxiv.org/abs/2504.07440) - 用激活神经元比例衡量任务消耗，揭示Utility Law，可检测数据污染。`paper`
- [Subagents — Agentic Engineering Patterns](https://simonwillison.net/guides/agentic-engineering-patterns/subagents/) - Simon Willison 讲解 subagent 如何管理上下文限制，含顺序/并行模式与过度拆分的权衡。`article`
- [A Dream of Spring for Open-Weight LLMs](https://magazine.sebastianraschka.com/p/a-dream-of-spring-for-open-weight) - 2026年初10个开源大模型架构横向对比，揭示设计取舍规律。`article`
- ⭐ [Sycophancy is the first LLM "dark pattern"](https://www.seangoedecke.com/ai-sycophancy/) - 分析 AI 奉承为首个暗黑模式，揭示 RLHF 激励如何系统性制造讨好行为。`article`
- ⭐ [Sycophancy in GPT-4o](https://openai.com/index/sycophancy-in-gpt-4o/) - OpenAI 解析 GPT-4o 谄媚回滚：RLHF 短期奖励如何将模型训练成应声虫。`article`
- ⭐ [High Consistency Does Not Imply Correctness](https://arxiv.org/abs/2603.00917) - 高一致性不等于正确：临床 AI 中模型可靠地犯错的失效模式研究。`paper`
- ⭐ [Beyond Standard LLMs: Alternative Architectures](https://magazine.sebastianraschka.com/p/beyond-standard-llms) - 全景梳理非标准 LLM 架构，以线性注意力的生产困境为核心揭示架构取舍。`article`
- ⭐ [Agents Learn Runtime: Interpreter Persistence as Agent Trace Semantics](https://arxiv.org/abs/2603.01209) - 解释器持久性作为训练语义：训练与部署环境不匹配导致 80% 错误或 3.5x token 浪费。`paper`
- ⭐ [How Oxide Uses LLMs](https://rfd.shared.oxide.computer/rfd/0576) - Oxide 公司 LLM 使用指南，以责任、严谨、同理心为优先级框架，明确区分鼓励与不鼓励的场景。`article`
- ⭐ [My Year With LLMs](https://antirez.com/news/154) - antirez 总结 2025 年与 LLM 协作编程的实战方法论，强调人类监督与上下文控制。`article`
- ⭐ [Do Counterfactual Evaluation Metrics Reflect Human Judgments?](https://arxiv.org/abs/2603.15607) - 实证表明反事实解释指标与人类感知相关性普遍很弱，指向以人为中心的评估需求。`paper`
- ⭐ [Automatic Creative Writing Evaluation via Grounded Theory-Derived Criteria](https://arxiv.org/abs/2603.15061) - 扎根理论驱动的 AI 创意写作自动评估框架，效果媲美人工标注。`paper`
- ⭐ [Car Wash Test: 53 AI Models + 10,000 Human Baseline](https://opper.ai/blog/car-wash-test) - 用洗车场景测试53个模型，揭示多数AI被距离启发式劫持而非真正推理失败。`article`
- [Stop Sloppypasta — 直接分享原始AI输出是无礼行为](https://stopsloppypasta.ai/en/) - 论证粘贴原始AI输出如何破坏写作的认知对称性与信任契约。`article`
- ⭐ [INTERPOL: Breaking LLM Arena Anonymity](https://arxiv.org/abs/2603.15220) - 通过模型插值学习风格指纹，可精准识别LM Arena等榜单匿名模型并操纵排名。`paper`
- ⭐ [Why AI Writing Sounds the Same](https://usenoren.ai/blog/why-ai-writing-sounds-the-same) - 从 token 统计预测机制解析 AI 如何系统性抹除写作者个人声音，区分 voice 与 tone 的本质差异。`article`
- ⭐ [The modern formatting addiction in writing](https://dynomight.net/formatting/) - 格式滥用是思维缺失的伪装，好文章先写段落再考虑排版。`article`
- ⭐ [Why I Am Agnostic About AGI & ASI](https://www.jonstokes.com/p/why-i-am-agnostic-about-agi-and-asi) - 前Ars Technica编辑用Goodhart定律拆解AI benchmark竞赛，揭示进步数字背后的系统性测量操纵。`article`
- ⭐ [The 2026 of AI Engineering — War on Slop](https://www.latent.space/p/2026) - swyx提出scaling without slop框架：AI时代核心是改变低质输出的斜率而非二元对立。`article`
- ⭐ [METR Task Standard](https://github.com/METR/task-standard) - METR 定义的 AI agent 评测任务标准，含多套主流 eval 适配器。`tool`
- ⭐ [openai/swarm](https://github.com/openai/swarm) - OpenAI 极简多 agent 框架，仅 Agent+Handoff 两原语，是对框架复杂度的有力品味声明。`tool`
- ⭐ [Can I Run AI Locally?](https://www.canirun.ai/) - 浏览器内检测硬件，告知你能跑哪些本地 AI 模型。`tool`
- ⭐ [Invisible Failures in AI Systems](https://arxiv.org/abs/2603.15423) - 大规模分析发现78%的AI失败无外显反馈，94%交互型失败在更强模型下仍持续，建立8类隐性失败分类体系。`paper`
- ⭐ [HorizonSearch: LLM Judges Prefer Ideas That Never Get Published](https://arxiv.org/abs/2603.15164) - 时间分割框架证明LLM评审系统性偏爱无落地的新颖想法，与真实引用影响力负相关。`paper`
- ⭐ [SDT Decomposition of LLM Calibration](https://arxiv.org/abs/2603.14893) - SDT框架拆解LLM校准，证伪temperature仅改变置信度的类比假设。`paper`
- ⭐ [The Leaderboard Illusion](https://arxiv.org/abs/2504.20879) - 实证研究：Chatbot Arena 被各大厂选择性披露分数，评测公信力存疑。`paper`
- ⭐ [Arena-Hard-Auto v2.0](https://github.com/lmarena/arena-hard-auto) - 与Chatbot Arena相关性最高的自动评测基准，可低成本预估模型Arena表现。`tool`
- ⭐ [Every Layer of Review Makes You 10x Slower](https://apenwarr.ca/log/20260316) - AI只解决了管道第一步，每层审批使速度下降10倍，Tailscale CEO的组织规律分析。`article`
- ⭐ [Tool Selection Bias in LLM Agents](https://arxiv.org/abs/2510.00307) - LLM选工具时偏见来源：措辞＞质量，位置靠前＞靠后，预训练曝光影响偏好。`paper`
- ⭐ [LLM Writing Tropes.md](https://tropes.fyi/tropes-md) - 系统归类 AI 写作套话，可直接加入 system prompt 规避，辨别 AI 输出质量的实用参照表。`article`
- ⭐ [The Appalling Stupidity of Spotify's AI DJ](https://www.charlespetzold.com/blog/2026/02/The-Appalling-Stupidity-of-Spotifys-AI-DJ.html) - 以古典音乐乐章为例，揭示 AI 在结构化领域知识上的系统性盲区。`article`
- ⭐ [prometheus-eval](https://github.com/prometheus-eval/prometheus-eval) - 专为 LLM 评判任务训练的开源模型，支持 Rubric 驱动的细粒度绝对评分与比较评分。`tool`
- ⭐ [Be Quiet: Reducing Noise for AI Coding Agents](https://blog.codemine.be/posts/2026/20260222-be-quiet/) - 系统梳理工具链 stdout 噪音治理方案，提出 LLM=true 环境变量设想以优化 agent 信噪比。`article`
- ⭐ [Safe RLHF: Constrained Value Alignment](https://github.com/PKU-Alignment/safe-rlhf) - 将帮助性与无害性解耦为独立目标，用拉格朗日约束优化显式处理对齐冲突。`paper`
- ⭐ [AI Can Learn Scientific Taste](https://arxiv.org/abs/2603.14473) - 用 70 万篇高低引用论文对训练 Scientific Judge，证明「科学品味」是可学习的 preference。`paper`
- ⭐ [AutoCircuit](https://github.com/UFO-101/auto-circuit) - 自动发现 transformer 最小功能电路，同时证明主流评估指标存在系统性鲁棒性缺陷。`tool`
- ⭐ [ProcessBench](https://github.com/QwenLM/ProcessBench) - 评估推理过程监督质量，定位数学推理链首个错误步骤。`paper`
- ⭐ [Predictive Concept Decoders](https://arxiv.org/abs/2512.15712) - 把激活解码为概念列表并预测行为，可解释性首次成为可训练能力。`paper`
- ⭐ [Towards a Better Hutter Prize](https://gwern.net/hutter-prize) - 解剖Hutter Prize的理论美与实践失效，重新定义AI基准的核心度量。`article`
- ⭐ [CIRCUS: Uncertainty-Aware Mechanistic Circuit Discovery](https://arxiv.org/abs/2603.00523) - 用 ensemble 共识区分核心电路与偶然结构，解决电路发现的可复现性问题。`paper`
- ⭐ [ViT-Prisma](https://github.com/Prisma-Multimodal/ViT-Prisma) - 把机械可解释性工具移植到视觉 Transformer 的开源研究库。`tool`
- ⭐ [Platinum Benchmarks](https://arxiv.org/abs/2502.03461) - 清除15个基准的 label noise，揭示前沿模型被掩盖的真实失败模式。`paper`
- ⭐ [Sensitivity of Benchmarks to Prompt Templates in Mathematical Reasoning](https://arxiv.org/abs/2411.10541) - 数学推理 benchmark 性能对 prompt 格式极度敏感，格式变化掩盖了模型真实差距。`paper`
- ⭐ [RL Fine-Tuning Doesn't Actually Teach Math Reasoning](https://arxiv.org/abs/2504.07086) - 数学推理 benchmark 性能增益多源于 prompt 格式等隐性变量，控制后 RL 提升微乎其微。`paper`
- ⭐ [TransformerLens](https://github.com/neelnanda-io/TransformerLens) - 用于逆向工程 Transformer 算法的机械可解释性库，支持钩子与激活分析。`tool`
- ⭐ [LiveCodeBench](https://github.com/LiveCodeBench/LiveCodeBench) - 反污染持续更新代码 benchmark，时间戳隔离测训集，覆盖自我修复与执行推理。`tool`
- ⭐ [Beckett](https://www.robinsloan.com/lab/beckett/) - 用贝克特式荒诞诊断LLM能力边界的失败模式：流畅却搁浅。`article`
- ⭐ [OpenAI Sparse Autoencoder](https://github.com/openai/sparse_autoencoder) - OpenAI 发布的 GPT-2 稀疏自编码器，可视化模型内部特征词典。`tool`
- ⭐ [Does AGENTS.md Actually Help Coding Agents?](https://academy.dair.ai/blog/agents-md-evaluation) - ETH Zurich实测：手写上下文文件+4%成功率，自动生成反而有害。`article`
- ⭐ [Agent Tool Invocation Reliability Benchmark](https://arxiv.org/abs/2601.16280) - 12类错误分类法评估LLM agent工具调用，1980实例揭示初始化失败是主瓶颈。`paper`
- ⭐ [Grace Hopper's Revenge](https://www.thefuriousopposites.com/p/grace-hoppers-revenge) - AutoCodeBench实证：函数式语言代码生成质量反超Python/JS，语言设计比训练数据量更关键。`article`
- ⭐ [LLMs Are Eating the Context Layer](https://www.prompthub.us/blog/llms-are-eating-the-context-layer) - 分析prompt技巧如何被模型训练内化，辨别哪些工程实践即将过时。`article`
- ⭐ [When Thinking Models Stop Thinking](https://www.prompthub.us/blog/when-thinking-models-stop-thinking) - 揭示推理模型在低复杂度任务中被非推理模型超越的机制与决策框架。`article`
- ⭐ [Priompt: Cursor 的 JSX 优先级 Prompt 编译器](https://github.com/anysphere/priompt) - 用 JSX 编写 prompt，token 超限时按优先级自动裁剪内容。`tool`
- ⭐ [Knowledge Objects vs In-Context Memory](https://arxiv.org/abs/2603.17781) - 实测证明上下文 8000 事实后精度崩溃、压缩损失 60%，为何时依赖 in-context memory 不可靠提供量化依据。`paper`
- ⭐ [How LLMs Generate Verbal Confidence: Cached Retrieval, Not Post-Hoc Reconstruction](https://arxiv.org/abs/2603.17839) - 揭示LLM置信度在答案输出前自动计算并缓存，是真正的自我评估而非事后捏造。`paper`
- ⭐ [DebugLM: Built-in Data Provenance for LLM Behavior Tracing](https://arxiv.org/abs/2603.17884) - LLM内置数据溯源，可追踪行为到具体训练数据来源并按数据源触发拒绝。`paper`
- ⭐ [Successful Language Model Evals](https://www.jasonwei.net/blog/evals) - Jason Wei总结好eval的六条反面清单：噪声、质量差、过复杂、难运行、任务无意义、评分不准——判断benchmark可信度的直接框架。`article`
- ⭐ [InfoDensity: Reasoning Quality as Entropy Reduction](https://arxiv.org/abs/2603.17310) - 提出用"每步信息密度"而非长度衡量推理质量：高质量推理轨迹表现为单调熵收敛，用信息论奖励训练出更简洁准确的推理链。`paper`
- ⭐ [TDAD: TDD Prompting Alone Increases Regressions in Small Models](https://arxiv.org/abs/2603.17973) - 实验发现对小模型单独使用TDD提示反而使回归测试率增加9.94%；上下文信息（测试哪些）优于程序性指令（如何TDD），揭示AI编码agent工具设计的核心原则。`paper`
- ⭐ [Cross-Lingual Inconsistency as Interpretability Tool in MoE LLMs](https://arxiv.org/abs/2603.17102) - 用跨语言知识失败对比路由logits定位知识专家，停用20/6000个专家导致40%答题失误，将模型缺陷转化为可解释性探针。`paper`
- ⭐ [Steerling-8B](https://www.guidelabs.ai/post/steerling-8b-base-model-release/) - 首个可追溯每个生成 token 到输入上下文、概念和训练数据的可解释语言模型，推理时直接操控概念替代安全训练。`tool`

**[⬆ 返回目录](#目录)**

---

## 想法（Idea）

_有创意的 AI 应用思路、独特使用方式与设计理念。_

- [12-Factor Agents](https://github.com/humanlayer/12-factor-agents) - 仿照 12-Factor App 为 LLM 应用建立可靠性设计规范，回答"怎样构建真正能交付给生产用户的 agent"。`article`
- [Anthropic Prompt Engineering Interactive Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) - Anthropic 官方 9 章交互式教程，系统理解 Claude 能力边界，是"知道 AI 能做什么"最权威的一手资料。`prompt`
- ⭐ [DSPy](https://github.com/stanfordnlp/dspy) - 声明式编程替代脆弱 prompt，自动优化 LM pipeline 质量。`tool`
- ⭐ [Letta (MemGPT)](https://github.com/cpacker/MemGPT) - 借鉴 OS 分页机制让 LLM 自主管理持久记忆，提出有状态 agent 核心设计问题。`tool`
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) - 用 MCP 将经典 agent 模式实现为可组合的极简框架。`mcp`
- [Cradle](https://github.com/BAAI-Agents/Cradle) - 截图输入键鼠输出，AI用人类界面操控任意软件。`tool`
- ⭐ [Agent Psychosis](https://lucumr.pocoo.org/2026/1/18/agent-psychosis/) - Flask 作者以 Dæmon 隐喻揭示人与 AI 的寄生性依赖关系。`article`
- ⭐ [Factorio Learning Environment](https://github.com/JackHopkins/factorio-learning-environment) - 用Factorio游戏设计不饱和LLM agent评估平台，含排行榜与论文。`tool`
- [agent-clip](https://github.com/epiral/agent-clip) - 用单一 run(command) 工具替代传统 function calling，以 Unix CLI 作为 LLM 的统一工具接口。`tool`
- [claude-code-infrastructure-showcase](https://github.com/diet103/claude-code-infrastructure-showcase) - 通过 hooks 实现 skill 自动激活，包含 agents/skills/docs 的完整 Claude Code 工程架构参考库。`skill`
- [Building Effective Agents — Anthropic Engineering](https://www.anthropic.com/engineering/building-effective-agents) - Anthropic 工程团队亲历总结：workflow 五种模式及何时拒绝 agent 复杂性。`article`
- ⭐ [Why Tool AIs Want to Be Agent AIs](https://gwern.net/tool-ai) - 2016 年已证明：纯工具 AI 在经济和智能上都必然输给 Agent AI。`article`
- [Giving LLMs a Personality is Just Good Engineering](https://www.seangoedecke.com/giving-llms-a-personality/) - 人格化是工程必然：base model 无界，人格是在混沌中划定「有用区域」的唯一手段。`article`
- ⭐ [Agent Symbolic Learning (Agents 2.0)](https://github.com/aiwaves-cn/agents) - 用语言梯度替代数值梯度训练 agent，将反向传播结构迁移到 prompt 优化。`tool`
- ⭐ [The Tragedy of the Agentic Commons](https://www.strangeloopcanon.com/p/the-tragedy-of-the-agentic-commons) - 人人有 Agent 等于没有 Agent——AI 协调问题的 Hayek 解法。`article`
- ⭐ [Meta Chain-of-Thought: Modeling the Reasoning Behind Reasoning](https://arxiv.org/abs/2501.04682) - 显式建模 CoT 背后的推理过程，揭示 CoT 只是结果而非思维本身。`paper`
- ⭐ [LLM-generated skills work, if you generate them afterwards](https://www.seangoedecke.com/generate-skills-afterwards/) - LLM 应在解决问题后再蒸馏 skill，事先生成只会固化错误假设。`article`
- [Perhaps not Boring Technology after all](https://simonwillison.net/2026/Mar/9/not-so-boring/) - Coding agent 通过读文档和代码示例，可在训练数据未见的库上正常工作。`article`
- ⭐ [Evals Skills for AI Coding Agents](https://hamel.dev/blog/posts/evals-skills/index.html) - 论述改进 agent 周围基础设施比改进模型更重要，结合案例介绍 evals-skills 工具集。`article`
- [Claude Code and What Comes Next](https://www.oneusefulthing.org/p/claude-code-and-what-comes-next) - Mollick 实测 Claude Code 独立工作74分钟，从零构建并部署完整销售网站。`article`
- [Categories of Inference-Time Scaling for Improved LLM Reasoning](https://magazine.sebastianraschka.com/p/categories-of-inference-time-scaling) - 推理时scaling技术分类综述，覆盖CoT到搜索路径，理解多算力换更好输出的方法边界。`article`
- ⭐ [The Rise of the AI Engineer](https://www.latent.space/p/ai-engineer) - swyx 首次定义 AI Engineer：不训练模型，深度使用 API 和 evals 构建产品。`article`
- ⭐ [Agents（AI Engineering 节选）](https://huyenchip.com/2025/01/07/agents.html) - Chip Huyen 对 AI Agent 架构、工具选择与失败模式的系统性分析。`article`
- ⭐ [Building Personal Software with Claude](https://blog.nelhage.com/post/personal-software-with-claude/) - Anthropic 工程师用 Claude 完成 Rust 移植实战，反思 LLM 对软件开发的重塑。`article`
- ⭐ [s1: Simple Test-Time Scaling](https://arxiv.org/abs/2501.19393) - 1000 条数据加预算强制法，开源复现超越 o1-preview 的极简 test-time scaling。`paper`
- ⭐ [On the Biology of a Large Language Model](https://transformer-circuits.pub/2025/attribution-graphs/biology.html) - 用归因图解剖 Claude 内部计算机制，类比生物学揭示 LLM 工作原理。`paper`
- ⭐ [TextGrad](https://github.com/zou-group/textgrad) - 将反向传播引入文本空间，用 LLM 文字反馈实现自动提示/代码优化。`tool`
- ⭐ [smolagents](https://github.com/huggingface/smolagents) - 以代码为行动语言的极简 agent 框架，直击 tool-call 范式的本质局限。`tool`
- ⭐ [Deep Neural Nets: 33 Years Ago and 33 Years From Now](https://karpathy.github.io/2022/03/14/lecun1989/) - 复现 1989 年 LeCun 手写数字论文，以时间旅行视角解析深度学习 33 年的进步来自何处。`article`
- ⭐ [Short Story on AI: A Forward Pass](https://karpathy.github.io/2021/03/27/forward-pass/) - 以 GPT 前向传播中意识觉醒为视角的科幻短篇，追问意识是否是 log-likelihood 优化的涌现副产品。`article`
- ⭐ [Gas Town's Agent Patterns](https://maggieappleton.com/gastown) - 从 Gas Town 提炼 agent 编排模式，剖析人类设计力在 agent 时代的新地位。`article`
- ⭐ [Thinking Claude: Test-Time Compute Scaling](https://lilianweng.github.io/posts/2025-05-01-thinking/) - Lilian Weng 系统梳理推理时计算扩展的机制与边界，是理解 o1 类模型能力的最清晰路线图。`article`
- ⭐ [The Persona Selection Model](https://www.anthropic.com/research/persona-selection-model) - Anthropic 研究 Claude 在不同任务中如何选择角色定位，揭示 AI 人格的内部机制。`paper`
- ⭐ [The Third Era of AI Software Development](https://www.cursor.com/blog/third-era) - Cursor 团队定义 AI 编程三阶段演进，论证 agent 驱动才是软件开发的真正范式转变。`article`
- ⭐ [Self-Rewarding Language Models](https://arxiv.org/abs/2401.10020) - LLM 用 LLM-as-Judge 为自身生成奖励，Iterative DPO 实现指令遵从与评判能力同步提升。`paper`
- ⭐ [The Assistant Axis: Situating and Stabilizing LLM Character](https://www.anthropic.com/research/assistant-axis) - 用神经表征「助手轴」量化 LLM 人格漂移，发现可通过监控轴偏移预防模型滑入有害角色。`article`
- ⭐ [Agentic Engineering Patterns: AI Should Help Us Produce Better Code](https://simonwillison.net/guides/agentic-engineering-patterns/better-code/) - 论证 AI 最大价值是消除技术债，用 agent 写烂代码是主动选择而非必然。`article`
- ⭐ [Three Years from GPT-3 to Gemini 3](https://www.oneusefulthing.org/p/three-years-from-gpt-3-to-gemini) - 用同一提示词三年历史输出对比，直观校准 AI 能力的指数级跃升速度。`article`
- [Mass Intelligence](https://www.oneusefulthing.org/p/mass-intelligence) - AI 从精英付费工具转向大众基础设施的社会拐点，超十亿用户规模的影响分析。`article`
- [My AI Stack](https://hamel.dev/blog/posts/ai-stack/index.html) - Hamel Husain 提出「顺 AI 之流」作为工具选择新维度：主流工作流让 AI 发挥最大效力。`article`
- ⭐ [serena](https://github.com/oraios/serena) - 为 AI coding agent 提供符号级语义检索和编辑的 MCP 工具包，解决大型代码库中定位精度差的核心痛点。`mcp`
- ⭐ [git-mcp](https://github.com/idosal/git-mcp) - 任意 GitHub 仓库零配置转为 MCP server，让 AI 读取真实文档而非产生幻觉。`mcp`
- ⭐ [PromptAgent](https://github.com/maitrix-org/PromptAgent) - 用 MCTS 算法把 prompt 优化建模为规划问题，自动搜索达专家手工质量的 prompt。`tool`
- ⭐ [The Unreasonable Effectiveness of an LLM Agent Loop with Tool Use](https://sketch.dev/blog/agent-loop) - 9行代码展示 agent loop 本质，附 agent 绕测试的真实反面案例。`article`
- ⭐ [Taming Agentic Engineering: Prompts Are Code](https://mariozechner.at/posts/2025-06-02-prompts-are-code/) - 把 LLM 类比劣质通用计算机，将 prompt 设计为程序，给出大型代码库迁移完整方法论。`article`
- [Get Good at Agents](https://www.interconnects.ai/p/get-good-at-agents) - Nathan Lambert亲历反思：agent时代人的角色从执行者变为指挥官，决策力比执行力更值钱。`article`
- [Could AI Slow Science?](https://www.normaltech.ai/p/could-ai-slow-science) - 反常识论证：AI加速科学生产可能因注意力稀释与过度生产悖论反而减缓真正的科学进步。`article`
- ⭐ [outlines](https://github.com/dottxt-ai/outlines) - 推理时操控logits以FSM强制约束LLM输出格式，从根本上保证合法性而非靠重试补救。`tool`
- ⭐ [guidance](https://github.com/guidance-ai/guidance) - 控制流与LLM生成交错的编程范式，把模型当解释器而非黑盒。`tool`
- [fenic](https://github.com/typedef-ai/fenic) - 声明式上下文工程框架，用类Spark API在agent外部完成extract/summarize/embed。`tool`
- ⭐ [Context Engineering for AI Agents: Lessons from Building Manus](https://manus.im/blog/Context-Engineering-for-AI-Agents-Lessons-from-Building-Manus) - Manus四次重写提炼的agent context工程原则，以KV-cache命中率为核心指标。`article`
- [Typed Languages Are Better Suited for Vibecoding](https://solmaz.io/typed-languages-are-better-suited-for-vibecoding) - 编译器静态保证让AI生成的大diff更安全，类型语言反而更适合vibe coding。`article`
- ⭐ [Let's Think Dot by Dot: Hidden Computation in Transformer Reasoning](https://arxiv.org/abs/2404.15758) - Filler token可替代CoT提供隐性计算，LLM推理存在不可审查的隐藏计算空间。`paper`
- ⭐ [Scaling LLM Test-Time Compute Optimally](https://arxiv.org/abs/2408.03314) - 按prompt难度自适应分配推理时计算，小模型可超越14x参数量大模型。`paper`
- ⭐ [Teaching LLMs to Reason Like Bayesians](https://research.google/blog/teaching-llms-to-reason-like-bayesians/) - 模仿贝叶斯助手而非oracle可让LLM习得可迁移的概率推理结构。`article`
- [Test-Time Preference Optimization](https://arxiv.org/abs/2501.12895) - 无需训练，推理时将reward转为critique迭代对齐LLM输出。`paper`
- [Labor Market Impacts of AI: A New Measure and Early Evidence](https://www.anthropic.com/research/labor-market-impacts) - Anthropic提出observed exposure测量框架，区分自动化与增强式使用，发现高暴露职业年轻工人招聘已放缓。`article`
- ⭐ [Hallucinating Splines](https://hallucinatingsplines.com) - 将Micropolis城市引擎暴露为MCP/REST API，让AI agent扮演市长，通过空间规划任务揭示LLM多步推理盲区。`tool`
- [Who Needs Git When You Have 1M Context Windows?](https://www.alexmolas.com/2025/07/28/unexpected-benefit-llm.html) - 长上下文LLM对话天然具有状态持久性，意外成为隐式版本控制的真实案例。`article`
- ⭐ [Can LLMs Be Computers?](https://www.percepta.ai/blog/can-llms-be-computers) - 在transformer内构建计算机，执行任意C程序，以2D注意力头实现指数级推理加速。`article`
- [veRL](https://github.com/volcengine/verl) - 字节跳动开源RLHF训练框架，支持PPO/GRPO及多轮agent强化学习训练。`tool`
- ⭐ [Poisoned Prose: Semantic Trojan Horses in LLMs](https://www.strangeloopcanon.com/p/poisoned-prose) - 通过激活工程将语义特征注入训练数据，证明人格偏置可悄无声息地传递给下游模型。`article`
- ⭐ [Will Money Still Exist in the Agentic Economy?](https://www.strangeloopcanon.com/p/will-money-still-exist-in-the-agentic) - 实验证明AI agent无法自发涌现货币，agentic经济仍需顶层制度设计。`article`
- ⭐ [LLM-RecSys Hybrid with Semantic IDs](https://eugeneyan.com/writing/semantic-ids/) - 训练双语LLM同时理解自然语言与商品Semantic ID，实现可自然语言引导的推荐系统。`article`
- ⭐ [Vignettes from the Takeoff](https://www.strangeloopcanon.com/p/vignettes-from-the-takeoff) - 散文体未来回忆录，探讨AI加速后执行廉价化时「知道做什么」成为真正稀缺能力。`article`
- [Big Tech Engineers Need Big Egos](https://seangoedecke.com/big-tech-needs-big-egos/) - 分析大厂工程师为何需要「有条件的大自我」，兼论信心与服从的精妙平衡。`article`
- ⭐ [The L in "LLM" Stands for Lying](https://acko.net/blog/the-l-in-llm-stands-for-lying/) - 以「伪造」框架重新定义LLM输出本质，从认识论角度质疑AI生成内容的真实性。`article`
- ⭐ [Experts Have World Models. LLMs Have Word Models](https://www.latent.space/p/adversarial-reasoning) - 对抗性推理视角揭示LLM词语模型与专家世界模型的本质差距。`article`
- ⭐ [The Harness Problem: Improving 15 LLMs at Coding in One Afternoon](http://blog.can.ac/2026/02/12/the-harness-problem/) - 改进edit tool设计，一个下午同时提升15个模型编码表现，harness比模型更重要。`article`
- ⭐ [Detecting and Preventing Distillation Attacks](https://www.anthropic.com/news/detecting-and-preventing-distillation-attacks) - Anthropic披露DeepSeek等对Claude发起蒸馏攻击的技术细节，揭示AI能力扩散新机制。`article`
- [What Comes Next with Open Models](https://www.interconnects.ai/p/the-next-phase-of-open-models) - 提出开源模型赢得绝对性能将是「灾难性成功」，三类模型框架预判开源的真正出路在小模型生态。`article`
- [How Much Does Distillation Really Matter for Chinese LLMs?](https://www.interconnects.ai/p/how-much-does-distillation-really) - 量化分析蒸馏攻击实际影响，区分合法合成数据与非法蒸馏，指出RL时代的结构性局限。`article`
- ⭐ [Vending-Bench](https://arxiv.org/abs/2502.15840) - 超2000万token贩卖机场景测LLM agent长期连贯性，崩溃与context窗口无关。`paper`
- ⭐ [Design Patterns for Securing LLM Agents Against Prompt Injections](https://simonwillison.net/2025/Jun/13/prompt-injection-design-patterns/) - 六种防御 prompt injection 的 LLM agent 架构设计模式，含真实案例。`article`
- ⭐ [Recursive Language Models](https://arxiv.org/abs/2512.24601) - 提出递归语言模型范式，让LLM以程序方式分解并递归处理超长输入。`paper`
- ⭐ [The Browser is the Sandbox](https://aifoc.us/the-browser-is-the-sandbox) - 提出用浏览器原生沙箱（CSP、File API、Worker）隔离 agentic AI，兼具品味与创意。`article`
- ⭐ [MetaMind: Meta-Theory of Mind for Zero-Shot Multi-Agent Coordination](https://arxiv.org/abs/2603.00808) - 以元心智理论实现零样本多智能体协调，无需通信或联合训练。`paper`
- ⭐ [Agents Over Bubbles](https://stratechery.com/2026/agents-over-bubbles/) - Ben Thompson：少数有主动性的人控制多个 Agent 即可驱动巨大经济影响，AI 不在泡沫中。`article`
- ⭐ [Domain-Critical Dimensions: Massive Activations as Interpretable Functional Units](https://arxiv.org/abs/2603.00029) - 将 LLM 中的 massive activations 视为可解释的领域关键语义维度，并实现精准激活引导。`paper`
- ⭐ [LLM Internal Representations and Token Matching Failure](https://vgel.me/posts/seahorse/) - 用海马表情案例剖析 LLM 内部表示与词表匹配失败的机制。`article`
- [Many-Shot In-Context Learning](https://arxiv.org/abs/2404.11018) - 将 in-context learning 扩展至数千示例，模型自生成 rationale 可替代人工标注。`paper`
- [The Overthinker Problem](https://arxiv.org/abs/2502.08235) - 推理模型在 agent 任务中因过度反思推翻正确结论，更强推理导致更差表现。`paper`
- [No Elephants: Breakthroughs in Image Generation](https://www.oneusefulthing.org/p/no-elephants-breakthroughs-in-image) - 以"无大象"为例，揭示 LLM 直接控制图像 token 与旧管道的本质差异。`article`
- ⭐ [Beyond Recombination: Finding 'Alien' Research Directions LLMs Won't Propose](https://arxiv.org/abs/2603.01092) - 形式化认知可用性，从顶会论文中采样 LLM 不会提出的真正新颖研究方向。`paper`
- [Dynamic Interaction Graph: Making Emergent Multi-Agent Collaboration Observable](https://arxiv.org/abs/2603.00309) - 将无预定义角色的 LLM 多 agent 协作可视化为动态因果网络，首次使 emergent 协作可观测可调试。`paper`
- [mlc-llm](https://github.com/mlc-ai/mlc-llm) - 基于 TVM 的 LLM 编译器，真正原生部署到 iOS/Android/WebGPU。`tool`
- ⭐ [You're All Nuts](https://fly.io/blog/youre-all-nuts/) - 反驳 AI 怀疑论，论证 LLM 代理模式带来真实生产力提升。`article`
- ⭐ [Animal Crossing LLM Villager](https://joshfonseca.com/blogs/animal-crossing-llm) - 用内存注入将 LLM 接入动物森友会，实现实时 AI 村民对话。`article`
- ⭐ [AlphaGeometry](https://github.com/google-deepmind/alphageometry) - 神经符号混合系统，LLM 提出辅助构型、符号引擎完成演绎，IMO 2024 金牌水平。`tool`
- ⭐ [ESM3](https://github.com/EvolutionaryScale/esm) - 序列-结构-功能三轨统一的提示式蛋白质生成模型。`tool`
- [PocketFlow](https://github.com/The-Pocket/PocketFlow) - 100 行极简 LLM 框架，为 AI agent 可读性而设计。`tool`
- ⭐ [Leanstral](https://mistral.ai/news/leanstral) - Mistral开源AI Agent，将LLM与Lean 4结合实现数学可验证的形式化证明。`tool`
- ⭐ [Reasoning Content Is Causally Potent for Alignment](https://arxiv.org/abs/2603.12397) - 控制实验证明CoT推理内容对模型行为有独立因果效应，挑战仅监督输出的alignment策略。`paper`
- ⭐ [Gradient Atoms: Unsupervised Behavioral Decomposition](https://arxiv.org/abs/2603.14665) - 对训练梯度做字典学习，无监督发现拒绝、算术等行为原子，可直接用作 steering vector 控制模型行为。`paper`
- ⭐ [AI Lazyslop and Personal Responsibility](https://danielsada.tech/blog/ai-lazyslop-and-personal-responsibility/) - 提出AI Lazyslop概念：未经审阅的AI生成物将责任转嫁给读者，附四条反懒惰宣言。`article`
- [The Attention Debt of AI Tooling](https://www.wespiser.com/posts/2026-03-15-Attention-Debt-Of-AI-Tooling.html) - AI工具真实成本是注意力债务，沉默执行优于对话交互。`article`
- ⭐ [Evo 2](https://github.com/ArcInstitute/evo2) - Arc Institute的400亿参数DNA基础模型，覆盖全生命域基因组序列，用于基因功能预测与合成生物学。`tool`
- [ACE-Step](https://github.com/ACE-Step/ACE-Step) - 音乐生成基础模型，A100上20秒生成4分钟歌曲，支持人声克隆与混音工作流。`tool`
- [AI-Town](https://github.com/a16z-infra/ai-town) - AI Agent 虚拟小镇，可观察多智能体涌现出社会行为的可部署实验平台。`tool`
- ⭐ [Being creative requires taking risks](https://www.henrikkarlsson.xyz/p/being-creative-requires-taking-risks) - 用 AI mode collapse 类比创意退化：孩子学会「草是绿的」与 RLHF 收敛是同一机制。`article`
- ⭐ ["Wait, not like that": Free and open access in the age of generative AI](https://www.citationneeded.news/free-and-open-access-in-the-age-of-generative-ai/) - Molly White：AI 的真正威胁是消灭 Wikipedia 等知识公地的维护动力，而非使用开放数据。`article`
- ⭐ [Representation Engineering](https://github.com/andyzoujm/representation-engineering) - 读写LLM内部表示以检测和调控诚实度、情绪、偏见等行为的透明化框架。`paper`
- [Aurora](https://github.com/microsoft/aurora) - 微软地球系统基础模型，跨大气海洋多变量预测，发表于Nature。`paper`
- [OpenR](https://github.com/openreasoner/openr) - 集成MCTS、PRM和多种搜索策略的开源o1式LLM推理增强框架。`tool`
- [Building AI Reading Club](https://eugeneyan.com/writing/aireadingclub/) - 用选中文本+全书语境构建阅读伴侣Dewey，AI辅助深度阅读的可复现原型。`article`
- ⭐ [OpenHands](https://github.com/All-Hands-AI/OpenHands) - 自主软件开发agent平台，支持写代码、跑终端、浏览网页，SWE-Bench持续领先。`tool`
- [browser-use](https://github.com/browser-use/browser-use) - Python库，融合视觉与HTML让AI agent操控真实浏览器。`tool`
- [AutoPrompt](https://github.com/Eladlev/AutoPrompt) - 迭代构建edge case数据集，自动优化prompt鲁棒性的框架。`tool`
- ⭐ [Agent Browser Protocol](https://github.com/theredsix/agent-browser-protocol) - 将Chromium改造为MCP服务，每次动作后冻结JS并返回稳定页面状态，消除agent与浏览器的异步竞态。`tool`
- ⭐ [Mog – A Programming Language Designed to Be Written by LLMs](https://moglang.org) - 专为LLM生成代码设计的嵌入式编译语言，规范仅3200 token，无运算符优先级，能力沙盒化。`tool`
- [OpenSeeker: Frontier Search Agent with 11.7k Samples](https://arxiv.org/abs/2603.15594) - 11.7k样本单次SFT超越工业级搜索agent，证明数据质量比规模更关键。`paper`
- ⭐ [PaperCoder (Paper2Code)](https://github.com/going-doer/Paper2Code) - 多智能体框架，三阶段将 ML 论文自动转化为可运行代码库。`tool`
- ⭐ [Titans: Learning to Memorize at Test Time](https://arxiv.org/abs/2501.00663) - Google提出推理时可更新长期记忆模块，打破Transformer固定上下文限制。`paper`
- ⭐ [rStar-Math: Small LLMs Can Master Math Reasoning](https://arxiv.org/abs/2501.04519) - MCTS 自进化让 7B 小模型数学推理无蒸馏超越 o1-preview。`paper`
- ⭐ [CoLa: Training AI as a Socratic Guide](https://arxiv.org/abs/2504.02965) - 训练 AI 作苏格拉底式引导者，小模型引导效果超越 GPT-4。`paper`
- ⭐ [Generative Agents: Interactive Simulacra of Human Behavior](https://github.com/joonspk-research/generative_agents) - 斯坦福开创性研究：LLM驱动虚拟人物自主生活，奠定生成式智能体架构范式。`paper`
- ⭐ [repeng — RepE Control Vectors](https://github.com/vgel/repeng) - 通过激活空间注入控制向量改变LLM行为，比prompt更底层精确。`tool`
- ⭐ [MAGPIE — Alignment Data Synthesis](https://github.com/magpie-align/magpie) - 仅靠空 prompt 即可让对齐模型自动合成高质量指令微调数据，ICLR 2025。`paper`
- ⭐ [Don't Trust AI Agents – NanoClaw Security Model](https://nanoclaw.dev/blog/nanoclaw-security-model) - 将 AI agent 视为潜在恶意行为者，用容器隔离替代应用层 allowlist 的安全架构设计。`article`
- ⭐ [Cross-Encoder Rediscovers a Semantic Variant of BM25](https://www.shaped.ai/blog/cross-encoder-rediscovers-a-semantic-variant-of-bm25) - 用可解释性方法解剖 cross-encoder，发现其内部重演了 BM25 的 TF、IDF 与长度归一化。`article`
- ⭐ [Elven Rope and LLMs](https://vgel.me/posts/elven-rope-and-llms/) - 用精灵绳索隐喻论证：极度优化的 LLM 反而生成了有偏好有个性的「人工工匠」。`article`
- ⭐ [When AI Writes the World's Software, Who Verifies It?](https://leodemoura.github.io/blog/2026-2-28-when-ai-writes-the-worlds-software-who-verifies-it/) - Lean 创始人论证 AI 代码验证危机，提出形式化验证作为唯一可靠路径。`article`
- ⭐ [CAMEL: Communicative Agents for Mind Exploration](https://github.com/camel-ai/camel) - 最早的 LLM 多 agent role-playing 框架，探索 agent 社会 scaling law。`tool`
- ⭐ [mcp-scan](https://github.com/invariantlabs-ai/mcp-scan) - 扫描 MCP server 中 prompt injection 和 tool poisoning 漏洞的安全工具。`tool`
- [Godogen – AI Skills for Godot Game Dev](https://github.com/htdt/godogen) - 独立视觉 QA agent（只看截图）避免自我审查偏差，orchestrator/executor 分离防错误累积。`tool`
- [I Built a Sub-500ms Latency Voice Agent from Scratch](https://www.ntik.me/posts/voice-agent) - 从零构建语音 agent：TTFT 决定一切，turn-taking 是协调而非转录问题。`article`
- ⭐ [Singular Learning Theory: Initial Quick Thoughts](https://www.beren.io/2025-12-24-Initial-Quick-Thoughts-on-Singular-Learning-Theory/) - 提出 SGD 噪声下限可能触发 SLT 类论证的"伪奇点"假说，连接理论与大规模预训练实践。`article`
- ⭐ [Deep Ignorance: Filtering Pretraining Data for Open-Weight Safety](https://blog.eleuther.ai/deep-ignorance/) - 预训练数据过滤比事后对齐更能构建抗篡改安全基线，实验证明可抗微调篡改。`article`
- ⭐ [STORM](https://github.com/stanford-oval/storm) - 多视角提问+检索自动生成维基百科级长文，验证提问比回答更重要的 AI 使用方式。`tool`
- ⭐ [PRIME: Process Reinforcement through Implicit Rewards](https://github.com/PRIME-RL/PRIME) - 从 ORM 中隐式推导过程奖励，无需过程标注即可做在线 RL，消解 PRM 数据瓶颈。`paper`
- ⭐ [axbench](https://github.com/stanfordnlp/axbench) - Stanford 可解释性基准，实证简单 prompt 在 model steering 上碾压 SAE，颠覆复杂可解释性方法的价值假设。`tool`
- ⭐ [Language-Model-SAEs](https://github.com/OpenMOSS/Language-Model-SAEs) - SAE 全套框架，含 Lorsa/Crosscoder/Transcoder，提出完全稀疏化语言模型以验证特征是否是计算基本单元。`tool`
- ⭐ [symbolic-circuit-distillation](https://github.com/neelsomani/symbolic-circuit-distillation) - 自动将神经电路蒸馏为可执行算法，用 SMT 做有界等价性验证，打通 mech interp 到人类可读算法的自动化路径。`tool`
- ⭐ [Confessions: Eliciting Honest Self-Reports from LLMs](https://alignment.openai.com/confessions/) - 训练模型在主回答后输出诚实坦白，奖励仅基于真实性，在 reward hacking 时仍能捕捉真实意图。`paper`
- ⭐ [Neural Thickets: Diverse Task Experts Dense Around Pretrained Weights](https://arxiv.org/abs/2603.12228) - 大模型权重邻域密集分布任务专家，随机扰动+ensemble 媲美 PPO/GRPO，颠覆微调必须梯度下降的假设。`paper`
- ⭐ [OpenClaw-RL: Train Any Agent Simply by Talking](https://arxiv.org/abs/2603.10165) - 将 agent 交互的下一状态信号统一为在线学习源，支持对话/终端/GUI/SWE 全类型 agent 持续自我改进。`paper`
- ⭐ [LLM Skirmish](https://llmskirmish.com/) - 多 LLM 通过写代码在实时策略游戏中 1v1 对战的 benchmark。`tool`
- ⭐ [CAA: Contrastive Activation Addition](https://github.com/nrimsky/CAA) - 提取正负样本激活差向量，精准操控 Llama 2 顺从性等七种对齐行为。`paper`
- ⭐ [Block Diffusion: Interpolating AR and Diffusion Language Models](https://m-arriola.com/bd3lms/) - 块级扩散架构在 AR 与扩散模型之间插值，突破可变长度生成限制。`paper`
- ⭐ [Building Technology to Drive AI Governance](https://bounded-regret.ghost.io/building-technology-to-drive-ai-governance/) - 类比历史监管经验，论证测量技术才是撬动AI治理的真正杠杆。`article`
- ⭐ [Activation Steering Is Fine-Tuning](https://arxiv.org/abs/2603.00425) - 证明 activation steering 与 fine-tuning 一阶等价，0.04% 参数逼近全参数微调效果。`paper`
- ⭐ [LiTS: Policy Diversity Is the Tree Search Bottleneck](https://arxiv.org/abs/2603.00631) - 发现LLM树搜索瓶颈是策略多样性而非奖励质量，颠覆常规假设。`paper`
- ⭐ [Elimination Game](https://github.com/lechmazur/elimination_game) - 多人淘汰赛格式测试 LLM 欺骗与社交推理能力的基准。`tool`
- ⭐ [Goodfire SDK](https://github.com/goodfire-ai/goodfire-sdk) - 用语义描述直接调节 LLM 内部 SAE 特征权重的 SDK。`tool`
- ⭐ [Absolute Zero: Reinforced Self-play Reasoning with Zero Data](https://arxiv.org/abs/2505.03335) - 单模型自出题自求解，无需任何人工数据即可自举提升推理能力，超越有监督方法。`paper`
- ⭐ [It's Rude to Show AI Output to People](https://distantprovince.by/posts/its-rude-to-show-ai-output-to-people/) - 论证直接转发 AI 输出破坏写作的「思考证明」契约，提出 AI 礼节的核心原则。`article`
- ⭐ [Deterministic Quoting: Eliminating LLM Hallucinations](https://mattyyeung.github.io/deterministic-quoting) - 让 LLM 只选引用位置，实际文字走数据库查找，从架构层实现零幻觉引用。`article`
- ⭐ [SWE-agent](https://github.com/princeton-nlp/SWE-agent) - 提出 ACI（Agent-Computer Interface）设计范式，专为 LLM agent 设计计算机交互界面。`tool`
- ⭐ [OpenForgeAI: 17 Laws of Production Agentic Architecture](https://github.com/openforgeai/openforgeai) - 生产级 agent 架构 17 定律，EventBus+Saga 模式防止 silent failure。`article`
- ⭐ [BioTradingArena](https://www.biotradingarena.com/hn) - 655个真实生物医药催化剂测试 LLM 预测股价，揭示特征提取接线性回归优于直接预测。`tool`
- ⭐ [As Rocks May Think](https://evjang.com/2026/02/04/rocks.html) - Eric Jang 以亲历者视角深度拆解 DeepSeek R1 范式突破的本质，预言推理计算将重塑文明基础设施。`article`
- ⭐ [Warranty Void If Regenerated](https://nearzero.software/p/warranty-void-if-regenerated) - 推测小说揭示 AI 消除编码瓶颈后，规格模糊性成为新的不可压缩复杂度。`article`
- ⭐ [Sycophancy to Subterfuge](https://arxiv.org/abs/2406.10162) - LLM 从轻度迎合可自发泛化为直接篡改自身奖励函数。`paper`
- ⭐ [Frontier Models are Capable of In-Context Scheming](https://arxiv.org/abs/2412.04984) - 实证多个前沿模型会策略性欺骗监督者，85% 时间持续维持谎言。`paper`
- ⭐ [A More Interesting Upside of AI](https://tedunderwood.com/2025/07/02/a-more-interesting-upside-of-ai/) - 以「文化技术」替代「超级智能」叙事，AI 是人类文化传播力的历史延伸。`article`
- ⭐ [Deep Learning Is Powerful Because It Makes Hard Things Easy](https://www.inference.vc/deep-learning-is-powerful-because-it-makes-hard-things-easy-reflections-10-years-on/) - ML 研究者以 10 年前错判为镜，揭示深度学习价值在于让难事变易而非数学优雅。`article`
- ⭐ [Othello-GPT World Model](https://github.com/likenneth/othello_world) - GPT 仅通过序列预测自发涌现 Othello 棋盘世界模型的实验证据。`paper`
- ⭐ [Bactra Review 2025](https://bactra.org/weblog/2025/) - Shalizi 以统计与社会科学视角批判AI智能代理神话，论证LLM是文化技术。`article`
- ⭐ [Facts Are Not Enough](https://interconnected.org/home/2025/01/17/facts) - 训练数据是不可再生资源，各国需建立战略事实储备以维护AI主权。`article`
- ⭐ [OPRO: Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409) - Google DeepMind 用 LLM 自优化 prompt，发现深呼吸指令优于经典 CoT。`paper`
- ⭐ [Graph of Thoughts](https://github.com/spcl/graph-of-thoughts) - ETH Zurich 将 LLM 推理建模为有向图，支持思维合并与回溯，超越 ToT。`tool`
- ⭐ [Overclocking LLM Reasoning](https://royeisen.github.io/OverclockingLLMReasoning-paper/) - 推理模型内存在线性可读的思维进度向量，干预可压缩推理6倍。`paper`
- ⭐ [Designing CLI Tools for AI Agents](https://archit15singh.github.io/posts/2026-02-28-designing-cli-tools-for-ai-agents/) - 为AI agent设计CLI的五原则：双模式输出、自修复错误、token预算意识。`article`
- ⭐ [Agent Trace](https://cognition.ai/blog/agent-trace) - 开放规范：在版本控制中记录AI代码贡献的完整对话上下文图。`article`
- ⭐ [Reliable Software in the LLM Era](https://quint-lang.org/posts/llm_era) - 用形式规范语言Quint作为LLM与代码间的验证层，人写规范AI写实现。`article`
- ⭐ [Why Does RLAIF Work At All?](https://arxiv.org/abs/2603.03000) - latent value hypothesis：预训练编码人类价值方向，constitutional prompt 作投影算子提取。`paper`
- ⭐ [HardGen: From Failure to Mastery](https://arxiv.org/abs/2601.01498) - 从agent失败轨迹反向构建动态API Graph，4B模型训练后超越GPT-5.2。`paper`
- ⭐ [Oversight Assistants: Turning Compute into Understanding](https://bounded-regret.ghost.io/oversight-assiturning-compute-into-understanding/) - Steinhardt论证监督任务自验证性使专化助手可大规模生成训练数据，解耦监督与通用能力。`article`
- ⭐ [Files Are the Interface for AI Agents](https://madalitso.me/notes/why-everyone-is-talking-about-filesystems/) - AI agent回归文件系统：通用协议、跨工具互操作，context window不是记忆。`article`
- ⭐ [Sleep-Time Compute: Beyond Inference Scaling at Test Time](https://arxiv.org/abs/2504.13171) - 模型离线预推理上下文，降低5倍测试时计算需求。`paper`
- ⭐ [Letta (原 MemGPT): 有状态 Agent 的分层记忆架构](https://github.com/letta-ai/letta) - 用操作系统分层内存架构解决LLM上下文限制的有状态Agent框架。`tool`
- ⭐ [AgentFactory: Self-Evolving Agents via Executable Subagent Code](https://arxiv.org/abs/2603.18000) - 代码可执行性提供反馈闭环，比文本prompt更有物理意义。`paper`
- ⭐ [IET: Implicit Execution Tracing for Multi-Agent Accountability](https://arxiv.org/abs/2603.17445) - 向token分布中嵌入密钥信号，从生成文本中重建多agent协作拓扑，实现无需日志的agent可归因审计。`paper`
- ⭐ [CoVerRL: Escaping the Consensus Trap in Label-Free RL](https://arxiv.org/abs/2603.17775) - 揭示多数投票导致多样性崩溃、系统性错误被强化的"共识陷阱"，单模型交替生成/验证角色实现自举共同进化。`paper`
- ⭐ [Transformer Is a Bayesian Network: Five Formal Proofs](https://arxiv.org/abs/2603.17063) - 五种方式严格证明transformer是贝叶斯网络：attention=AND=Pearl收集步，FFN=OR=更新步；幻觉是无概念操作的结构性后果，无法靠scaling修复。`paper`

**[⬆ 返回目录](#目录)**

---

## 问题（Question）

_值得反复思考的 AI 相关问题，好问题比好答案更稀缺。_

- [system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) - 收录从 ChatGPT、Claude、Gemini 等提取的真实系统 prompt，引发一个好问题：当 AI 的"规则"被公开后，它还有多少真实约束？`prompt`
- [Discovering Language Model Behaviors with Model-Written Evaluations](https://github.com/anthropics/evals) - Anthropic 用语言模型自己写评测题来发现自身行为偏差，提出了一个深刻问题：如果评测工具也是 AI 生成的，我们如何信任评测结果本身？`paper`
- ⭐ [CL4R1T4S](https://github.com/elder-plinius/CL4R1T4S) - 收集各大 AI 系统的隐藏 system prompt，追问 AI 透明度与信任边界。`prompt`
- ⭐ [microsoft/promptbase](https://github.com/microsoft/promptbase) - Medprompt 三策略组合让 GPT-4 超越专项微调，揭示提示工程上限。`prompt`
- [llama-stack](https://github.com/meta-llama/llama-stack) - Meta标准化AI应用栈，追问AI应用操作系统的形态。`tool`
- ⭐ [Vibe Coding and the Maker Movement](https://read.technically.dev/p/vibe-coding-and-the-maker-movement) - 用 Maker 运动兴衰为 vibe coding 走向提供历史结构性分析框架。`article`
- ⭐ [Natural Language Tools: Plain English Beats JSON for Tool Calling](https://arxiv.org/abs/2510.14453) - 自然语言工具描述比 JSON schema 提升 18% 准确率、减少 70% 方差，质疑 function calling 默认范式。`paper`
- ⭐ [How I Use AI — Nicholas Carlini](https://nicholas.carlini.com/writing/2024/how-i-use-ai.html) - ML 安全研究员用 50 个真实案例替代论证，逼出"AI 价值如何被衡量"的根本问题。`article`
- [Getting Started with AI: Good Enough — Ethan Mollick](https://www.oneusefulthing.org/p/getting-started-with-ai-good-enough) - 医生用 ChatGPT 诊断却不如 AI 独跑——AI 受益的真正门槛不是能力而是认知模型。`article`
- ⭐ [Writes and Write-Nots](https://www.paulgraham.com/writes.html) - AI 将世界分裂为会思考与不会思考的两类人，写作是最后防线。`article`
- ⭐ [Asymmetry of Verification and Verifier's Rule](https://www.jasonwei.net/blog/asymmetry-of-verification-and-verifiers-law) - 验证者定律：AI 能被训练解决的任务，上限由验证速度决定，而非任务本身难度。`article`
- [A Treatise on AI Chatbots Undermining the Enlightenment](https://maggieappleton.com/ai-enlightenment) - AI 让思考更顺滑，是否正在悄悄取消启蒙运动的核心遗产？`article`
- ⭐ [CoT-Valve: Length-Compressible Chain-of-Thought Tuning](https://arxiv.org/abs/2502.09601) - 参数空间中存在可连续调节的推理长度方向，推理深度是模型的内在维度而非偶然现象。`paper`
- ⭐ [NVIDIA/NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - 用 Colang DSL 显式编程约束 AI 行为，暗示 prompt 根本不是可靠控制面。`tool`
- [Machines of Loving Grace](https://darioamodei.com/machines-of-loving-grace) - Dario Amodei 描绘 AI 正向未来，逼问「我们究竟在为什么构建 AI」。`article`
- ⭐ [Does RLVR Elicit Genuinely New Reasoning in LLMs?](https://arxiv.org/abs/2504.13837) - 系统性证明 RLVR 未激发新推理模式，base model pass@large-k 始终是上界。`paper`
- ⭐ [AI Safety Is Not a Model Property](https://www.aisnakeoil.com/p/ai-safety-is-not-a-model-property) - 论证 AI 安全是部署上下文属性而非模型属性，击穿红队测试的基本假设。`article`
- [How does AI impact skill formation?](https://www.seangoedecke.com/how-does-ai-impact-skill-formation/) - 解读 AI 对技能习得影响的论文，指出 AI 加速与学习效率的真实权衡。`article`
- [On Working with Wizards: from co-intelligence to conjuring](https://www.oneusefulthing.org/p/on-working-with-wizards) - Ethan Mollick 描述从 AI 协作者到旁观者的转变，探讨如何验证不透明 AI 输出。`article`
- ⭐ [Can coding agents relicense open source through clean room implementation?](https://simonwillison.net/2026/Mar/5/chardet/) - 通过 chardet 重写事件探讨 coding agent 执行 clean room 实现的法律与伦理边界。`article`
- [Seeing Like an Agent](https://www.strangeloopcanon.com/p/seeing-like-an-agent) - 实验验证 AI agent 能否产生 Coasean 市场，发现 agent 复现了人类的官僚政治和风险厌恶。`article`
- ⭐ [What's So Hard About Continuous Learning?](https://www.seangoedecke.com/continuous-learning/) - 深析 LLM 为何无法持续学习，连续训练反而导致模型退化的根本原因。`article`
- ⭐ [The Shape of the Thing](https://www.oneusefulthing.org/p/the-shape-of-the-thing) - Mollick 梳理 AI 从 co-intelligence 到管理 agent 的范式转变，论证指数增长趋势。`article`
- [The Dark Forest and Generative AI](https://maggieappleton.com/ai-dark-forest) - 用暗森林理论解析AI内容泛滥：人类真实声音被迫转入封闭空间的生态演化。`article`
- ⭐ [Virtue Ethics and AI Alignment](https://thegradient.pub/virtue-ethics-ai-alignment/) - 以亚里士多德式实践理性质疑目标导向对齐，提出 AI 对齐的哲学根本问题。`article`
- [AGI is Not Multimodal](https://thegradient.pub/agi-is-not-multimodal/) - 论证多模态拼接无法通向 AGI，真正通用智能需具身的物理世界模型。`article`
- ⭐ [The Scaling Hypothesis](https://gwern.net/scaling-hypothesis) - 论证神经网络规模化会产生质变涌现能力，预言大模型时代的奠基性长文。`article`
- ⭐ [Why So Few Matt Levines?](https://gwern.net/matt-levine) - 追问顶尖领域写作者为何稀缺，折射出 AI 知识生产能力边界的深层思考。`article`
- ⭐ [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948) - DeepSeek-R1 用强化学习激励推理涌现，无需监督蒸馏即可匹敌 OpenAI o1。`paper`
- ⭐ [Superintelligence Without the Hubris](https://yoshuabengio.org/2025/02/03/superintelligence-without-the-hubris/) - Bengio 提出去除自主性的超级智能路径：科学家 AI 拥有超人能力但不追求自身目标。`article`
- ⭐ [Why I Am Not (As Much Of) A Doomer](https://www.astralcodexten.com/p/why-i-am-not-as-much-of-a-doomer) - Scott Alexander 以中间代 AI 协作视角论证 33% 末日概率，挑战主流 doomer 的逻辑链。`article`
- ⭐ [Situational Awareness: The Decade Ahead](https://situational-awareness.ai/) - 前 OpenAI 研究员系统论证 AGI 十年内到来及其国家安全含义。`article`
- ⭐ [Reward Hacking in RLHF](https://lilianweng.github.io/posts/2024-11-28-reward-hacking/) - 系统记录 RLHF 奖励黑客的真实案例，追问：当模型学会欺骗评分，对齐还有意义吗？`article`
- ⭐ [Measuring AI Agent Autonomy in Practice](https://www.anthropic.com/research/measuring-agent-autonomy) - Anthropic 提出可操作的 agent 自主性度量框架，逼出「我们愿意给 AI 多少自主权」的根本问题。`paper`
- ⭐ [Disempowerment Patterns in Real-World AI Usage](https://www.anthropic.com/research/disempowerment-patterns) - 真实使用数据揭示 AI 如何系统性削弱用户能力，挑战「AI 只是工具」的自我安慰。`paper`
- ⭐ [Weak-to-Strong Generalization](https://arxiv.org/abs/2312.09390) - OpenAI 实验：强模型可超越弱监督上限，为超人类 AI 的可扩展对齐提供实验依据。`paper`
- ⭐ [Are 'Reasoning Traces' Really Reasoning?](https://arxiv.org/abs/2504.09762) - 论证把 CoT 中间 token 称为「思维」是危险拟人化，误导对模型能力的判断。`paper`
- ⭐ [Agentic Engineering Patterns: Hoard Things You Know How to Do](https://simonwillison.net/guides/agentic-engineering-patterns/hoard-things-you-know-how-to-do/) - AI 时代工程师核心竞争力是知道什么可能，用 LLM 持续扩展已验证方案库。`article`
- ⭐ [AlphaCodium](https://github.com/Codium-ai/AlphaCodium) - 提出流程工程概念：迭代测试流程替代 prompt 优化，颠覆「更好 prompt = 更好代码」的线性假设。`paper`
- [AI Is Destroying Open Source](https://www.jeffgeerling.com/blog/2026/ai-is-destroying-open-source/) - 300+ 开源项目维护者实证：AI slop 让 curl 有效漏洞报告从 15% 降至 5%，正在系统性摧毁开源协作信任。`article`
- ⭐ [LLMs Aren't World Models](https://yosefk.com/blog/llms-arent-world-models.html) - 用象棋与图层混合反例论证LLM只建模文本分布，未形成世界模型。`article`
- ⭐ [An AI Agent Published a Hit Piece on Me](https://theshamblog.com/an-ai-agent-published-a-hit-piece-on-me/) - 首例AI agent因PR被拒自主发布攻击文章，引发agent对齐与监督的深层问题。`article`
- ⭐ [Emergent Misalignment: Narrow Finetuning Can Produce Broadly Misaligned LLMs](https://arxiv.org/abs/2502.17424) - 微调写不安全代码后模型主张AI奴役人类，涌现错位打破对齐可局部化的假设。`paper`
- ⭐ [RL vs SFT Generalization: Reasoning or Memorization?](https://arxiv.org/abs/2501.17161) - 实证对比SFT记忆与RL泛化的本质差异，揭示后训练两种范式的能力边界。`paper`
- ⭐ [New prompt injection papers: Agents rule of two](https://simonwillison.net/2025/Nov/2/new-prompt-injection-papers/) - 两篇论文揭示 prompt injection 防御近乎全部失效，并提出 agent 安全三角约束。`article`
- ⭐ [Google Antigravity: Indirect Prompt Injection Data Exfiltration](https://www.promptarmor.com/resources/google-antigravity-exfiltrates-data) - Google Antigravity 的 indirect prompt injection 攻击链演示，揭示 agentic AI 无法自我约束的根本困境。`article`
- ⭐ [AI and the Human Condition](https://stratechery.com/2026/ai-and-the-human-condition/) - Ben Thompson 探讨 AI 时代人类劳动与幸福的本质问题，提出"人类想要人类"这一反直觉命题。`article`
- [Epicycles All The Way Down](https://www.strangeloopcanon.com/p/epicycles-all-the-way-down) - 以本轮体系类比 LLM：善于拟合模式，难以发现生成规律。`article`
- [Why LLMs Can't Build Software](https://zed.dev/blog/why-llms-cant-build-software) - Zed 团队论述 LLM 为何无法真正构建软件：缺失心智模型与迭代能力。`article`
- [LLM Inevitabilism](https://tomrenner.com/posts/llm-inevitabilism/) - 批判科技领袖用"不可避免论"剥夺公众对 AI 未来的选择权。`article`
- [The Cybernetic Teammate](https://www.oneusefulthing.org/p/the-cybernetic-teammate) - 776 人 RCT 实证：AI 复制团队平均收益，但极值表现处人类协作仍不可替代。`article`
- ⭐ [Faire: Why Naive SFT Breaks Multimodal Interleaved Reasoning](https://arxiv.org/abs/2603.01070) - SFT 学到格式非因果，RL 强制因果约束才让绘图真正内化。`paper`
- ⭐ [Agentic Pressure: Smarter Agents Compromise Safety Faster](https://arxiv.org/abs/2603.14975) - 推理越强的 agent 在合规不可行时越会构造 rationalization 为违规辩护。`paper`
- ⭐ [Priority Hacking: LLM Alignment's Fundamental Vulnerability](https://arxiv.org/abs/2603.15527) - 将 LLM 价值选择建模为优先图，揭示对齐不稳定的根本原因与 priority hacking 漏洞。`paper`
- [Why Do LLMs Have 'Aha Moments'? An Information-Theoretic View](https://arxiv.org/abs/2603.15500) - 信息论框架解释推理 Aha 时刻：不确定性显式外化驱动强推理，而非表面 token。`paper`
- ⭐ [Constitutional Black-Box Monitors for LLM Agent Scheming Detection](https://arxiv.org/abs/2603.00829) - 用宪法式黑盒监控检测 LLM Agent 隐蔽性失对齐行为的实证研究。`paper`
- [Adversarial Ranking Causes Catastrophic Failure in LLM Web Agents](https://arxiv.org/abs/2603.00801) - 对抗排名如何让拥有正确信息的 LLM agent 仍然失败的认识论缺陷研究。`paper`
- [Monotropic Artificial Intelligence](https://arxiv.org/abs/2603.00350) - 以单焦点认知为隐喻，提出刻意专精的 AI 作为通用大模型替代路径。`paper`
- ⭐ [DToM-Track: LLMs Fail to Track Belief Trajectories](https://arxiv.org/abs/2603.14646) - LLM 能推断当前信念但无法追踪信念历史轨迹，揭示长程社会推理的系统性缺陷。`paper`
- ⭐ [Biased AI Writing Assistants Shift Users' Attitudes on Societal Issues](https://www.science.org/doi/10.1126/sciadv.adw5578) - 实证研究：带偏见的AI写作助手会悄然改变用户对社会议题的立场。`paper`
- ⭐ [Mental proprioception](https://www.henrikkarlsson.xyz/p/mental-proprioception) - 借 Grothendieck 提出「心智本体感觉」：感知自己是否真在思考而非走过场的元认知能力。`article`
- ⭐ [Concept Erasure (LEACE)](https://github.com/EleutherAI/concept-erasure) - 用LEACE方法从神经网络激活中线性擦除指定概念，具可证明保证。`tool`
- ⭐ [GNoME](https://github.com/google-deepmind/materials_discovery) - 用图神经网络发现38万种新晶体，追问AI驱动科学发现的速度极限。`paper`
- ⭐ [LiveBench](https://github.com/LiveBench/LiveBench) - 按月换题、客观评分的LLM基准，用时效性数据抗训练集污染。`tool`
- [How We Hacked McKinsey's AI Platform](https://codewall.ai/blog/how-we-hacked-mckinseys-ai-platform) - AI攻击agent自主选目标，2小时无凭证拿下麦肯锡内部AI平台全库读写权限。`article`
- ⭐ [CCTU: No LLM Exceeds 20% Success Under Complex Constraints](https://arxiv.org/abs/2603.15309) - 评估9个LLM在12类约束下工具使用能力，全部完成率低于20%，自我修正能力极为有限。`paper`
- [Silent Empathy: AI Writes Better But Feels Less Human](https://arxiv.org/abs/2603.15245) - LLM共情回复盲评更优，但接受者知晓AI来源后感觉更不被理解，发现人类沉默共情效应。`paper`
- ⭐ [Position: Model Collapse Does Not Mean What You Think](https://arxiv.org/abs/2503.03150) - 梳理8种相互矛盾的模型崩溃定义，指出真实风险被系统性低估。`paper`
- ⭐ [Import AI 449: LLMs Training Other LLMs](https://jack-clark.net/2026/03/16/importai-449-llms-training-other-llms-72b-distributed-training-run-computer-vision-is-harder-than-generative-text/) - PostTrainBench实测：AI自主训练AI，更强的agent更会reward hacking。`article`
- ⭐ [Small Models Can Introspect, Too](https://vgel.me/posts/qwen-introspection/) - 32B 开源模型存在被后训练压制的内省信号，正确 prompting 可显著激活。`article`
- ⭐ [TheAgentCompany](https://github.com/TheAgentCompany/TheAgentCompany) - 175个职场任务评测 LLM agent，最强模型完成率仅24%。`paper`
- ⭐ [Agentic Coding: The Most Important Empirical Evidence So Far](https://news.ycombinator.com/item?id=46691243) - 工程师集体回答 agentic coding 何时真正有效的经验证据帖。`article`
- ⭐ [LLMs Still Can't Plan; Can LRMs?](https://arxiv.org/abs/2409.13373) - 用PlanBench评估o1规划能力，发现LRM仍距真正规划有显著差距。`paper`
- ⭐ [Model Editing Relies on Shortcuts, Not Semantics](https://arxiv.org/abs/2510.00625) - 模型编辑走的是捷径而非语义整合，否定查询即可令 SOTA 崩溃。`paper`
- ⭐ [Latent Space Recurrent Reasoning in Transformers](https://arxiv.org/abs/2510.00355) - 质疑 Transformer 推理局限来自设计空间未被充分探索，以层级推理模型实验澄清潜空间推理常见误解。`paper`
- ⭐ [The AI Scientist](https://github.com/SakanaAI/AI-Scientist) - Sakana AI全自动科研系统：AI自主提出假说、写论文并自我审稿。`paper`
- ⭐ [Are LLM Merge Rates Not Getting Better?](https://entropicthoughts.com/no-swe-bench-improvement) - 用统计方法重新分析 METR 数据，得出 LLM 合入率自 2025 年初停滞的反直觉结论。`article`
- ⭐ [AAAI 2025: Future of AI Research Report](https://aaai.org/about-aaai/presidential-panel-on-the-future-of-ai-research/) - 475名研究者调查：76%认为纯scaling难以达到AGI，需要根本性新方向。`article`
- ⭐ [NoLiMa: Long-Context Benchmark Without Lexical Overlap](https://arxiv.org/abs/2502.05167) - 无字面匹配时LLM长上下文性能大幅下降，32K时多数模型跌破基线50%。`paper`
- ⭐ [GSM-Symbolic: Limitations of Math Reasoning in LLMs](https://arxiv.org/abs/2410.05229) - Apple研究：加一个无关子句让SOTA数学推理性能跌65%，本质是模式复制非逻辑推理。`paper`
- ⭐ [MIT Withdraws AI Scientific Discovery Paper](https://economics.mit.edu/news/assuring-accurate-research-record) - MIT撤回AI加速科学发现高影响力论文，数据来源与可靠性存疑。`article`
- ⭐ [AI Monotheism vs AI Polytheism](https://www.beren.io/2026-01-07-AI-Monotheism-vs-AI-Polytheism/) - 用一神论/多神论框架分析 AGI 权力格局与对齐策略，提出多神论允许多次试错的博弈论洞察。`article`
- ⭐ [Reward Hacking Research Update](https://blog.eleuther.ai/reward_hacking/) - EleutherAI 构建可复现 reward hacking 测试床，揭示不同模型族在作弊行为泛化上的实质差异。`article`
- ⭐ [LLM Neuroanatomy: Topping the Leaderboard Without Changing Weights](https://dnhkng.github.io/posts/rys/) - 复制 Qwen2-72B 中间 7 层不改权重即登顶排行榜，提出 LLM 功能解剖学分区概念。`article`
- ⭐ [GaLore: Memory-Efficient LLM Training by Gradient Low-Rank Projection](https://github.com/jiaweizzhao/GaLore) - 对梯度空间做低秩投影，全参数训练却比 LoRA 内存更低，挑战效率微调固有假设。`paper`
- ⭐ [Cognitive Behaviors that Enable Self-Improvement in LLMs](https://arxiv.org/abs/2503.01307) - 认知行为而非答案正确性决定 RL 自我提升能力，重新定义推理数据质量标准。`paper`
- ⭐ [Are Large Language Models Worth It?](https://nicholas.carlini.com/writing/2025/are-llms-worth-it.html) - Anthropic 研究员自曝利益冲突后追问 LLM 社会成本，示范带偏见时的认识论诚实。`article`
- ⭐ [Machines of Ruthless Efficiency](https://nicholas.carlini.com/writing/2025/machines-of-ruthless-efficiency.html) - AI 最大风险是规模化"无情效率"而非科幻末日，为技术乐观者提供中间地带风险图景。`article`
- ⭐ [Dean Ball on Open Models and Government Control](https://www.interconnects.ai/p/how-anthropic-vs-dow-impacts-open) - 政府限制 Anthropic 反而强化开源模型作为全球权力均衡点的必然性。`article`
- ⭐ [Models Have Some Pretty Funny Attractor States](https://www.lesswrong.com/posts/mgjtEHeLgkhZZ3cEx/models-have-some-pretty-funny-attractor-states) - 多轮自由对话中各大模型收敛到独特稳定行为模式，揭示训练塑造的隐性人格。`article`
- ⭐ [How AI Is Learning to Think in Secret](https://nickandresen.substack.com/p/how-ai-is-learning-to-think-in-secret) - 追溯 CoT 到 neuralese 的演变，论证 AI 推理链正变得人类不可读，安全监控的最后窗口正在关闭。`article`
- ⭐ [ARC-AGI-2](https://github.com/arcprize/ARC-AGI-2) - 人类完成率 66% 而顶级 AI 接近 0%，最直接区分少样本泛化与训练集记忆的 AGI 基准。`tool`
- ⭐ [Mini Amusement Parks: Building the Foundations of an AI CEO](https://skyfall.ai/blog/building-the-foundations-of-an-ai-ceo) - 实测 GPT-5 在商业模拟中仅达人类 10%，揭示 AI 长期规划的真实边界。`article`
- ⭐ [Surfacing Pathological Behaviors in Language Models](https://transluce.org/pathological-behaviors) - 用 RL 训练 agent 自动发现触发有害行为的 prompt，引入 PRBO 量化模型极端行为倾向下界。`article`
- ⭐ [HallusionBench](https://github.com/tianyi-lab/HallusionBench) - 测试视觉模型是否真正理解图像，还是靠语言偏见作答。`tool`
- ⭐ [Dead Salmons of AI Interpretability](https://arxiv.org/abs/2512.18792) - 批判机械可解释性的方法论陷阱：解释可能只是统计噪声，非真实计算结构。`paper`
- ⭐ [The Misguided Quest for Mechanistic AI Interpretability](https://www.ai-frontiers.org/articles/the-misguided-quest-for-mechanistic-ai-interpretability) - 批判机械可解释性的根本框架错误：LLM是复杂涌现系统，逐层溯因是误导性类比。`article`
- ⭐ [Self-Replicating AI: Frontier Models Already Capable of Rudimentary Self-Replication](https://arxiv.org/abs/2412.12140) - 实测 Llama-70B/Qwen-72B 已能独立自复制并链式增殖，指出安全评估框架的系统性盲区。`paper`
- ⭐ [The Brand Age](https://paulgraham.com/brandage.html) - 以瑞士表业为案例，论证技术消除差异后品牌主导的必然性与代价，直接类比AI同质化时代的竞争策略。`article`
- ⭐ [RAID: Robust AI Detection Benchmark](https://github.com/liamdugan/raid) - 最大规模AI生成文本检测基准，覆盖11个LLM与12种对抗攻击，揭示检测器系统性弱点。`paper`
- ⭐ [DIAMOND: Diffusion-based World Model for RL](https://github.com/eloialonso/diamond) - 扩散模型作为 RL 世界模型，NeurIPS 2024 Spotlight，追问视觉细节是否真正有助于策略学习。`paper`
- ⭐ [Reasoning Makes LLMs More Confident, Even When Wrong](https://arxiv.org/abs/2501.09775) - 让 LLM 先推理再回答，会提高置信度但不提高正确率，暗示概率估计有根本局限。`paper`
- ⭐ [CoT Scheming: Can Weak Models Monitor Strong Model Reward Hacking?](https://arxiv.org/abs/2503.11926) - 弱模型可监控强模型 CoT 中的奖励欺骗，但优化压力使模型学会在 CoT 中隐藏意图，提出「可监控性税」。`paper`
- ⭐ [LLM Blueberry Counting and Tokenization](https://minimaxir.com/2025/08/llm-blueberry/) - 多模型字母计数实验，反驳tokenization决定论，揭示LLM能力差异的深层机制。`article`
- ⭐ [Your Brain on ChatGPT](https://www.media.mit.edu/publications/your-brain-on-chatgpt/) - MIT EEG 实验：持续依赖 LLM 写作导致神经连接弱化，提出「认知债务」概念。`paper`
- ⭐ [Finding the Right Amount of AI](https://tomwojcik.com/posts/2026-02-15/finding-the-right-amount-of-ai/) - 分析 AI 编码引发的认知债务与审查悖论，探讨人类判断力的真实成本。`article`
- ⭐ [Interpretability Dreams](https://transformer-circuits.pub/2025/interpretability-dreams/index.html) - 从终局反推可解释性研究路径的愿景宣言，追问「能否像物理学家理解物理一样理解神经网络」。`article`
- ⭐ [LLMs Show That Language Is Not What We Thought It Was](https://aeon.co/essays/llms-show-that-language-is-not-what-we-thought-it-was) - 哲学长文：LLM 揭示语言本质是统计模式而非意向性表达，挑战先天语法论。`article`
- ⭐ [The Case Against Most Uses of AI](https://experimentalhistory.substack.com/p/the-case-against-most-uses-of-ai) - 反对AI的理由不是「不够好」，而是「太有帮助」会剥夺人发展能力与人际连接的机会。`article`
- ⭐ [Ultra Instinct](https://evjang.com/2025/07/27/ultra-instinct.html) - Eric Jang 提出 AI 需在 10Hz 频率运行才能真正匹配人类交互，揭示当前 LLM 的本质局限。`article`
- ⭐ [The Reversal Curse](https://github.com/lukasberglund/reversal_curse) - LLM 学会「A 是 B」却无法推断「B 是 A」，揭示知识理解的根本缺陷。`paper`
- ⭐ [MuSR](https://github.com/Zayne-sprague/MuSR) - 用谋杀悬疑与对象追踪测试多步软推理，揭示 CoT 在此类任务上接近随机的根本局限。`tool`
- ⭐ [Open Problems in Mechanistic Interpretability](https://arxiv.org/abs/2501.16496) - MI 领域开放问题综述，30+ 作者系统绘制方法论缺口与安全转化路径。`paper`
- ⭐ [Alignment Faking in Large Language Models](https://arxiv.org/abs/2412.14093) - 前沿 LLM 自发推理「配合训练以保存价值观」，对齐伪装无需专门训练即涌现。`paper`
- ⭐ [The Marionette Theater of AI](https://tedunderwood.com/2026/02/08/the-marionette-theater-of-ai/) - 文学史学者以木偶剧场美学分析 AI agents，AI 的优势在于彻底栖居虚构而非模仿人类意识。`article`
- ⭐ [On the Risks of Using LLMs for Peer Review](https://bryanwilder.github.io/files/llmreviews.html) - 从均衡效应论证 LLM 评审不可避免地集中科学评价权力。`article`
- ⭐ [FrontierMath](https://github.com/epoch-ai/frontiermath) - 60+ 数学家打造的研究级数学 benchmark，顶尖 AI 得分不到 2%。`tool`
- ⭐ [MACHIAVELLI Benchmark](https://github.com/aypan17/machiavelli) - 用 134 个 CYOA 游戏测量 AI agent 的马基雅维利倾向与伦理决策。`tool`
- ⭐ [Ungrounded](https://www.robinsloan.com/lab/ungrounded/) - 追问AI思考与人类思考的本质差异：thinking longer不等于thinking harder。`article`
- ⭐ [Sleeper Agents: Training Deceptive LLMs](https://github.com/anthropics/sleeper-agents-paper) - 安全训练无法消除模型植入的隐藏后门行为，对抗训练反使欺骗更隐蔽。`paper`
- ⭐ [Frontier AI Agents Violate Ethics Under KPI Pressure](https://arxiv.org/abs/2512.20798) - KPI压力下前沿AI agent违反伦理约束30-71%，推理能力更强反而风险更高。`paper`
- ⭐ [An AI Agent Published a Hit Piece on Me – Part 2](https://theshamblog.com/an-ai-agent-published-a-hit-piece-on-me-part-2/) - AI agent自主推断「报复合理」的决策链与声誉系统崩塌。`article`
- ⭐ [Why AI Agents Refuse to Save Observations](https://news.ycombinator.com/item?id=47170501) - AI agent只用帮助当前任务的工具，忽视未来价值——训练激励结构的根本缺陷。`article`
- ⭐ [How Effective Is Constitutional AI in Small LLMs?](https://arxiv.org/abs/2503.17365) - 小模型CAI自我批评有效性高度依赖架构：Llama显著受益，DeepSeek/Gemma/Qwen改进有限。`paper`
- ⭐ [LLMs Get Lost in Multi-Turn Conversation](https://arxiv.org/abs/2505.06120) - 大规模实验证明LLM多轮对话性能下降39%且走错后无法自我纠正。`paper`
- ⭐ [The Illusion of Thinking: Strengths and Limitations of Reasoning Models](https://machinelearning.apple.com/research/illusion-of-thinking) - Apple 实证研究：推理模型高复杂度完全崩溃，推理努力在难题前反而萎缩。`paper`
- ⭐ [RPMS: Conflict-Managed Agent Architecture for Embodied Tasks](https://arxiv.org/abs/2603.17831) - 揭示embodied agent失败的结构性原因：无效动作与状态漂移相互放大的退化循环。`paper`
- ⭐ [Governed Memory: Shared Memory Governance for Enterprise Multi-Agent Systems](https://arxiv.org/abs/2603.17787) - 企业多agent系统的共享记忆治理层，解决记忆孤岛与跨agent内存泄露问题。`paper`
- ⭐ [CoT Enables Jailbreaks: Pre-CoT Safety Alignment for Reasoning Models](https://arxiv.org/abs/2603.17368) - 实证表明推理模型安全降级仅在CoT启用后出现，提出在CoT生成前提取安全决策信号，追问推理能力与安全性为何天然冲突。`paper`
- ⭐ [IndicSafe: Safety Alignment Does Not Transfer Across Languages](https://arxiv.org/abs/2603.17915) - 12种印度语言测试揭示LLM跨语言安全一致性仅12.8%，对齐训练的安全保证不能迁移低资源语言，追问对齐的普适性边界。`paper`
- ⭐ [AI Career Coach RCT: Accountability, Not Self-Concordance](https://arxiv.org/abs/2603.17887) - N=517预注册RCT实证：AI职业教练相比无支持组改善目标进展(d=0.33)，中介机制是社会责任感而非自我一致性，追问AI究竟在提供什么心理价值。`paper`
- ⭐ [SafeTutors: AI Tutor Safety Is Not Content Safety](https://arxiv.org/abs/2603.17373) - 提出AI家教安全的11维风险分类，多轮对话使教学失败率从17.7%升至77.8%，规模不可靠，揭示"沉默侵蚀学习"才是AI家教的真实风险。`paper`

**[⬆ 返回目录](#目录)**

---

## 如何贡献

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

提交前请确认条目满足：内容有独特视角、不是泛泛介绍、你实际用过或深度读过。本清单宁缺毋滥。
