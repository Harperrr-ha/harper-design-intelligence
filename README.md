# Harper Design Intelligence

Harper Design Intelligence 是一个长期使用的个人设计知识系统。

它不是项目管理软件，也不是普通文件分类系统。它的目标是把每天阅读的品牌案例、设计案例、工作中的重要思考、与 AI 的深度讨论、真实项目经验，逐渐沉淀为属于 Harper 自己的：

```text
Case -> Insight -> Principle -> Method
```

最终形成个人设计判断体系、方法论和职业知识资产。

## Core Idea

知识不应该被过早整理成漂亮结论。这个仓库会保留思想成长和变化的过程。

知识成熟度分为五个阶段：

```text
SEED
刚产生、还不成熟的想法

-> INSIGHT
可以清晰表达的独立判断

-> VALIDATED INSIGHT
已经被多个案例 / 项目经验支持

-> PRINCIPLE
已经成为相对稳定的设计原则

-> METHOD
已经可以指导实际工作的具体方法
```

原则：不要把所有笔记直接变成 Principle。必须先保留来源、证据、反例、判断变化和开放问题。

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

## Daily Workflow

1. 先进入 `00_INBOX/`。

   把 AI 对话总结、突然产生的想法、工作反思、阅读笔记先放进这里。不要急着分类。

2. 判断它是什么。

   - 真实品牌 / 设计案例：进入 `01_CASES/`
   - 独立判断或想法：进入 `02_INSIGHTS/`
   - 长期问题但尚无稳定结论：进入 `05_WORKING_THESES/`
   - 真实项目里的可迁移经验：进入 `06_PROJECT_LEARNINGS/`
   - 未来可能变成文章、作品集表达、演讲的内容：进入 `07_WRITING/`
   - 原始资料索引：进入 `08_SOURCES/`

3. 建立连接。

   每次新增内容，都尽量回答：它支持了哪个 Insight？它挑战了哪个 Principle？它能否成为某个 Method 的例子？

4. 定期 Review。

   在 `09_REVIEWS/` 做 Weekly / Monthly / Quarterly Reflection，专门判断哪些想法重复出现、哪些旧观点被推翻、哪些 Insight 可能升级。

## After Reading A Brand Case

使用 `templates/case-template.md`。

重点不是收藏案例，而是提取判断：

- What happened
- Key Decision
- Why it worked
- Evidence
- My Judgment
- What changed my mind
- Transferable Insight
- Related
- Source

写完 Case 后，再判断是否需要创建或更新某个 Insight。

## After A Deep AI Conversation

先放入 `00_INBOX/`，然后整理为：

- 新 Insight
- Existing Insight 的新证据
- 反例或冲突
- Working Thesis
- Writing draft

不要只做摘要。AI 对话的价值在于帮助 Harper 的判断变得更清晰，而不是生成一份漂亮笔记。

## After Important Work Reflection

如果来自真实项目，不做项目管理记录，只提取可迁移经验。

使用 `templates/project-learning-template.md`，重点记录：

- Origin Project
- What Happened
- What I Learned
- Why It Matters
- Transferable Insight
- Related Principle / Method

## When To Upgrade Insight To Principle

只有当一个 Insight 同时满足这些条件，才考虑升级为 Principle：

- 被多个 Case 或 Project Learning 支持
- 有明确反例或适用边界
- Harper 的判断已经相对稳定
- 能影响实际设计决策
- 在 Review 中被反复验证，而不是一次性冲动结论

升级时，不要删除原 Insight。应在 Principle 中引用相关 Insight，并在 Insight 的 History 中记录升级过程。

## When To Form A Method

只有当一个 Principle 已经可以指导实际工作流程，才形成 Method。

Method 必须能回答：

- Purpose
- When to Use
- Inputs
- Steps
- Decision Criteria
- Common Mistakes
- Examples
- Related Principles

Method 是可以拿来工作的，不是观点口号。

## Demo Chain

仓库中包含一组明确标注为 `DEMO` 的虚构示例，用来展示：

```text
DEMO Case -> DEMO Insight -> DEMO Principle -> DEMO Method
```

这些示例不是 Harper 的真实个人观点，只是演示系统如何运作。

## Working Rule

未来所有 Codex Agent 必须先阅读 `AGENTS.md`，再帮助维护这个知识系统。