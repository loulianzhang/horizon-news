# Horizon 每日速递 - 2026-07-07

> From 10 items, 6 important content pieces were selected

---

1. [聊天控制 1.0 和 2.0：概述与担忧](#item-1) ⭐️ 8.0/10
2. [欧盟议会通过聊天控制第一轮投票](#item-2) ⭐️ 8.0/10
3. [sqlite-utils 4.0 添加了模式迁移、嵌套事务和复合外键](#item-3) ⭐️ 8.0/10
4. [腾讯发布 2950 亿参数的 MoE 模型 Hy3](#item-4) ⭐️ 8.0/10
5. [StreetComplete：通过小任务改进 OpenStreetMap](#item-5) ⭐️ 7.0/10
6. [30papers.com：Ilya 的 30 篇机器学习重要论文，适合初学者](#item-6) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [聊天控制 1.0 和 2.0：概述与担忧](https://fightchatcontrol.eu/chat-control-overview) ⭐️ 8.0/10

新闻提供了聊天控制 1.0 和 2.0 的概述，这些措施涉及扫描私人消息以查找儿童性虐待材料，引发了关于隐私和监控的重大担忧。 这很重要，因为它突显了在线保护儿童与维护数字隐私和安全之间的紧张关系，影响了广泛的用户和平台。 聊天控制 1.0 是对电子隐私指令的临时豁免，允许（但不要求）提供商扫描私人消息。仍在讨论中的聊天控制 2.0 旨在使此类扫描成为法律要求，可能会破坏端到端加密。

hackernews · gasull · Jul 7, 14:23 · [社区讨论](https://news.ycombinator.com/item?id=48818311)

**背景**: 《防止和打击儿童性虐待条例》（通常称为聊天控制）是欧盟于 2022 年提出的一项法规。它旨在通过数字平台的普遍监控等措施来防止在线儿童性虐待。然而，该法规因可能侵犯隐私和数据保护的基本权利而受到批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control_1.0">Chat Control 1.0</a></li>
<li><a href="https://eutechloop.com/double-threat/">Double threat to privacy: Chat Control 1.0 and 2.0 are back</a></li>
<li><a href="https://www.expressvpn.com/blog/eu-chat-control-legislation/">Explainer: The EU's Chat Control Legislation | ExpressVPN Blog</a></li>

</ul>
</details>

**社区讨论**: 社区成员表达了对法律广泛性的担忧，以及可能的隐私侵犯和对加密消息的影响。一些人认为应该使用更具体和高效的方法来解决这个问题。

**标签**: `#privacy`, `#security`, `#policy`, `#surveillance`, `#child-safety`

---

<a id="item-2"></a>
## [欧盟议会通过聊天控制第一轮投票](https://www.heise.de/en/news/Showdown-in-Strasbourg-The-unexpected-return-of-Chat-Control-1-0-11356680.html) ⭐️ 8.0/10

欧盟议会通过了旨在通过扫描在线通信来防止和打击儿童性虐待的“聊天控制”法规的第一轮投票。 这项法规可能对数字隐私和通信产生重大影响，因为它可能要求在线服务使用客户端扫描技术，从而可能破坏端到端加密。 这项被称为《儿童性虐待条例》（CSAR）的法规由欧盟内政事务专员伊尔瓦·约翰逊于 2022 年 5 月提出。接下来的步骤将涉及进一步的投票和潜在的修正案。

hackernews · miroljub · Jul 7, 15:16 · [社区讨论](https://news.ycombinator.com/item?id=48819008)

**背景**: 聊天控制法规是欧盟加强数字隐私和安全的更广泛努力的一部分。它基于现有的框架，如《通用数据保护条例》（GDPR）和《数字服务法》（DSA）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>
<li><a href="https://www.techpolicy.press/how-europes-chat-control-regulation-could-compromise-american-communications/">How Europe’s “Chat Control” Regulation Could Compromise American Communications | TechPolicy.Press</a></li>

</ul>
</details>

**社区讨论**: 社区成员表达了对该法规可能对隐私产生的影响以及通过该法规所使用的程序策略的担忧。一些人担心，该法规可能会为其他国家采用类似措施树立先例，影响全球数字通信。

**标签**: `#EU Legislation`, `#Privacy`, `#Digital Communication`, `#Regulation`

---

<a id="item-3"></a>
## [sqlite-utils 4.0 添加了模式迁移、嵌套事务和复合外键](https://simonwillison.net/2026/Jul/7/sqlite-utils-4/#atom-everything) ⭐️ 8.0/10

sqlite-utils 4.0 引入了主要功能，包括数据库模式迁移、嵌套事务和支持复合外键。 这些新功能增强了工具的功能，使其在管理 SQLite 数据库时更加强大和灵活，这对于依赖这一广泛使用的工具的开发人员和数据管理人员来说非常重要。 sqlite-utils 4.0 中的模式迁移使用 Python 文件定义，并包含一个 `table.transform()` 方法以增强表修改功能。此次发布还包括一些破坏性变更，这些变更在升级指南中有详细说明。

rss · Simon Willison · Jul 7, 19:32

**背景**: SQLite 是一种广泛使用的开源关系型数据库管理系统。随着应用程序的发展，模式迁移对于演进数据库结构至关重要。复合外键允许使用多个列作为外键，为数据库设计提供了更大的灵活性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://one2n.io/blog/database-schema-migrations-a-practical-guide-for-mastering-change">A practical guide for database schema migrations | One2N</a></li>
<li><a href="https://en.wikipedia.org/wiki/Composite_key">Composite key - Wikipedia</a></li>

</ul>
</details>

**标签**: `#SQLite`, `#Database Management`, `#Version Release`, `#Schema Migrations`

---

<a id="item-4"></a>
## [腾讯发布 2950 亿参数的 MoE 模型 Hy3](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

腾讯发布了 Hy3，这是一个 2950 亿参数的混合专家（MoE）模型，具有 210 亿活跃参数，性能优于同类模型，并且在 7 月 21 日之前可以在 OpenRouter 上免费使用。 这次发布意义重大，因为它展示了 MoE 模型能够在较少的活跃参数下实现高性能，使其在各种 AI 应用中更加高效和易于访问。 完整模型大小为 598GB，FP8 量化版本为 300GB。上下文长度为 256K，并且在各种产品和生产力任务中显示出显著的实用性提升。

rss · Simon Willison · Jul 6, 23:57

**背景**: 混合专家（MoE）模型是一种神经网络架构，它使用多个专家子模型，每个子模型专门处理数据的不同方面。这使得模型既大又高效，因为只有必要的专家会被激活来处理特定输入。FP8 量化是一种技术，将模型权重和激活值减少到 8 位浮点格式，从而提高推理性能同时保持准确性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://www.ibm.com/think/topics/mixture-of-experts">What is mixture of experts? | IBM</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#NLP`, `#Models`, `#Tencent`

---

<a id="item-5"></a>
## [StreetComplete：通过小任务改进 OpenStreetMap](https://streetcomplete.app/) ⭐️ 7.0/10

StreetComplete 是一款应用程序，允许用户通过在其所在地区完成小型、具体的任务或“任务”来为 OpenStreetMap 做出贡献。 这款工具使普通贡献者和初学者更容易提高地图数据的质量，从而提升 OpenStreetMap 的整体准确性和完整性。 该应用程序会提示用户回答关于其周围地点和物体的简单问题，例如营业时间或特定特征的存在。它设计得非常用户友好，不需要用户事先了解 OpenStreetMap。

hackernews · kls0e · Jul 7, 12:38 · [社区讨论](https://news.ycombinator.com/item?id=48816883)

**背景**: OpenStreetMap（OSM）是一个由志愿者创建的免费可编辑的世界地图。与专有地图不同，OSM 是开放的，任何人都可以编辑，使其成为各种应用的宝贵资源。StreetComplete 通过将任务分解成易于管理的小任务，简化了对 OSM 的贡献过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/StreetComplete">StreetComplete - Wikipedia</a></li>
<li><a href="https://streetcomplete.app/">StreetComplete</a></li>
<li><a href="https://wiki.openstreetmap.org/wiki/StreetComplete">StreetComplete - OpenStreetMap Wiki</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了使用 StreetComplete 的积极体验，指出它的易用性和为 OpenStreetMap 做贡献的乐趣。一些用户还建议增加更多功能，例如添加简单的道路和人行道。

**标签**: `#OpenStreetMap`, `#Mapping`, `#Community Engagement`, `#Mobile App`

---

<a id="item-6"></a>
## [30papers.com：Ilya 的 30 篇机器学习重要论文，适合初学者](https://30papers.com/) ⭐️ 7.0/10

一个名为 30papers.com 的网站整理了 Ilya 的 30 篇重要的机器学习论文，并以适合初学者的格式呈现，社区贡献和讨论进一步增加了其价值。 这个资源非常重要，因为它以易于理解的格式提供了一份精心挑选的重要机器学习论文列表，使新进入该领域的人更容易理解和参与关键研究。社区讨论和 PdfToMp3、ListenDock 等附加工具进一步提升了整体价值。 该网站包括社区贡献和讨论，以及像 PdfToMp3 和 ListenDock 这样的工具，分别可以将 PDF 转换为音频并提供教师解释。该网站仍在不断完善中，欢迎贡献和反馈。

hackernews · notmcrowley · Jul 7, 15:58 · [社区讨论](https://news.ycombinator.com/item?id=48819608)

**背景**: 机器学习（ML）是人工智能的一个子集，涉及使用算法和统计模型使计算机能够通过经验改进任务。该领域的研究论文通常很复杂，对于初学者来说可能难以理解。精心挑选的列表和适合初学者的格式有助于使这些资源更易于访问。

**社区讨论**: 一些社区成员对列表的来源和组织方式表示了担忧，而其他人则贡献了工具和见解，如 PdfToMp3 和 ListenDock，以增强学习体验。作者是一名大一的计算机科学学生，他将该网站作为副项目创建，并愿意接受反馈和贡献。

**标签**: `#Machine Learning`, `#Education`, `#Resources`, `#Community`

---

