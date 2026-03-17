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

**[⬆ 返回目录](#目录)**

---

## 如何贡献

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

提交前请确认条目满足：内容有独特视角、不是泛泛介绍、你实际用过或深度读过。本清单宁缺毋滥。
