# Horizon 每日速递 - 2026-08-04

> From 14 items, 7 important content pieces were selected

---

1. [Keyv 及其他 npm 包受到 Shai-Hulud 供应链攻击](#item-1) ⭐️ 8.0/10
2. [用于生成多样化肤色的新算法和色彩空间](#item-2) ⭐️ 7.0/10
3. [DeepSeek V4 Flash 在单个 AMD MI300X 上运行](#item-3) ⭐️ 7.0/10
4. [苹果称更多前员工可能将机密数据带到了 OpenAI](#item-4) ⭐️ 7.0/10
5. [Xbox 停机导致无法玩光盘游戏](#item-5) ⭐️ 7.0/10
6. [MiniMax-H3 全模态系统移植到 MLX 以支持苹果芯片](#item-6) ⭐️ 7.0/10
7. [Niklas Gruhn 提出“肉代理”一词](#item-7) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Keyv 及其他 npm 包受到 Shai-Hulud 供应链攻击](https://www.aikido.dev/blog/keyv-and-friends-compromised-in-npm-supply-chain-attack) ⭐️ 8.0/10

Shai-Hulud 供应链攻击影响了多个 npm 包，包括 Keyv，导致了一份详细的报告和社区响应。 这次攻击凸显了 npm 生态系统及其更广泛的软件供应链的脆弱性，影响了依赖这些包的开发者和用户。 攻击涉及一个自我复制的蠕虫，通过 GitHub 仓库传播，影响了超过 25,000 个仓库并暴露了机密信息。预安装和后安装钩子被用作攻击载体。

hackernews · cimi_ · Aug 4, 11:01 · [社区讨论](https://news.ycombinator.com/item?id=49166874)

**背景**: npm 是 JavaScript 的包管理器，在网页开发中广泛使用。Keyv 是一个支持多种后端的简单键值存储库。供应链攻击针对软件依赖项的完整性，通常通过向受信任的包中注入恶意代码来实现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/security/blog/2025/12/09/shai-hulud-2-0-guidance-for-detecting-investigating-and-defending-against-the-supply-chain-attack/">Shai-Hulud 2.0: Guidance for detecting, investigating, and ...</a></li>
<li><a href="https://unit42.paloaltonetworks.com/npm-supply-chain-attack/">"Shai-Hulud" Worm Compromises npm Ecosystem in Supply Chain ...</a></li>
<li><a href="https://www.wiz.io/blog/shai-hulud-2-0-ongoing-supply-chain-attack">Shai-Hulud 2.0 Supply Chain Attack: 25K+ Repos Exposing Secrets</a></li>

</ul>
</details>

**社区讨论**: 社区成员建议对预安装和后安装钩子进行更严格的控制，并建议为 npm 包设置最小发布年龄。还有人呼吁采取更强大的安全措施并让执法部门介入。

**标签**: `#security`, `#npm`, `#supply-chain-attack`, `#software-engineering`

---

<a id="item-2"></a>
## [用于生成多样化肤色的新算法和色彩空间](https://toneyalexander.github.io/inclusive-color-space/) ⭐️ 7.0/10

作者开发了一种色彩空间和算法，用于生成多样且合理的肤色，并提供了一个颜色选择器和程序生成工具。 这个工具对于需要创建真实且包容的肤色的数字艺术家和游戏开发者来说非常重要，可以增强他们项目中的多样性和真实性。 尽管方法仍在不断完善中，但该工具提供了一种实用的方法来生成肤色。该项目包括一个颜色选择器和程序生成算法，并有进一步改进的空间。

hackernews · automatoney · Aug 4, 15:16 · [社区讨论](https://news.ycombinator.com/item?id=49170165)

**背景**: 色彩空间用于在数字媒体中定义和表示颜色。Fitzpatrick 量表是一种常见的人类肤色数值分类方案，但它并不能涵盖所有肤色范围。程序生成算法可以通过算法生成数据，这对于生成多样且真实的内容非常有用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Fitzpatrick_scale">Fitzpatrick scale - Wikipedia</a></li>
<li><a href="https://coloruxlab.com/colors/skin-tones">20+ Real Skin Tone Color Palettes: HEX, RGB & HTML Codes</a></li>
<li><a href="https://toneyalexander.github.io/inclusive-color-space/">What Colors Are We? Constructing A Color Space For Skin Tones</a></li>

</ul>
</details>

**社区讨论**: 社区成员赞赏了这项工作，指出其实用性和研究投入。一些人建议考虑现有的标准，如 Pantone 肤色和光照对肤色的影响。其他人则称赞了创新的方法和工具的展示。

**标签**: `#digital-art`, `#game-development`, `#color-theory`, `#algorithm`

---

<a id="item-3"></a>
## [DeepSeek V4 Flash 在单个 AMD MI300X 上运行](https://github.com/ryanzhou/deepseek-v4-flash-mi300x) ⭐️ 7.0/10

一个项目成功展示了在单个 AMD MI300X 上运行 DeepSeek V4 Flash，这是一个 284B 的专家混合模型，展示了该硬件在大型模型推理方面的潜力。 这一成就突显了 AMD MI300X 处理大规模 AI 模型的能力，可能使高性能计算对研究人员和开发人员来说更加可及且成本更低。 DeepSeek V4 Flash 模型具有 13B 活跃参数和 1M 令牌上下文窗口，在提供 192 GB HBM3 内存和 5.3 TB/s 峰值理论内存带宽的 AMD MI300X 上运行。

hackernews · zhoutong · Aug 4, 10:00 · [社区讨论](https://news.ycombinator.com/item?id=49166386)

**背景**: DeepSeek V4 Flash 是一个 284B 的专家混合模型，设计用于编码、工具使用和代理工作流。AMD MI300X 是一款高性能 GPU，专为生成式 AI 工作负载和高性能计算应用设计，与竞争对手相比，在 AI 和 HPC 性能方面有显著提升。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://lmstudio.ai/models/deepseek-v4-flash">DeepSeek V4 Flash - lmstudio.ai</a></li>
<li><a href="https://www.amd.com/en/products/accelerators/instinct/mi300/mi300x.html">AMD Instinct™ MI300X Accelerators</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了 AMD MI300X 的可用性和实用性，指出它通常作为更大系统的一部分出售。他们还提到了其他项目如 DwarfStar 以及在不同硬件配置上运行大型模型所涉及的权衡。

**标签**: `#AI`, `#Hardware`, `#Inference`, `#AMD`, `#DeepSeek`

---

<a id="item-4"></a>
## [苹果称更多前员工可能将机密数据带到了 OpenAI](https://techcrunch.com/2026/08/04/apple-says-more-ex-employees-may-have-taken-confidential-data-to-openai/) ⭐️ 7.0/10

苹果公司声称，更多的前员工可能将机密数据带到了 OpenAI，引发了关于知识产权和企业间谍活动的担忧。 这个问题突显了主要科技公司在知识产权方面的紧张关系以及企业间谍活动的可能性，这可能会影响科技行业的竞争格局和法律框架。 这些指控涉及截取文档屏幕截图，而不仅仅是知识的转移。此案可能导致苹果和 OpenAI 面临重大的法律和财务后果。

hackernews · thewebguyd · Aug 4, 15:37 · [社区讨论](https://news.ycombinator.com/item?id=49170479)

**背景**: 在科技行业中，知识产权和企业间谍活动是关键问题，因为公司会大量投资于研发。员工在公司之间的流动，尤其是那些掌握敏感信息的员工，可能会导致关于专有数据的所有权和使用的争议。

**社区讨论**: 社区评论显示了各种观点，从对苹果策略的批评到对 OpenAI 硬件项目的怀疑。一些评论者强调了指控的严重性，而另一些人则指出了涉事方安全实践中的讽刺之处。

**标签**: `#Apple`, `#OpenAI`, `#Intellectual Property`, `#Corporate Espionage`, `#Tech Industry`

---

<a id="item-5"></a>
## [Xbox 停机导致无法玩光盘游戏](https://birchtree.me/blog/xbox-goes-down-you-cant-play-games-you-own-on-disc/) ⭐️ 7.0/10

Xbox 停机导致用户无法玩光盘游戏，突显了即使对于光盘游戏也依赖在线服务的问题。 这一事件突显了游戏行业中对数字所有权和在线服务可靠性的日益增长的担忧，影响了玩家访问其购买内容的能力。 停机期间，用户需要登录微软服务器才能进行离线游戏，一些用户还遇到了低分辨率和强制创建账户的问题。

hackernews · surprisetalk · Aug 4, 12:01 · [社区讨论](https://news.ycombinator.com/item?id=49167448)

**背景**: 游戏中的数字所有权指的是消费者对其购买的游戏所拥有的权利和访问权限。虽然光盘曾经是一种可靠的拥有形式，但现代游戏机通常需要在线验证，这在服务器停机时会导致问题。这种向数字和在线要求的转变引发了关于真正所有权和游戏长期可访问性的争论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dataconomy.com/2025/08/28/digital-ownership-in-gaming-what-you-actually-own/">Digital Ownership In Gaming: What You Actually ‘own’ - Dataconomy</a></li>
<li><a href="https://www.midiaresearch.com/blog/online-game-ownership-in-the-digital-age-do-we-really-own-what-we-play">Online game ownership in the digital age – do we really own what we play?</a></li>

</ul>
</details>

**社区讨论**: 社区成员表达了对即使使用实体媒介也需要在线服务的不满，并讨论了这对数字所有权和游戏未来的影响。一些人强调了能够离线玩游戏的重要性以及随着时间推移可能失去对游戏的访问权的问题。

**标签**: `#gaming`, `#digital-ownership`, `#consumer-rights`, `#online-services`

---

<a id="item-6"></a>
## [MiniMax-H3 全模态系统移植到 MLX 以支持苹果芯片](https://simonwillison.net/2026/Aug/4/minimax-h3-mlx/#atom-everything) ⭐️ 7.0/10

MiniMax-H3 全模态生成系统，可以从多种输入生成长达 15 秒的带音频的视频片段，现在已被移植到 MLX 上，可以在苹果芯片上运行。 这一进展使得使用苹果芯片设备（如 M5 Max MacBook Pro）的用户能够在本地利用强大的生成式 AI 模型，增强了高级 AI 应用的可访问性和实用性。 该软件包需要下载约 115 GB 的模型文件，生成一个视频大约需要 45 分钟。生成的视频质量令人印象深刻，但音频需要额外的提示指导才能获得更好的效果。

rss · Simon Willison · Aug 4, 19:10

**背景**: MiniMax-H3 是一个通用的全模态生成系统，可以处理和生成文本、图像、音频和视频内容。MLX 是一个针对苹果芯片统一内存架构优化的数组框架，旨在支持高效的机器学习和数值计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.minimax.io/blog/minimax-h3">MiniMax H3: An Open Model Breaking the Boundaries Between Tasks and Modalities - MiniMax Research | MiniMax</a></li>
<li><a href="https://huggingface.co/MiniMaxAI/MiniMax-H3">MiniMaxAI/MiniMax-H3 · Hugging Face</a></li>
<li><a href="https://github.com/ml-explore/mlx">GitHub - ml-explore/mlx: MLX: An array framework for Apple ... Exploring LLMs with MLX and the Neural Accelerators in the M5 ... MLX Get started with MLX for Apple silicon - WWDC25 - Videos ... Apple Silicon LLMs: Run AI Models on Mac (MLX, 2026) MLX: Apple Silicon ML Framework - emergentmind.com</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Apple Silicon`, `#Generative Models`, `#Python`

---

<a id="item-7"></a>
## [Niklas Gruhn 提出“肉代理”一词](https://simonwillison.net/2026/Aug/3/dont-be-a-meat-proxy/#atom-everything) ⭐️ 7.0/10

Niklas Gruhn 提出了“肉代理”一词，用来描述那些盲目复制和粘贴 AI 生成的内容而不进行批判性评估的人，强调了理解和验证 AI 输出的重要性。 这一术语突显了在使用 AI 时的一个重要问题，即在与 AI 生成的内容互动时需要人类的监督和批判性思维，尤其是在 AI 越来越多地融入日常任务的情况下。 Gruhn 建议人们应该阅读、理解、验证，然后用自己的话写回复，通过这种方式增加价值。这种方法确保 AI 输出不仅被传递，还经过了批判性评估。

rss · Simon Willison · Aug 3, 23:45

**背景**: 随着生成式 AI 的普及，不加批判地接受 AI 生成内容的风险也在增加。交叉验证、保留验证和使用适当的指标等技术通常用于确保 AI 模型的性能和可靠性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Aug/3/dont-be-a-meat-proxy/">Don’t be a meat proxy</a></li>
<li><a href="https://www.biggestgoal.ai/l/workslop">Workslop and Meat Proxy: What They Mean and How to Stop Them · Biggest Goal</a></li>
<li><a href="https://elsolitario.org/en/2026/08/03/meat-proxy-ai-code-review-without-reading/">Meat Proxy: The Risk of Forwarding AI Answers Unread</a></li>

</ul>
</details>

**标签**: `#ai`, `#generative-ai`, `#ai-misuse`, `#definitions`

---

