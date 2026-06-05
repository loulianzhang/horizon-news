# Horizon 每日速递 - 2026-06-05

> From 15 items, 9 important content pieces were selected

---

1. [微软开源 pg_durable，实现数据库内持久执行](#item-1) ⭐️ 8.0/10
2. [Gemma 4 QAT 模型优化移动和笔记本效率](#item-2) ⭐️ 8.0/10
3. [AI 爱好者与怀疑者：时间与熵的竞赛](#item-3) ⭐️ 8.0/10
4. [宇航员在修复空气泄漏后返回国际空间站](#item-4) ⭐️ 7.0/10
5. [软件工程中对规范提交的批评](#item-5) ⭐️ 7.0/10
6. [Gov.uk 改用 Adyen 进行支付处理](#item-6) ⭐️ 7.0/10
7. [家庭实验室中 IP KVM 的全面评测](#item-7) ⭐️ 7.0/10
8. [分析 Claude 对 rsync 错误的影响](#item-8) ⭐️ 7.0/10
9. [Ladybird 浏览器不再接受公共拉取请求](#item-9) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [微软开源 pg_durable，实现数据库内持久执行](https://github.com/microsoft/pg_durable) ⭐️ 8.0/10

微软开源了 pg_durable 工具，该工具能够在 PostgreSQL 中实现数据库内的持久执行，支持容错和长时间运行的 SQL 函数。 微软对 Postgres 生态系统的这一贡献可以显著提高后台工作和数据管道的可靠性，减少对外部服务和基础设施的需求。 pg_durable 允许用户用 SQL 定义工作流，对每个步骤进行检查点，并在崩溃或重启后恢复。它专为已经在 Postgres 中保存状态并希望避免管理多个外部系统的团队设计。

hackernews · coffeemug · Jun 5, 15:59 · [社区讨论](https://news.ycombinator.com/item?id=48414367)

**背景**: 持久执行确保即使在系统故障的情况下，事务的效果也能被保留。传统上，这通常是通过外部服务和复杂的设置来实现的，但 pg_durable 将这种能力直接带入数据库中，简化了架构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/microsoft/pg_durable">GitHub - microsoft/pg_durable: PostgreSQL in-database durable execution · GitHub</a></li>
<li><a href="https://news.ycombinator.com/item?id=48414367">pg_durable: Microsoft open sources in-database durable execution | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 社区讨论包括关于某些调用的幂等性的问题，与其他工具如 Temporal 的比较，以及对 Azure 的 Postgres 服务限制的关注。一些用户表达了对使用 pg_durable 的兴趣，但也强调了托管 Postgres 服务需要更好的支持和功能。

**标签**: `#Postgres`, `#Durable Execution`, `#Open Source`, `#Microsoft`

---

<a id="item-2"></a>
## [Gemma 4 QAT 模型优化移动和笔记本效率](https://blog.google/innovation-and-ai/technology/developers-tools/quantization-aware-training-gemma-4/) ⭐️ 8.0/10

谷歌发布了 Gemma 4 QAT 模型，这些模型针对移动设备和笔记本电脑的性能进行了优化。 这一模型压缩技术的进步非常重要，因为它使得日常设备能够更高效地使用 AI，从而提升用户体验和可访问性。 Gemma 4 QAT 模型可以处理音频和图像输入，12B 模型在 Q4_0 量化下只需要 6.7GB 的显存，可以轻松适应 16GB 的显存限制。

hackernews · theanonymousone · Jun 5, 16:18 · [社区讨论](https://news.ycombinator.com/item?id=48414653)

**背景**: 量化感知训练（QAT）是一种将权重精度降低集成到训练过程中的技术，使大型语言模型更加高效。这使得模型更小、更快、更节能，适合边缘设备使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/quantization-aware-training-gemma-4/">Gemma 4 with quantization-aware training</a></li>
<li><a href="https://unsloth.ai/docs/models/gemma-4/qat">Gemma 4 QAT | Unsloth Documentation</a></li>
<li><a href="https://pytorch.org/blog/quantization-aware-training/">Quantization-Aware Training for Large Language Models with PyTorch – PyTorch</a></li>

</ul>
</details>

**社区讨论**: 社区成员已经对这些模型进行了本地测试，并提供了实际见解，指出一些第三方量化，如 Unsloth 的量化，可能比谷歌的原始 QAT 表现更好。还有关于预期显存使用量以及在旧 GPU 上运行这些模型的潜力的讨论。

**标签**: `#AI`, `#Model Compression`, `#Quantization`, `#Mobile Efficiency`, `#Laptop Efficiency`

---

<a id="item-3"></a>
## [AI 爱好者与怀疑者：时间与熵的竞赛](https://simonwillison.net/2026/Jun/4/ai-enthusiasts-ai-skeptics/#atom-everything) ⭐️ 8.0/10

Charity Majors 的文章讨论了 AI 爱好者和怀疑者之间的不同观点，强调了创新的紧迫性以及软件开发中信任和上下文的潜在风险。 这一讨论很重要，因为它涉及快速采用 AI 所带来的现实影响和风险，这可能会影响软件系统的可靠性和一致性。 关键问题在于缺乏连接爱好者和怀疑者的自然反馈循环，使得弥合这一差距成为组织设计的挑战。

rss · Simon Willison · Jun 4, 23:55

**背景**: AI 爱好者推动快速创新，而怀疑者则担心可靠性和机构知识的退化。两组人员对于构建优秀的软件都是必不可少的，但他们往往在没有有效沟通的情况下各自为战。

**标签**: `#AI`, `#Software Development`, `#Innovation`, `#Risk Management`

---

<a id="item-4"></a>
## [宇航员在修复空气泄漏后返回国际空间站](https://www.bbc.com/news/live/c4g44ew3g1kt) ⭐️ 7.0/10

国际空间站（ISS）上的宇航员在躲避空气泄漏修复期间后，被指示恢复正常活动。 这一事件突显了维护国际空间站的安全和完整性的重要性，确保宇航员的健康和太空任务的持续进行。 修复工作包括多次检查和密封剂的应用，NASA 的机器人外部泄漏定位器（RELL）用于检测并确认泄漏修复。

hackernews · janpot · Jun 5, 15:00 · [社区讨论](https://news.ycombinator.com/item?id=48413464)

**背景**: 国际空间站（ISS）是位于近地轨道上的人造可居住卫星。它作为一个微重力和太空环境研究实验室，宇航员在其中进行各种领域的实验。RELL 是一种机器人工具，帮助任务操作员检测和定位国际空间站上的外部泄漏。

**社区讨论**: 社区成员讨论了 RELL 的技术细节以及检测和确认泄漏的挑战。还有关于国际空间站安全措施和应急程序的问题，包括气闸的使用和逃生舱的可用性。

**标签**: `#ISS`, `#Astronaut Safety`, `#Space Engineering`, `#NASA`

---

<a id="item-5"></a>
## [软件工程中对规范提交的批评](https://sumnerevans.com/posts/software-engineering/stop-using-conventional-commits/) ⭐️ 7.0/10

文章批评了规范提交的使用，认为它们可能不是结构化提交信息的最有效方式，并且不同的项目有不同的需求。 这一批评很重要，因为它挑战了软件工程中广泛采用的做法，鼓励开发者重新考虑他们的提交信息方法，并适应项目的具体需求。 文章指出，虽然规范提交提供了一个定义明确的结构，但并不总是增加价值，有时可能会过于规定性。它强调了围绕提交信息设定期望的重要性，但建议其他结构可能更适合不同的项目。

hackernews · jsve · Jun 5, 15:39 · [社区讨论](https://news.ycombinator.com/item?id=48414027)

**背景**: 规范提交是版本控制系统中标准化提交信息的一种规范。它根据代码更改的目的（如功能、错误修复或文档更新）对其进行分类，以促进自动生成变更日志和语义版本控制等自动化流程。其目标是创建一个明确的提交历史记录，使编写自动化工具变得更加容易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.conventionalcommits.org/en/v1.0.0/">Conventional Commits</a></li>
<li><a href="https://www.gitkraken.com/learn/git/best-practices/git-commit-message">How to Write a Good Git Commit Message | Git Best Practices</a></li>

</ul>
</details>

**社区讨论**: 社区成员对此意见不一。一些人认为规范提交提供了一个定义明确的结构并设定了期望，这是有价值的。其他人则认为不同的项目有不同的需求，规范提交并不总是能提供有用的信息。还有一些人担心提交标题中缺少问题编号，这对上下文来说是必不可少的。

**标签**: `#software-engineering`, `#version-control`, `#best-practices`

---

<a id="item-6"></a>
## [Gov.uk 改用 Adyen 进行支付处理](https://www.theregister.com/public-sector/2026/06/04/govuk-goes-dutch-on-payments-as-it-dumps-stripe/5250763) ⭐️ 7.0/10

英国政府的 Gov.uk 网站已从 Stripe 切换到 Adyen 作为其支付处理提供商，自 2026 年 6 月起生效。 这一变化可能会影响 Gov.uk 平台上的成本和支付选项，可能会对数百万用户和各种政府服务产生影响。 Adyen 以其全球覆盖和灵活的支付解决方案而闻名，与 Stripe 相比，可能提供更好的转化率和处理费率。这一切换也符合英国政府现代化和简化数字服务的努力。

hackernews · toomuchtodo · Jun 5, 16:55 · [社区讨论](https://news.ycombinator.com/item?id=48415217)

**背景**: Gov.uk Pay 是一项允许用户在线向英国政府付款的服务。它处理多种交易，包括市政税、罚款和其他政府费用。Adyen 是一家全球支付处理公司，提供多种支付方式并支持多种货币。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.adyen.com/online-payments">Online payments | Making online payments easy - Adyen</a></li>
<li><a href="https://www.nerdwallet.com/business/software/learn/adyen">Adyen Review 2024: Features, Pricing, Alternatives - NerdWallet</a></li>
<li><a href="https://wise.com/us/blog/adyen-payment-processing">Adyen Payment Processing : Products, Features & Pricing - Wise</a></li>

</ul>
</details>

**社区讨论**: 一些社区成员对相对较小的合同规模感到惊讶，而其他人则对潜在的成本节约和扩大的支付选项表示好奇。还有关于 Adyen 的营销和客户选择标准的讨论。

**标签**: `#payment-processing`, `#government-technology`, `#stripe`, `#adyen`

---

<a id="item-7"></a>
## [家庭实验室中 IP KVM 的全面评测](https://www.jeffgeerling.com/blog/2026/i-tested-every-ip-kvm/) ⭐️ 7.0/10

Jeff Geerling 在他的家庭实验室中测试并评测了多种 IP KVM，详细列出了每种设备的优点和缺点。 这篇评测对于那些正在设置或管理家庭实验室的人来说非常有价值，因为它提供了不同 IP KVM 的性能和可用性的实用见解。 评测包括 PiKVM V4 Plus、GL.iNet KVM 和 JetKVM 等设备，并突出了具体的使用场景和技术细节。

hackernews · vquemener · Jun 5, 14:30 · [社区讨论](https://news.ycombinator.com/item?id=48413072)

**背景**: IP KVM（键盘、视频和鼠标）切换器允许远程访问和控制多台计算机。在家庭实验室设置中特别有用，用户需要通过单一界面管理多台机器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/IPKVM">IPKVM</a></li>
<li><a href="https://pikvm.org/">KVM over IP - PiKVM</a></li>
<li><a href="https://grokipedia.com/page/Homelab">Homelab</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了他们的经验和额外见解，例如在 AI 驱动的笔记本电脑翻新中使用 PiKVM 以及 JetKVM 的新硬件版本的可用性。

**标签**: `#homelab`, `#IP KVM`, `#hardware review`

---

<a id="item-8"></a>
## [分析 Claude 对 rsync 错误的影响](https://alexispurslane.github.io/rsync-analysis/) ⭐️ 7.0/10

进行了一项分析，以确定在 rsync 开发中使用 AI Claude 是否增加了错误数量，引发了关于 AI 在软件开发中的作用的广泛讨论。 这项分析很重要，因为它突显了将 AI 集成到软件开发中的潜在风险和好处，这可能会影响行业未来的实践和政策。 该分析没有考虑提交的复杂性、安全强度或错误严重性，并且在归因错误时没有区分次要更新和主要更新。所使用的方法虽然粗糙，但为进一步调查提供了起点。

hackernews · logicprog · Jun 5, 12:43 · [社区讨论](https://news.ycombinator.com/item?id=48411635)

**背景**: rsync 是一个用于在计算机和存储驱动器之间传输和同步文件的工具，常用于类 Unix 系统。Claude 是由 Anthropic 开发的一个大型语言模型，应用于包括 AI 辅助软件开发在内的各种场景。将 AI 集成到软件开发中是一个日益增长的趋势，既有潜在的好处，也有关于代码质量和安全性的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_AI">Claude AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Rsync">Rsync</a></li>

</ul>
</details>

**社区讨论**: 社区成员对该分析的看法不一。一些人认为该方法过于简单，没有考虑到提交的复杂性。其他人则认为，对维护者的压力可能会阻碍负责任地披露 AI 使用情况。还有人呼吁对引入的错误的性质和严重性进行更详细的检查。

**标签**: `#AI in Software Development`, `#rsync`, `#Code Quality`, `#Community Discussion`

---

<a id="item-9"></a>
## [Ladybird 浏览器不再接受公共拉取请求](https://simonwillison.net/2026/Jun/5/andreas-kling/#atom-everything) ⭐️ 7.0/10

Ladybird 浏览器的开发者 Andreas Kling 宣布，该项目将不再接受公共拉取请求，并强调贡献者需要对其更改负责。 这一变化反映了开发过程的转变，强调了在开源项目和人工智能伦理中责任和信任的重要性。 该决定基于这样的观察：大量的补丁不再意味着大量的努力，引入更改的人必须是决定这些更改是否属于项目并对其后果负责的人。

rss · Simon Willison · Jun 5, 11:10

**背景**: Ladybird 是一个由非营利组织 Ladybird 浏览器倡议开发的开源网络浏览器。它采用 BSD 2 条款许可证，并通过捐赠获得资金支持。该浏览器计划于 2026 年发布 alpha 版本，2027 年发布 beta 版本，2028 年发布稳定版本。公共拉取请求是贡献者向开源项目提出更改的一种常见方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ladybird_browser">Ladybird browser</a></li>
<li><a href="https://maritvandijk.com/contributing-to-open-source-software-creating-a-pull-request/">Contributing to open source software; creating a pull request - Marit van Dijk</a></li>

</ul>
</details>

**标签**: `#ladybird`, `#ai-ethics`, `#open-source`

---

