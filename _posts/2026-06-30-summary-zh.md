---
layout: default
title: "Horizon Summary: 2026-06-30 (ZH)"
date: 2026-06-30
lang: zh
---

> From 17 items, 12 important content pieces were selected

---

1. [Claude AI 使用隐写术标记用户请求](#item-1) ⭐️ 8.0/10
2. [Postgres 19 将引入原生应用时间时态数据支持](#item-2) ⭐️ 8.0/10
3. [Zluda 6 使未修改的 CUDA 应用程序在非 Nvidia GPU 上运行](#item-3) ⭐️ 8.0/10
4. [Anthropic 发布 Claude Sonnet 5 用于自主开发](#item-4) ⭐️ 7.0/10
5. [Claude Science：具有广泛集成的新数据科学工具](#item-5) ⭐️ 7.0/10
6. [Nano Banana 2 Lite：更快的 AI 图像生成模型](#item-6) ⭐️ 7.0/10
7. [当前一代可能是最后一批理解基础技术的人](#item-7) ⭐️ 7.0/10
8. [拥有 37 个数据中心的县要求学校节约用电](#item-8) ⭐️ 7.0/10
9. [关于金融泡沫和群体行为的经典书籍](#item-9) ⭐️ 7.0/10
10. [欧洲数字身份钱包依赖谷歌和苹果的服务](#item-10) ⭐️ 7.0/10
11. [shot-scraper 1.10 新增网页应用演示视频录制功能](#item-11) ⭐️ 7.0/10
12. [Simon Willison 推出新的 HTML 表格提取工具](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Claude AI 使用隐写术标记用户请求](https://thereallo.dev/blog/claude-code-prompt-steganography) ⭐️ 8.0/10

一篇博客文章揭示了 AI 服务 Claude 正在使用隐写术来标记用户请求，引发了关于透明度和道德实践的担忧。 这种做法引发了对 AI 服务透明度和可信度的重大担忧，因为用户可能不知道他们的请求中隐藏了标记。 隐写术标记用于识别特定实体（如中国公司）的使用情况，这些实体可能正在进行模型蒸馏。尽管这种方法有效，但其实施方式可以通过逆向工程被检测到。

hackernews · kirushik · Jun 30, 15:44 · [社区讨论](https://news.ycombinator.com/item?id=48734373)

**背景**: 隐写术是一种将信息隐藏在另一条消息或物理对象中的技术，使其对不知情的人不可见。在数字通信的背景下，这可以包括将数据隐藏在文件、图像或其他媒体中。Claude 是由 Anthropic 开发的 AI 助手，旨在帮助完成各种任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Steganography">Steganography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (AI) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 一些社区成员对缺乏透明度和潜在的滥用表示担忧，而其他人则认为隐写术背后的意图是明确且合理的。还有关于技术实现和更复杂方法的可能性的讨论。

**标签**: `#AI Ethics`, `#Steganography`, `#Transparency`, `#AI Services`, `#Security`

---

<a id="item-2"></a>
## [Postgres 19 将引入原生应用时间时态数据支持](https://www.snowflake.com/en/blog/engineering/postgresql-19-features-beta/) ⭐️ 8.0/10

Postgres 19 预计将引入基于 SQL:2011 标准的原生应用时间时态数据支持，以及其他改进和功能。 这一新功能将增强数据库管理历史数据的能力，使其在需要基于时间的数据管理的应用中更加多才多艺和强大。它还满足了社区的重要需求，提升了整体用户体验和操作效率。 应用时间时态数据支持可以更好地管理随时间变化的数据，提供更强大的解决方案来跟踪和查询历史数据。此外，该版本还包括 COPY 和逻辑复制的改进，这对备份和数据传输操作非常有益。

hackernews · thinkingemote · Jun 30, 14:14 · [社区讨论](https://news.ycombinator.com/item?id=48733031)

**背景**: PostgreSQL，通常简称为 Postgres，是一个强大、开源的关系型数据库系统，以其可靠性、功能丰富性和性能而闻名。PostgreSQL 全球开发组每年大约发布一个包含新功能的主要版本。时态数据支持是一种允许数据库存储和查询带有时间维度的数据的功能，使用户能够查看数据随时间的变化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Temporal_database">Temporal database - Wikipedia</a></li>
<li><a href="https://www.postgresql.org/support/versioning/">PostgreSQL: Versioning Policy</a></li>
<li><a href="https://www.postgresql.org/docs/release/">PostgreSQL: Release Notes</a></li>

</ul>
</details>

**社区讨论**: 社区成员对新功能表示兴奋，特别是原生应用时间时态数据支持。然而，一些用户也提出了缺乏列式存储和轻量级连接的需求。还有人希望能够在主要版本之间进行就地升级，特别是在 Docker 环境中。

**标签**: `#Postgres`, `#Database`, `#Version Release`, `#Community Discussion`

---

<a id="item-3"></a>
## [Zluda 6 使未修改的 CUDA 应用程序在非 Nvidia GPU 上运行](https://vosen.github.io/ZLUDA/blog/zluda-update-q1q2-2026/) ⭐️ 8.0/10

Zluda 6 已发布，该工具允许在非 Nvidia GPU 上运行未修改的 CUDA 应用程序，并带来了新功能和开发重点的转变。 此次发布意义重大，因为它扩大了 CUDA 应用程序对更广泛硬件的可访问性，可能减少高性能计算任务对 Nvidia GPU 的依赖。 新版本包括 32 位 PhysX 支持和其他功能，该项目现在是一个个人周末项目，专注于开发者觉得最有趣的方面。

hackernews · Tiberium · Jun 30, 10:34 · [社区讨论](https://news.ycombinator.com/item?id=48730713)

**背景**: CUDA（统一计算设备架构）是 Nvidia 开发的一种专有并行计算平台和应用程序编程接口，允许软件使用 GPU 进行通用处理。ZLUDA 是一个开源工具，它使未修改的 CUDA 应用程序能够在非 Nvidia GPU 上运行，主要通过 ROCm 在 AMD GPU 上实现接近原生的性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/ZLUDA">ZLUDA</a></li>
<li><a href="https://github.com/vosen/ZLUDA">GitHub - vosen/ZLUDA: CUDA on non-NVIDIA GPUs · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/CUDA">CUDA</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了开发重点转向个人兴趣，增加了 32 位 PhysX 支持这一有趣的功能，并对与 Vulkan 相比其在大型语言模型上的性能表示好奇。

**标签**: `#CUDA`, `#GPU`, `#Open-Source`

---

<a id="item-4"></a>
## [Anthropic 发布 Claude Sonnet 5 用于自主开发](https://www.anthropic.com/news/claude-sonnet-5) ⭐️ 7.0/10

Anthropic 宣布发布了 Claude Sonnet 5，这是一个设计为更具自主性和能够独立运行的 AI 模型。它针对自主和代理辅助开发进行了优化。 这个新模型旨在为需要自主性的任务提供更具成本效益的解决方案，但社区反馈表明，在所有场景中，特别是在高努力任务中，它可能不会优于现有模型。 Claude Sonnet 5 比其前身 Sonnet 4.6 表现出更低的不良行为率，在代理环境中使用更安全。然而，与 Opus 模型相比，它在执行网络安全任务方面的能力要低得多。

hackernews · marinesebastian · Jun 30, 17:59 · [社区讨论](https://news.ycombinator.com/item?id=48736605)

**背景**: Claude 是由 Anthropic 开发的一系列大型语言模型，使用“宪法 AI”进行训练以提高道德和法律合规性。每一代 Claude 通常有三种规模：Haiku、Sonnet 和 Opus。自主和代理辅助开发涉及可以最小化人工干预来编排和执行软件开发任务的 AI 系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-sonnet-5">Introducing Claude Sonnet 5 \ Anthropic</a></li>
<li><a href="https://techcrunch.com/2026/06/30/anthropic-launches-claude-sonnet-5-as-a-cheaper-way-to-run-agents/">Anthropic launches Claude Sonnet 5 as a cheaper way to run agents | TechCrunch</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 Claude Sonnet 5 的看法不一。一些用户赞赏它在某些任务上的成本效益，而另一些用户则认为它在高努力任务上不如其他模型（如 Opus）能力强且成本更高。还有人对其在特定领域（如网络安全）的表现表示担忧。

**标签**: `#AI`, `#Machine Learning`, `#Model Comparison`, `#Autonomous Agents`

---

<a id="item-5"></a>
## [Claude Science：具有广泛集成的新数据科学工具](https://claude.com/product/claude-science) ⭐️ 7.0/10

Claude Science 是一款新的数据科学工具，集成了多个数据库和计算工具，包括机构集群，以增强研究能力。 该工具通过提供对各种资源和计算能力的无缝访问，可以显著提高数据科学和科学研究的效率和效果。 Claude Science 集成了诸如 Biomni HPC 等数据库和计算工具，并支持 Jupyter Notebook 2.0，使其成为研究人员的多功能工具。

hackernews · lebovic · Jun 30, 17:07 · [社区讨论](https://news.ycombinator.com/item?id=48735770)

**背景**: 数据科学和科学计算通常需要访问强大的计算资源和多样化的数据源。机构集群是一组互连的计算机，提供高性能计算能力，这对于复杂的数据分析和模拟至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0167268111001089">Institutional clusters and economic performance - ScienceDirect</a></li>
<li><a href="https://medium.com/data-science-collective/how-i-use-llms-as-a-data-scientist-fa9a85262773">How I use LLMs as a Data Scientist | by Marc Matterson | Data Science Collective | Medium</a></li>
<li><a href="https://www.pecan.ai/blog/llm-data-science-and-analytics/">How are LLMs Used in Data Science and Analytics? | Pecan AI</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了 Claude Science 不仅仅局限于数据可视化和论文写作，但也表达了对 LLM 在技术讨论中占据主导地位以及数据可能被滥用的担忧。一些研究人员由于担心数据被滥用和抢先发布他们的工作而对使用 LLM 持谨慎态度。

**标签**: `#data-science`, `#research-tools`, `#LLMs`, `#scientific-computing`

---

<a id="item-6"></a>
## [Nano Banana 2 Lite：更快的 AI 图像生成模型](https://deepmind.google/models/gemini-image/flash-lite/) ⭐️ 7.0/10

Google DeepMind 推出了 Nano Banana 2 Lite，这是 Nano Banana 2 AI 模型的一个更快版本，并且提供了早期访问反馈和社区对其性能和功能的讨论。 这个更快的 AI 模型版本可以显著减少图像生成时间，使其在实时应用中更加实用，并在各种使用场景中提升用户体验。 Nano Banana 2 Lite 保持了与原版 Nano Banana 2 相似的良好文本渲染能力，但在细微之处不如原版。它生成图像的时间不到 5 秒，而基础版 Nano Banana 2 需要大约 30 秒。

hackernews · minimaxir · Jun 30, 16:48 · [社区讨论](https://news.ycombinator.com/item?id=48735444)

**背景**: Nano Banana 2 是 Google DeepMind 开发的一种 AI 图像生成模型，基于 Gemini Flash Image 基础构建。它结合了高级功能和快速编辑及迭代能力。该模型将创意方向解释为多模态语言模型，捕捉单一模态系统可能错过的细微差别和上下文。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/ai/nano-banana-2/">Nano Banana 2: Google’s latest AI image generation model</a></li>
<li><a href="https://gemini.google/overview/image-generation/">Nano Banana 2 - Gemini AI image generator & photo editor</a></li>
<li><a href="https://fal.ai/models/fal-ai/nano-banana-2">Nano Banana 2: Fast AI Image Generation by Google | fal</a></li>

</ul>
</details>

**社区讨论**: 社区成员提供了多样化的反馈，包括对速度的赞扬以及无法通过编程强制设置宽高比的批评。一些用户对实时应用的潜力感到兴奋，而其他人则对特定情境下（如房地产）生成图像的质量表示担忧。

**标签**: `#AI`, `#Machine Learning`, `#Image Generation`, `#DeepMind`, `#Nano Banana`

---

<a id="item-7"></a>
## [当前一代可能是最后一批理解基础技术的人](https://unix.foo/posts/last-people-who-know-how-it-works/) ⭐️ 7.0/10

文章探讨了当前一代可能是最后一批能够深入理解基础技术如何工作的一代，因为新的抽象和接口变得越来越普遍。 这一趋势突显了人们与技术互动和理解方式的重大转变，可能会导致我们依赖的系统失去深厚的技术知识和控制。 文章指出，虽然新的抽象使技术更加易于访问，但它们也创造了复杂的层次，可能掩盖了底层机制。

hackernews · cylo · Jun 30, 16:59 · [社区讨论](https://news.ycombinator.com/item?id=48735633)

**背景**: 过去，用户经常需要理解和操作计算机的低级组件，例如编辑配置文件或创建启动磁盘。随着技术的发展，这些交互变得越来越少，被更高级的抽象和用户友好的界面所取代。

**社区讨论**: 社区成员讨论了深厚技术知识的丧失以及对高级抽象的日益依赖。一些人表达了对未来技术的理解可能需要放弃现有知识的担忧，以及对失去控制的不安。

**标签**: `#technology`, `#software engineering`, `#cultural shift`

---

<a id="item-8"></a>
## [拥有 37 个数据中心的县要求学校节约用电](https://www.404media.co/henrico-virginia-datacenter-energy-cost-email/) ⭐️ 7.0/10

拥有 37 个数据中心的亨里科县要求当地学校节约用电，突显了数据中心运营日益增长的能源需求和挑战。 这种情况突显了数据中心对当地能源消耗的重大影响，以及科技行业需要采取可持续实践。 《弗吉尼亚清洁经济法案》要求电力公司 Dominion 在 2045 年前实现 100%可再生能源转型，导致目前对尚未投入使用的可再生能源项目的投资。

hackernews · 01-_- · Jun 30, 16:05 · [社区讨论](https://news.ycombinator.com/item?id=48734699)

**背景**: 数据中心是数字经济的关键基础设施，但它们消耗大量电力。2023 年，美国数据中心的年度能源使用量约为 176 太瓦时（TWh），约占美国年度总电力消耗的 4.4%。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.congress.gov/crs-product/R48646">Data Centers and Their Energy Consumption: Frequently Asked Questions | Congress.gov | Library of Congress</a></li>
<li><a href="https://www.ey.com/en_us/data-centers/enable-data-center-growth-and-advance-sustainability">Enable data center growth and advance sustainability | EY - US</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了向可再生能源转型的挑战、建设新发电厂的可能性以及该地区的高电价。一些人还指出，尽管短期内存在挑战，但这种转型具有长期益处。

**标签**: `#data centers`, `#energy consumption`, `#sustainability`, `#infrastructure`

---

<a id="item-9"></a>
## [关于金融泡沫和群体行为的经典书籍](https://www.gutenberg.org/ebooks/24518) ⭐️ 7.0/10

1852 年的《非凡大众幻想与群体性疯狂的回忆》一书探讨了历史上金融泡沫和群体非理性行为的实例。 这本书对于理解市场动态和金融泡沫背后的心理学非常有帮助，为经济学家和投资者提供了宝贵的见解。 书中详细描述了南海泡沫和郁金香狂热等历史事件，尽管其中一些描述可能被夸大或渲染。

hackernews · lstodd · Jun 30, 12:47 · [社区讨论](https://news.ycombinator.com/item?id=48731989)

**背景**: 查尔斯·麦凯的《非凡大众幻想与群体性疯狂的回忆》是行为经济学领域的开创性著作，研究了集体热情和恐慌如何导致金融危机。这本书对现代经济思想产生了重要影响。

**社区讨论**: 社区成员称赞这本书内容深刻且有趣，但也有人指出它可能夸大了一些历史事件。其他阅读建议包括约翰·肯尼斯·加尔布雷斯的《金融狂热简史》。

**标签**: `#finance`, `#history`, `#behavioral-economics`

---

<a id="item-10"></a>
## [欧洲数字身份钱包依赖谷歌和苹果的服务](https://waag.org/en/article/european-digital-id-wallets-are-gift-google-and-apple/) ⭐️ 7.0/10

欧洲数字身份钱包现在依赖谷歌和苹果提供的安全服务，引发了关于数字主权和安全的担忧。 这种对美国科技巨头的依赖可能会削弱欧盟实现数字主权的努力，并可能带来安全风险。 欧盟数字身份钱包旨在让用户安全地请求、存储和共享重要的数字文件，但其功能需要谷歌 Play 服务和苹果的服务支持。

hackernews · donohoe · Jun 30, 10:36 · [社区讨论](https://news.ycombinator.com/item?id=48730729)

**背景**: 欧盟数字身份钱包是 eIDAS 框架的一部分，旨在建立一个欧洲数字身份。该钱包旨在使各种任务变得更加容易和安全，例如开设银行账户或在国外大学注册。数字主权指的是国家在不受外国实体不当影响的情况下控制自己的数字基础设施、数据和技术的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EU_Digital_Identity_Wallet">EU Digital Identity Wallet - Wikipedia</a></li>
<li><a href="https://ec.europa.eu/digital-building-blocks/sites/spaces/EUDIGITALIDENTITYWALLET/pages/694487738/EU+Digital+Identity+Wallet+Home">EU Digital Identity Wallet Home - European Commission</a></li>
<li><a href="https://en.wikipedia.org/wiki/Digital_sovereignty">Digital sovereignty</a></li>

</ul>
</details>

**社区讨论**: 社区成员表达了对依赖谷歌和苹果的担忧，一些人认为这会削弱数字自主权和主权。还有人讨论了政府过度干预的可能性以及需要替代方案。

**标签**: `#digital-identity`, `#security`, `#european-union`, `#google`, `#apple`

---

<a id="item-11"></a>
## [shot-scraper 1.10 新增网页应用演示视频录制功能](https://simonwillison.net/2026/Jun/30/shot-scraper-video/#atom-everything) ⭐️ 7.0/10

Simon Willison 在 shot-scraper 1.10 中引入了一个新功能，可以录制在 storyboard.yml 文件中定义的网页应用流程的视频演示。 这一功能非常重要，因为它使开发人员能够创建其网页应用的可视化演示，这对于测试、调试和展示功能非常有价值。 新的 `shot-scraper video` 命令使用 Playwright 录制视频，并支持通过 JSON 文件进行身份验证。该功能通过一个示例进行了展示，即从粘贴的 CSV、TSV 或 JSON 数据中在 Datasette 中创建新表。

rss · Simon Willison · Jun 30, 16:54

**背景**: shot-scraper 是一个用于自动截取屏幕截图和抓取网页的命令行工具。它基于 Playwright 构建，Playwright 是由微软开发的一个用于浏览器测试和网页抓取的开源自动化库。这个新功能扩展了它的能力，包括视频录制，增强了其在开发工作流中的实用性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://shot-scraper.datasette.io/">shot-scraper</a></li>
<li><a href="https://github.com/simonw/shot-scraper-template">GitHub - simonw/shot-scraper-template: Template repository for setting up shot-scraper · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Playwright_(software)">Playwright (software) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#web-development`, `#automation`, `#testing-tools`

---

<a id="item-12"></a>
## [Simon Willison 推出新的 HTML 表格提取工具](https://simonwillison.net/2026/Jun/29/html-table-extractor/#atom-everything) ⭐️ 6.0/10

Simon Willison 推出了一款名为 HTML 表格提取器的新工具，该工具可以将包含嵌入式 HTML 表格的富文本转换为 HTML、Markdown、CSV、TSV 或 JSON 等多种格式。 这款工具对于数据处理和操作非常重要，因为它简化了将 HTML 表格转换为更可用格式的过程，使从网页中处理表格数据变得更加容易。 该工具支持多种输出格式，并可以通过粘贴维基百科页面的内容进行测试。它还包括一个更新，允许搜索维基百科页面并自动导入和显示该页面中的任何表格。

rss · Simon Willison · Jun 29, 23:38

**背景**: 包含嵌入式 HTML 表格的富文本可以从 Google Docs 或 MS Word 等外部来源复制并粘贴到网络工具中。这些工具通常缺乏对表格的原生支持，需要用户以 HTML 形式嵌入表格。粘贴转换工具可以帮助将这种富文本转换为更结构化和可用的格式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.contentful.com/help/content-and-entries/tables-in-rich-text-fields/">Tables in Rich Text fields | Contentful Help Center</a></li>
<li><a href="https://euangoddard.github.io/clipboard2markdown/">Paste to Markdown</a></li>

</ul>
</details>

**标签**: `#web tools`, `#data conversion`, `#HTML tables`

---