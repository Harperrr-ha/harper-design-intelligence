# Harper Design Intelligence

Harper Design Intelligence 是 Harper 的长期个人认知资产系统。

它不是：

- 品牌案例收藏夹
- 项目管理系统
- 普通知识管理库
- PDF 文件仓库
- AI 自动总结库

它的目标是持续记录：

- Harper 看到了什么
- Harper 如何理解
- Harper 为什么这样判断
- Harper 的判断如何变化
- 哪些经验被反复验证
- 哪些观点被推翻
- 哪些原则逐渐稳定
- 这些原则最终如何变成实际工作方法

核心知识生长链是：

```text
Experience / Source
        -> Thinking
        -> Insight
        -> Validation
        -> Principle
        -> Method
```

## The Simplest Way To Use This System

Harper 不需要先判断材料属于哪个文件夹。

日常只需要做一件事：

```text
纳入 Design Intelligence：
[粘贴任何原始内容]
```

内容可以来自书、案例、文章、项目、设计评审、会议、AI 对话、观察、想法、问题、反思，或者一次 Changed Mind。

Agent 的责任是理解、提取、比较、判断成熟度，并更新知识库。Harper 不负责每天手动创建文件、选择目录、维护链接、检查重复、更新 Knowledge Map 或判断 Insight 是否成熟。

如果这个系统让 Harper 花大量时间管理知识库，说明系统设计失败。

## What The Agent Will Do

每次收到新材料，Agent 不应该立刻创建文件。标准流程是：

1. Understand

   理解来源、发生了什么、Harper 真正在讨论什么、哪些是外部事实、哪些是 Harper 的判断、哪些仍然只是猜测。

2. Extract

   判断是否存在 Evidence / Fact、Observation、Insight、Seed、Project Learning、Working Thesis、Open Question、Changed My Mind、Principle Candidate、Method Candidate。

3. Compare

   搜索现有知识，优先判断它是否更新、连接、验证或挑战已有内容，而不是马上创建新文件。

4. Judge Maturity

   按照 `SEED -> INSIGHT -> VALIDATED INSIGHT -> PRINCIPLE -> METHOD` 谨慎判断成熟度。一个案例不能直接产生 Principle。

5. Update

   只修改真正需要变化的部分：新增必要内容、更新已有内容、增加 Evidence / Counter Evidence、记录 Changed My Mind、建立连接，并在必要时更新 `KNOWLEDGE_MAP.md`。

## Repository Structure

```text
00_INBOX/
01_CASES/
02_INSIGHTS/
03_PRINCIPLES/
04_METHODS/
05_WORKING_THESES/
06_PROJECT_LEARNINGS/
07_WRITING/
08_SOURCES/
09_REVIEWS/
templates/
README.md
AGENTS.md
KNOWLEDGE_MAP.md
```

这些目录仍然有用，但它们主要服务 Agent 的长期维护，不应该成为 Harper 每天的负担。

## How Sources Become Knowledge

Source 不是最终知识资产。

一本书、一个案例、一篇文章、一次会议、一段 AI 对话、一个项目节点，本身只是来源。真正重要的是：

- 它让 Harper 看到了什么
- Harper 是否认同
- 为什么认同或不认同
- 它支持了哪个已有 Insight
- 它挑战了哪个旧判断
- 它是否带来反例
- 它是否让某个 Working Thesis 变清晰

例如，读到一个品牌案例后，系统不应停在“保存案例总结”。它应该进一步判断：这个案例是否支持或挑战某个关于品牌资产、识别、规则、差异化或设计决策的思想。

## Maturity Rules

```text
SEED
刚产生、还不成熟的想法

-> INSIGHT
可以清晰表达的独立判断

-> VALIDATED INSIGHT
被多个来源、案例或项目经验支持

-> PRINCIPLE
经过多次验证后，Harper 愿意在未来设计判断中继续使用的稳定认知

-> METHOD
已经可以帮助 Harper 在真实工作中做出更好决定的可重复方法
```

不要把所有笔记直接变成 Principle。必须保留来源、证据、反例、适用边界、判断变化和开放问题。

## Working With Books

这里不是普通读书笔记库。

书籍讨论应该优先进入 Insight、Working Thesis、Principle 或 Method，而不是长期停留在章节摘要。

Agent 应该判断：作者观点为什么让 Harper 在意？Harper 是否认同？它和 Harper 过去判断有什么关系？是否改变了 Harper 的认识？

## Working With Projects

`06_PROJECT_LEARNINGS/` 不承担项目管理职能。

不要维护项目进度、To Do、截止时间、会议流水账或文件版本。

只保留真实项目中产生的可迁移知识：发生了什么、为什么重要、Harper 原来怎么想、后来意识到什么、是否可迁移、支持或挑战了哪个 Insight。

## Processing Result Format

每次完成一次知识归档后，默认用简短回执：

```text
KNOWLEDGE UPDATE

Source
本次材料大致来源

Most Important Development
这次最值得保留的新认知

Added
真正新增了什么

Updated
哪些已有思想得到补充

Connections
和过去哪些内容形成关联

Challenge / Changed My Mind
是否出现冲突或认识变化

Open Questions
还有什么值得继续想

Maturity
是否发生成熟度变化；如果没有，写 No maturity upgrade.
```

不要为了回执显得丰富而制造变化。

## Demo Content

仓库中包含一组明确标注为 `DEMO` 的虚构示例，用来展示：

```text
DEMO Case -> DEMO Insight -> DEMO Principle -> DEMO Method
```

这些示例不是 Harper 的真实个人观点，只是演示系统如何运作。

## Working Rule

未来所有 Codex Agent 必须先阅读 `AGENTS.md`，再帮助维护这个知识系统。
