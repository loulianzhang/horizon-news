# Horizon 每日速递 - 2026-07-18

> From 10 items, 5 important content pieces were selected

---

1. [GPT-5.6 解决长期存在的凸优化问题](#item-1) ⭐️ 8.0/10
2. [LG 显示器通过 Windows 更新静默安装软件](#item-2) ⭐️ 8.0/10
3. [Fable 5 与 GPT-5.6 Sol 在 NP 难问题上的比较](#item-3) ⭐️ 7.0/10
4. [图表显示 AI 对 Stack Overflow 活动的影响](#item-4) ⭐️ 7.0/10
5. [Anthropic 将 Claude Fable 5 永久纳入高级计划](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [GPT-5.6 解决长期存在的凸优化问题](https://old.reddit.com/r/math/comments/1uxj3cy/after_openais_cdc_proof_announcement_gpt56_used_a/) ⭐️ 8.0/10

GPT-5.6 使用提示解决了凸优化领域中的一个长期存在的问题，为某些类型函数的时间复杂度理解做出了贡献。 这一突破展示了 AI 在推进数学研究方面的潜力，并可能导致在机器学习和运筹学等应用中更高效的算法。 GPT-5.6 解决的问题涉及球形域上的凸、Lipschitz 函数，并提供了求解此类优化问题的时间复杂度的上限。

hackernews · mbustamanter · Jul 18, 13:00 · [社区讨论](https://news.ycombinator.com/item?id=48957779)

**背景**: 凸优化是数学优化的一个子领域，研究在凸集上最小化凸函数的问题。许多凸优化问题类可以使用多项式时间算法解决，这使得它们在实际应用中非常有价值。时间复杂度是衡量解决问题所需的计算资源的一种度量，理解它对于开发高效算法至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Convex_optimization">Convex optimization - Wikipedia</a></li>
<li><a href="https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf">PDF Convex Optimization - Stanford University</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了这一贡献的重要性，指出虽然这个问题比较小众，但它确实代表了一个真正的进步。还讨论了 AI 在未来数学研究中的作用以及对研究人员培训和工作的影响。

**标签**: `#AI`, `#Convex Optimization`, `#Mathematics`, `#Research`

---

<a id="item-2"></a>
## [LG 显示器通过 Windows 更新静默安装软件](https://videocardz.com/newz/lg-monitors-silently-install-software-through-windows-update-without-user-consent) ⭐️ 8.0/10

LG 显示器通过 Windows 更新静默安装软件，未征得用户同意，引发了严重的安全和隐私问题。 这个问题凸显了对用户信任的严重违反，可能会使用户暴露于恶意软件，影响系统的安全性和隐私。 一旦通过 HDMI 连接 LG 显示器，该软件就会被安装，并且它具有完全的系统访问权限，没有沙箱隔离。每次系统启动时都会运行，并且即使用户已经拥有旧款 LG 显示器，该软件也会被安装。

hackernews · baranul · Jul 18, 10:21 · [社区讨论](https://news.ycombinator.com/item?id=48956688)

**背景**: Windows 更新是微软提供的一项服务，可以自动下载并安装 Windows 操作系统的更新。通常，这些更新包括安全补丁、驱动程序更新和其他重要更新。然而，在这种情况下，LG 的软件在未经用户同意的情况下被安装，这是不寻常且令人担忧的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/troubleshoot/windows-client/installing-updates-features-roles/command-line-switches-deploy-update-packages">Command-line switches for Microsoft software update packages</a></li>
<li><a href="https://www.lg.com/us/support/help-library/lg-monitor-onscreen-control-how-to-update-monitor-software--20154629827481">[LG Monitor OnScreen Control] How to Update Monitor Software ...</a></li>

</ul>
</details>

**社区讨论**: 社区成员对安全影响表达了强烈的担忧，并提出了一些解决方法，例如使用 gpedit.msc 或 sysdm.cpl 来阻止制造商应用程序的自动下载。一些人还指出，责任在于微软，因为他们控制着 Windows 更新过程。

**标签**: `#security`, `#privacy`, `#hardware`, `#windows`, `#lg`

---

<a id="item-3"></a>
## [Fable 5 与 GPT-5.6 Sol 在 NP 难问题上的比较](https://charlesazam.com/blog/fable-5-gpt-5-6-sol-goal/) ⭐️ 7.0/10

对 Fable 5 和 GPT-5.6 Sol 在 NP 难问题上的表现进行了详细比较，重点探讨了/goal 指令的有效性。 这一比较提供了每个 AI 模型在解决复杂问题方面的优缺点的见解，这对于从事高级 AI 应用开发的研究人员和开发者来说至关重要。 评估包括一个图表，显示两个模型的表现，y 轴是倒置的，表示数值越低越好。/goal 指令在单轨调查或小规模分散/收集任务中似乎更有效。

hackernews · couAUIA · Jul 18, 11:00 · [社区讨论](https://news.ycombinator.com/item?id=48956879)

**背景**: Fable 5 是 Anthropic 公司 Claude 平台的一部分，旨在为构建 AI 解决方案的开发者提供支持。GPT-5.6 Sol 由 OpenAI 开发，被描述为其迄今为止最好的编码模型，适用于复杂的推理和编码任务。/goal 指令是一种用于引导 AI 注意力并提高其在特定任务上表现的功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/introducing-claude-fable-5-and-claude-mythos-5">Introducing Claude Fable 5 and Claude Mythos 5 - Claude Platform Docs</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT‑5.6 Sol: a next-generation model - OpenAI</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了/goal 指令的有效性，并建议进行额外的评估，例如使用超模式进行并行调查。还有关于图表清晰度以及在实际应用中不同 AI 模型体验的评论。

**标签**: `#AI`, `#NLP`, `#Benchmarking`, `#Problem-Solving`

---

<a id="item-4"></a>
## [图表显示 AI 对 Stack Overflow 活动的影响](https://data.stackexchange.com/stackoverflow/query/1953768#graph) ⭐️ 7.0/10

Hacker News 上的一张图表和讨论分析了 AI 和其他因素对 Stack Overflow 活动随时间变化的影响，显示在 ChatGPT 发布之前活动量有所下降。 这项分析提供了技术进步和社区动态如何影响最受欢迎的编程问答平台之一的见解，突显了在线社区和知识共享的更广泛影响。 图表显示 2014 年活动达到峰值，随后下降。社区评论认为，高参与门槛和缺乏强大的社区可能是导致这一趋势的因素。

hackernews · secretslol · Jul 18, 11:12 · [社区讨论](https://news.ycombinator.com/item?id=48956949)

**背景**: Stack Overflow 是一个广泛使用的编程问答平台。多年来，该平台经历了重大变化，包括 2021 年被 Prosus 收购以及像 ChatGPT 这样的 AI 工具的日益使用。

**社区讨论**: 社区成员讨论了导致活动下降的各种因素，包括高参与门槛、缺乏强大社区以及平台收购的影响。一些人还指出，现代项目中更好的文档和问题跟踪器可能减少了对 Stack Overflow 的需求。

**标签**: `#AI`, `#StackOverflow`, `#CommunityAnalysis`, `#DataVisualization`

---

<a id="item-5"></a>
## [Anthropic 将 Claude Fable 5 永久纳入高级计划](https://simonwillison.net/2026/Jul/18/claude-make-fable-5-permanent/#atom-everything) ⭐️ 7.0/10

从 7 月 20 日开始，Anthropic 将在所有 Max 和 Team Premium 计划中以 50%的限制包含 Claude Fable 5。Pro 和 Team Standard 用户将获得一次性 100 美元的信用额度。 这一变化反映了来自其他 AI 模型如 GPT-5.6 Sol 和 Kimi 3 的竞争压力，并确保 Anthropic 的最佳模型对高级订阅用户保持可访问性，从而提升其价值主张。 每月 20 美元计划的用户仍然无法访问 Claude Fable 5。这一决定是出于对计算能力的担忧，可能会影响未来的训练工作。

rss · Simon Willison · Jul 18, 06:00

**背景**: Claude Fable 5 是由 Anthropic 开发的一个大型语言模型，以其在编码和复杂任务中的先进能力而闻名。最初计划将其从订阅计划中移除，仅通过 API 定价提供，但由于 GPT-5.6 Sol 和 Kimi 3 等其他模型的竞争，导致了这一变化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT‑5.6 Sol: a next-generation model - OpenAI</a></li>

</ul>
</details>

**标签**: `#AI`, `#Pricing`, `#Claude`, `#Anthropic`, `#Competitive Landscape`

---

