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

**[⬆ 返回目录](#目录)**

---

## 如何贡献

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

提交前请确认条目满足：内容有独特视角、不是泛泛介绍、你实际用过或深度读过。本清单宁缺毋滥。
