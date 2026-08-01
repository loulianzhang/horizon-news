# Horizon 每日速递 - 2026-08-01

> From 17 items, 8 important content pieces were selected

---

1. [DeepSeek-V4-Flash-0731：高性价比的 3040 亿参数 AI 模型发布](#item-1) ⭐️ 8.0/10
2. [无状态 MCP 2.0 重新点燃对模型上下文协议的兴趣](#item-2) ⭐️ 8.0/10
3. [Simon Willison 在 Oxide and Friends 播客中讨论开放权重 AI 模型](#item-3) ⭐️ 8.0/10
4. [新的 800 页 64 位汇编编程书籍](#item-4) ⭐️ 7.0/10
5. [加拿大签署联合国网络犯罪公约，引发隐私担忧](#item-5) ⭐️ 7.0/10
6. [微软发布 Flint，一种面向 AI 的可视化语言](#item-6) ⭐️ 7.0/10
7. [smevals：评估 AI 模型和提示的新工具](#item-7) ⭐️ 7.0/10
8. [RipGrep musl 二进制文件在大规模搜索中偶尔崩溃](#item-8) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [DeepSeek-V4-Flash-0731：高性价比的 3040 亿参数 AI 模型发布](https://simonwillison.net/2026/Jul/31/deepseek-v4-flash-0731/#atom-everything) ⭐️ 8.0/10

DeepSeek 发布了 DeepSeek-V4-Flash-0731，这是一个具有增强代理能力的 3040 亿参数 AI 模型，在 Hugging Face 上可用，输入费用为每百万次 0.14 美元，输出费用为每百万次 0.27 美元。 该模型在智能和成本效益方面超越了更大的模型，对于那些寻求以较低成本获得高性能的人来说，这是 AI/ML 领域的一个重要进展。 根据 Artificial Analysis 的评估，DeepSeek-V4-Flash-0731 排名超过了 4280 亿参数的 MiniMax M3 模型，目前是性价比最高的智能模型。

rss · Simon Willison · Jul 31, 23:59

**背景**: Artificial Analysis Intelligence Index 是一个综合基准，用于衡量 AI 在数学、科学、编码和推理等各个领域的性能。Hugging Face 是一个平台，社区成员可以在上面托管、共享和发现机器学习模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/evaluations/artificial-analysis-intelligence-index">Artificial Analysis Intelligence Index</a></li>
<li><a href="https://huggingface.co/docs/hub/models">Models · Hugging Face</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Model Release`, `#Cost-Effectiveness`

---

<a id="item-2"></a>
## [无状态 MCP 2.0 重新点燃对模型上下文协议的兴趣](https://simonwillison.net/2026/Jul/31/stateless-mcp/#atom-everything) ⭐️ 8.0/10

Simon Willison 讨论了 MCP 2.0 的推出，这是模型上下文协议的一个重要更新，重新点燃了他对该协议的兴趣。 这次更新简化了协议客户端和服务器的实现，使其更容易审计和控制，并且适合可以在笔记本电脑上运行的小型模型。 新的无状态 MCP 规范通过使用单个 HTTP 请求而不是两个请求来减少复杂性，消除了会话管理的需要并提高了可扩展性。

rss · Simon Willison · Jul 31, 23:13

**背景**: 模型上下文协议（MCP）是 Anthropic 在 2024 年 11 月引入的一个开放标准，旨在标准化大型语言模型（LLM）等 AI 系统与外部工具和系统的数据集成和共享方式。它最初很受欢迎，但后来被其他技术如 Skills 所掩盖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol</a></li>
<li><a href="https://github.com/modelcontextprotocol">Model Context Protocol - GitHub</a></li>

</ul>
</details>

**标签**: `#LLM`, `#MCP`, `#AI`, `#Agent Frameworks`, `#Anthropic`

---

<a id="item-3"></a>
## [Simon Willison 在 Oxide and Friends 播客中讨论开放权重 AI 模型](https://simonwillison.net/2026/Jul/31/oxide-and-friends/#atom-everything) ⭐️ 8.0/10

Simon Willison 加入了 Oxide and Friends 播客，讨论了开放权重 AI 模型的最新进展，包括 Kimi K3 的表现和行业对开放权重的讨论。 这次讨论突显了开放权重 AI 模型的重要进展及其影响，这些模型现在可以与专有模型竞争，并正在重塑 AI 领域。 播客涵盖了 Kimi K3 的表现、网络安全事件以及关于开放权重和美国 AI 领导力的公开信。还涉及了其他与 AI 相关的主题和对未来的一些预测。

rss · Simon Willison · Jul 31, 21:33

**背景**: 开放权重 AI 模型是指在某些条件下提供内部参数（权重）的模型，允许更多的控制和定制。这不同于完全开源的模型，后者提供更广泛的训练数据和代码访问权限。由 Moonshot AI 开发的 Kimi K3 是一个显著的例子，它拥有 2.8 万亿个参数和先进的功能，如 100 万令牌的上下文窗口。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/models">Comparison of AI Models across Intelligence, Performance, and Price</a></li>
<li><a href="https://kilo.ai/open-source-models">Kilo - Best Open Source AI Models for Coding (2026)</a></li>
<li><a href="https://www.linkedin.com/pulse/open-weight-ai-what-we-finally-opened-bonnet-nicolas-pistorio-n3ulf">Open - weight AI : what if we finally opened the bonnet ?</a></li>

</ul>
</details>

**标签**: `#AI`, `#Open Source`, `#Podcast`, `#Industry Discussion`

---

<a id="item-4"></a>
## [新的 800 页 64 位汇编编程书籍](https://nostarch.com/art-64-bit-assembly-v2) ⭐️ 7.0/10

一本名为《64 位汇编的艺术》的详细 800 页书籍已经出版，重点介绍在 Windows 下使用 Microsoft MASM 汇编器进行 64 位汇编编程。 这本书为对低级编程和汇编语言感兴趣的人提供了一个全面的资源，这些知识对于理解硬件和系统级操作仍然非常重要。 这本书涵盖了基本的汇编语言编程、整数和浮点运算、SIMD（SSE/AVX）编程、字符串和位操作等主题。它旨在弥合理论知识和实际理解之间的差距。

hackernews · 0x54MUR41 · Aug 1, 14:09 · [社区讨论](https://news.ycombinator.com/item?id=49134599)

**背景**: 汇编语言是一种低级编程语言，它提供了与计算机指令集架构最小的抽象。它允许程序员完全控制程序内存和机器代码指令，使其成为需要直接硬件交互的任务所必需的。64 位 x86-64 架构在现代计算中被广泛使用，学习其汇编语言对于系统级编程和性能优化非常有价值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artofasm.randallhyde.com/">Randall Hyde - The Art of 64-bit Assembly Language</a></li>
<li><a href="https://en.wikipedia.org/wiki/Low-level_programming_language">Low-level programming language</a></li>

</ul>
</details>

**社区讨论**: 社区讨论中包含各种反应，一些人批评营销文案和使用的特定工具，而另一些人则认可这本书的潜在影响和汇编语言的持续相关性。还有一些评论者表示有兴趣提高他们的汇编技能。

**标签**: `#assembly`, `#programming`, `#low-level`, `#64-bit`, `#education`

---

<a id="item-5"></a>
## [加拿大签署联合国网络犯罪公约，引发隐私担忧](https://www.michaelgeist.ca/2026/07/a-surveillance-treaty-in-disguise-the-trouble-with-canadas-quiet-decision-to-sign-the-un-cybercrime-convention/) ⭐️ 7.0/10

加拿大签署了《联合国打击网络犯罪公约》，该条约旨在促进国际间在执行网络犯罪法律方面的合作。 签署这一条约意义重大，因为它可能会增加监控和侵犯隐私的行为，引起了隐私倡导者和人权组织的担忧。 该条约也被称为《河内公约》，于 2024 年 12 月由联合国大会通过，旨在加强国际间在严重犯罪电子证据共享方面的合作。

hackernews · iamnothere · Aug 1, 14:19 · [社区讨论](https://news.ycombinator.com/item?id=49134694)

**背景**: 《联合国打击网络犯罪公约》是俄罗斯于 2017 年提出的，这是首个全面的全球性网络犯罪条约。它为各国提供了预防和打击网络犯罪的措施，但由于潜在的隐私问题，该条约遭到了人权组织的抵制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/United_Nations_Convention_against_Cybercrime">United Nations Convention against Cybercrime - Wikipedia</a></li>
<li><a href="https://www.unodc.org/unodc/en/cybercrime/convention/home.html">United Nations Convention against Cybercrime</a></li>

</ul>
</details>

**社区讨论**: 社区成员对加拿大的决定表达了复杂的情绪，一些人认为这是国际合作的必要步骤，而另一些人则担心这可能会增加监控和侵犯隐私的行为。

**标签**: `#cybersecurity`, `#privacy`, `#international-policy`, `#surveillance`

---

<a id="item-6"></a>
## [微软发布 Flint，一种面向 AI 的可视化语言](https://microsoft.github.io/flint-chart/) ⭐️ 7.0/10

微软发布了 Flint，这是一种新的可视化语言，旨在简化 AI 代理创建数据可视化的过程。 这一发展意义重大，因为它旨在使数据可视化对 AI 来说更加易于访问和高效，从而可能提高 AI 系统生成图表的质量和表现力。 Flint 支持 50 种图表类型，并从数据、语义类型、图表类型和编码中推导出优化的图表设置，减少了对冗长的低级参数的需求。

hackernews · vinhnx · Aug 1, 02:45 · [社区讨论](https://news.ycombinator.com/item?id=49130604)

**背景**: 数据可视化对于理解和解释复杂数据至关重要。传统工具通常需要详细的配置，这可能会很繁琐。Flint 旨在通过允许 AI 代理使用简单且可人工编辑的规范来创建富有表现力和精美的可视化效果，从而简化这一过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://microsoft.github.io/flint-chart/">Flint: A Visualization Language for the AI Era</a></li>
<li><a href="https://www.microsoft.com/en-us/research/blog/flint-a-visualization-language-for-the-ai-era/">Flint: A visualization language for the AI era - Microsoft ...</a></li>

</ul>
</details>

**社区讨论**: 一些社区成员将 Flint 与现有的工具如 GGPlot 进行了比较，指出虽然 GGPlot 的 API 备受推崇，但 Flint 为 AI 提供了一个更简单的接口。其他人则认为，由 AI 直接生成 Vega Lite 规范可能会提供更多的灵活性和更高品质的可视化效果。

**标签**: `#visualization`, `#AI`, `#data-analysis`, `#programming-languages`

---

<a id="item-7"></a>
## [smevals：评估 AI 模型和提示的新工具](https://simonwillison.net/2026/Jul/31/smevals/#atom-everything) ⭐️ 7.0/10

Simon Willison 与 Jesse Vincent 的 Prime Radiant 应用 AI 研究实验室合作，推出了 smevals，这是一个旨在对不同模型配置运行小型评估套件并评分的新工具。 这个工具很重要，因为它提供了一种结构化且文档齐全的方法来评估和比较不同 AI 模型的能力，可以为研究人员和从业者简化评估过程。 该工具允许用户创建评估套件，针对多个模型运行，并对结果进行评分。它还包括一个用于探索结果的 Web 服务器和一个用于生成静态 HTML 报告的命令。

rss · Simon Willison · Jul 31, 21:15

**背景**: 评估 AI 模型对于理解它们的能力和局限性至关重要。像 smevals 这样的工具有助于系统地测试和比较不同的模型、提示和配置。Prime Radiant 是一个专注于为代理执行工作而人类进行思考的世界构建工具和方法的 AI 研究实验室。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jul/31/smevals/">smevals—a small eval suite for evaluating models, prompts ...</a></li>
<li><a href="https://primeradiant.com/about/">About | Prime Radiant</a></li>

</ul>
</details>

**标签**: `#AI`, `#Model Evaluation`, `#Tooling`

---

<a id="item-8"></a>
## [RipGrep musl 二进制文件在大规模搜索中偶尔崩溃](https://github.com/BurntSushi/ripgrep/issues/3494) ⭐️ 6.0/10

GitHub 上的一个问题和 Hacker News 的讨论指出，RipGrep 的 musl 二进制文件在进行非常大的搜索时偶尔会崩溃。 这个问题影响了广泛使用的搜索工具 RipGrep 的可靠性，特别是在高性能和大规模环境中，这可能会影响到依赖它进行关键任务的用户。 问题与 musl 中的默认分配器有关，该分配器在多线程场景中可能无法很好地处理竞争。社区成员建议使用性能更好的分配器可以缓解这个问题。

hackernews · throwaway2037 · Aug 1, 12:34 · [社区讨论](https://news.ycombinator.com/item?id=49133889)

**背景**: RipGrep 是一个面向行的搜索工具，递归地搜索目录，以其速度和效率著称。musl 是一个轻量级的 C 标准库实现，常用于创建静态二进制文件。这两种工具的结合在创建快速、自包含的可执行文件方面很受欢迎。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/BurntSushi/ripgrep">BurntSushi / ripgrep: ripgrep recursively searches directories ... - GitHub</a></li>
<li><a href="https://ripgrep.dev/">ripgrep - Lightning-Fast Search Tool for Developers</a></li>
<li><a href="https://musl.cc/">musl libc toolchains | static cross/native toolchains</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了性能和内存管理问题，一些人建议用性能更好的分配器替换 musl 中的默认分配器。其他人指出，在 HPC 集群上对大型文件系统运行 RipGrep 可能会导致显著的 I/O 瓶颈。

**标签**: `#RipGrep`, `#Performance`, `#Memory Management`, `#Community Discussion`

---

