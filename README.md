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

**[⬆ 返回目录](#目录)**

---

## 如何贡献

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

提交前请确认条目满足：内容有独特视角、不是泛泛介绍、你实际用过或深度读过。本清单宁缺毋滥。
