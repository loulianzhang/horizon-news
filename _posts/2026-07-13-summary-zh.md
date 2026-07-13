---
layout: default
title: "Horizon Summary: 2026-07-13 (ZH)"
date: 2026-07-13
lang: zh
---

> From 14 items, 6 important content pieces were selected

---

1. [洛杉矶警察局终止与监控公司 Flock 的合同](#item-1) ⭐️ 8.0/10
2. [苹果的 SpeechAnalyzer API 与 Whisper 对比评测](#item-2) ⭐️ 7.0/10
3. [世嘉 CD 游戏《Silpheed》的技术分析](#item-3) ⭐️ 7.0/10
4. [新工具将 HTML 转换为可编辑的 Word 文档](#item-4) ⭐️ 7.0/10
5. [Simon Willison 讨论直接责任人和大语言模型代理](#item-5) ⭐️ 7.0/10
6. [Anthropic 延长 Claude Max 计划中的 Fable 5 可用性](#item-6) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [洛杉矶警察局终止与监控公司 Flock 的合同](https://techcrunch.com/2026/07/13/lapd-lets-contract-with-surveillance-giant-flock-expire-citing-serious-concerns-over-civil-liberties-and-privacy/) ⭐️ 8.0/10

由于对公民自由和隐私的严重担忧，洛杉矶警察局决定不再续签与监控公司 Flock 的合同。 这一决定凸显了执法部门使用监控技术与公众对隐私和公民自由的担忧之间的日益紧张的关系。 Flock 提供自动车牌识别（ALPR）、视频监控和枪声定位系统。洛杉矶警察局的这一决定可能会影响其他执法机构重新考虑他们对类似技术的使用。

hackernews · forks · Jul 13, 15:11 · [社区讨论](https://news.ycombinator.com/item?id=48893947)

**背景**: Flock Safety 是一家美国的安全硬件和软件制造商及运营商，以其自动车牌识别和视频监控系统而闻名。这些技术被执法部门用于跟踪和监控车辆和活动，但它们引发了重大的伦理和隐私问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.flocksafety.com/">Flock Safety</a></li>
<li><a href="https://www.aclu.org/news/privacy-technology/flock-roundup">Flock’s Aggressive Expansions Go Far Beyond Simple Driver Surveillance | American Civil Liberties Union</a></li>

</ul>
</details>

**社区讨论**: 社区成员对这一决定表达了复杂的情绪，一些人强调数据可能被滥用的问题，另一些人则讨论了监控在预防犯罪方面的益处。还有人呼吁对政府购买其无法合法收集的数据进行更严格的监管。

**标签**: `#surveillance`, `#privacy`, `#civil-liberties`, `#law-enforcement`, `#technology-ethics`

---

<a id="item-2"></a>
## [苹果的 SpeechAnalyzer API 与 Whisper 对比评测](https://get-inscribe.com/blog/apple-speech-api-benchmark.html) ⭐️ 7.0/10

苹果的新 SpeechAnalyzer API 与 Whisper 语音转文字模型以及其他现有模型进行了对比评测，突出了其性能和可用性。 这次对比评测为苹果新 API 的能力提供了有价值的见解，可能会影响开发人员在语音转文字应用中的选择，并可能影响第三方转录工具的市场。 对比结果显示，SpeechAnalyzer 比 Whisper-Large-V2 更快，准确性稍差，非常适合实时转录。然而，一些社区成员建议，Nvidia 的 Nemotron 和 Parakeet，以及 Mistral 的 Voxtral 和 Cohere Transcribe 等更先进的模型可能是更好的对比基准。

hackernews · get-inscribe · Jul 13, 16:06 · [社区讨论](https://news.ycombinator.com/item?id=48894752)

**背景**: SpeechAnalyzer 是 iOS 26 中引入的一个新类，旨在提高性能、灵活性并支持完全离线操作。它提供了一个模块化且并发友好的 API，适用于从听写到自定义模型管理的所有功能。另一方面，Whisper 是由 OpenAI 创建的语音识别和转录机器学习模型，于 2022 年 9 月首次作为开源软件发布。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.apple.com/documentation/speech/speechanalyzer">SpeechAnalyzer | Apple Developer Documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Whisper_(speech_recognition_system)">Whisper ( speech recognition system) - Wikipedia</a></li>
<li><a href="https://openai.com/index/whisper/">Introducing Whisper | OpenAI</a></li>

</ul>
</details>

**社区讨论**: 社区成员意见不一，一些人认为 Nvidia 的 Nemotron 和 Parakeet，以及 Mistral 的 Voxtral 和 Cohere Transcribe 等更新的模型更适合进行对比评测。其他人则强调这可能会对那些基于 Whisper 的付费应用程序产生影响，并指出苹果有可能开发一个 macOS 原生 GUI 来替代这些封装工具。

**标签**: `#speech-to-text`, `#API`, `#benchmark`, `#Apple`, `#Whisper`

---

<a id="item-3"></a>
## [世嘉 CD 游戏《Silpheed》的技术分析](https://fabiensanglard.net/silpheed/index.html) ⭐️ 7.0/10

对世嘉 CD 游戏《Silpheed》进行了详细的技术分析，探讨了其创新地使用全动态视频（FMV）和类似多边形的视觉效果来创造独特的游戏体验。 这项分析提供了对复古游戏开发中使用的创新技术的见解，突显了开发者如何突破硬件限制来创造沉浸式体验。 该游戏使用预先录制的视频文件和巧妙的视觉技巧来模拟多边形图形，在一个 3D 能力有限的系统上创造出 3D 环境的错觉。

hackernews · ibobev · Jul 13, 14:52 · [社区讨论](https://news.ycombinator.com/item?id=48893639)

**背景**: 全动态视频（FMV）是一种使用预先录制的视频文件在游戏中显示动作的技术。在 20 世纪 90 年代初，FMV 是为游戏添加电影元素的一种流行方式，但通常会导致体验不连贯。世嘉 CD 是世嘉 Genesis 的一个附加设备，是最早支持 CD-ROM 的游戏机之一，允许制作更复杂且视觉效果更丰富的游戏。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Full-motion_video">Full-motion video - Wikipedia</a></li>
<li><a href="https://medium.com/@stojanovicsrdjan27/the-evolution-of-retro-gaming-from-pixels-to-polygons-60250e78b4c0">The Evolution of Retro Gaming: From Pixels to Polygons | by Gamerzila | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区成员赞扬了游戏中创新地使用全动态视频（FMV）和类似多边形的视觉效果，一些人指出它提供了独特的体验。然而，也有人评论说游戏的实际玩法并不好，一位用户甚至将其描述为“真的糟糕”。

**标签**: `#retro-gaming`, `#game-development`, `#technical-analysis`

---

<a id="item-4"></a>
## [新工具将 HTML 转换为可编辑的 Word 文档](https://github.com/floodtide/dom-docx) ⭐️ 7.0/10

一个新的开源工具 DOM-docx 允许开发者将 HTML 转换为原生、可编辑的 Word 文档，从而改进了文档生成过程。 该工具解决了后端文档生成中的一个常见痛点，提供了一种更直观和高效的方式来创建和更新 Word 文档，可以显著提高开发者的生产力。 DOM-docx 是用 TypeScript 编写的，这增加了类型安全性和更好的工具支持。它还包括一个截图到 docx 的评分循环来验证布局保真度，使其在从 HTML 生成报告时非常有用。

hackernews · fishbone · Jul 13, 11:51 · [社区讨论](https://news.ycombinator.com/item?id=48891267)

**背景**: HTML（超文本标记语言）是用于创建网页的标准标记语言，而 DOCX 是 Microsoft Word 使用的文件格式。将 HTML 转换为 DOCX 通常涉及将 HTML 文档的结构和内容翻译成可以在 Word 中打开和编辑的格式。现有的工具往往难以保持原始的格式和结构，导致结果不尽如人意。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dom-docx.com/">dom-docx — HTML to Word converter in the browser</a></li>
<li><a href="https://github.com/floodtide/dom-docx">GitHub - floodtide/dom-docx: Convert semantic HTML fragments to native, editable Word documents (OOXML) · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区讨论是积极的，突出了该工具的实际应用和独特功能，比如用 TypeScript 编写。用户赞赏能够直接从 HTML 生成可编辑的 Word 文档，有些人表示有兴趣将其用于特定任务，如生成简历。

**标签**: `#document-generation`, `#html-to-docx`, `#open-source`, `#typescript`

---

<a id="item-5"></a>
## [Simon Willison 讨论直接责任人和大语言模型代理](https://simonwillison.net/2026/Jul/12/directly-responsible-individuals/#atom-everything) ⭐️ 7.0/10

Simon Willison 探讨了直接责任人（DRI）的概念，并认为由于人类独有的承担责任的能力，大语言模型代理不应被视为 DRI。 这一讨论很重要，因为它强调了在组织管理中人类责任的重要性，尤其是在人工智能和大语言模型代理在工作场所变得越来越普遍的情况下。 DRI 这个术语起源于苹果公司，用于描述对特定项目、倡议或活动最终负责的人。Simon Willison 还引用了 IBM 1979 年的培训幻灯片，指出“计算机永远不能被追究责任，因此计算机永远不能做出管理决策。”

rss · Simon Willison · Jul 12, 23:57

**背景**: 直接责任人（DRI）是组织管理中使用的一个概念，以确保对特定结果有明确的责任归属。这个术语由苹果公司推广，现在以多种形式广泛使用。大语言模型（LLM）代理是能够执行复杂任务并与人类自然互动的人工智能系统，但它们缺乏对其行为真正负责的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dbmteam.com/insights/directly-responsible-individual-dri/">Directly Responsible Individual (DRI) | D. Brown Management</a></li>
<li><a href="https://tettra.com/article/directly-responsible-individuals-guide/">Directly Responsible Individuals: The What, How and Why of DRIs - Tettra</a></li>
<li><a href="https://arxiv.org/abs/2505.16120">[2505.16120] LLM-Powered AI Agent Systems and Their Applications in Industry</a></li>

</ul>
</details>

**标签**: `#AI Ethics`, `#Organizational Management`, `#Accountability`, `#LLM Agents`

---

<a id="item-6"></a>
## [Anthropic 延长 Claude Max 计划中的 Fable 5 可用性](https://simonwillison.net/2026/Jul/12/bump/#atom-everything) ⭐️ 6.0/10

Anthropic 将 Fable 5 模型在 Claude Max 计划中的可用性延长至 2026 年 7 月 19 日，为用户提供了更多灵活性。 这一延期使用户可以继续使用在前沿物理研究方面特别强大的 Fable 5 模型，并帮助 Anthropic 更好地了解需求和计算资源的可用性。 用户可以在每周使用限额中最多使用一半用于 Fable 5，之后可以通过使用积分继续使用 Fable 5，或者切换到其他模型。

rss · Simon Willison · Jul 12, 21:20

**背景**: Claude 是由 Anthropic 开发的人工智能助手，提供包括免费、专业、Max、团队和企业在内的不同计划。Fable 5 模型以其在推理和研究任务中的高效性而闻名，尤其是在物理学领域。竞争对手 OpenAI 也对其 GPT-5.6 Sol 模型进行了更新，包括取消使用限制和提高效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://claude.com/pricing">Plans & Pricing | Claude by Anthropic</a></li>
<li><a href="https://freeacademy.ai/blog/claude-free-vs-pro-vs-max-comparison-2026">Claude Pro vs Max vs Free (2026): Usage Limits Compared</a></li>

</ul>
</details>

**标签**: `#AI`, `#Anthropic`, `#Claude`

---