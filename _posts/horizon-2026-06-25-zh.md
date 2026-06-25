# Horizon 每日速递 - 2026-06-25

> From 15 items, 7 important content pieces were selected

---

1. [研究人员使用 AI 和成像技术读取整卷赫库兰尼姆古卷](#item-1) ⭐️ 9.0/10
2. [IBM 推出亚 1 纳米芯片技术](#item-2) ⭐️ 8.0/10
3. [Zig 改进 bitCast 和 LLVM 后端](#item-3) ⭐️ 8.0/10
4. [Mac OS 9 新应用 OS9Map](#item-4) ⭐️ 7.0/10
5. [《半条命 2》现在可以在浏览器中游玩](#item-5) ⭐️ 7.0/10
6. [Hacker News 的谷歌趋势工具追踪了 18 年的评论](#item-6) ⭐️ 7.0/10
7. [Simon Willison 将 MDN 浏览器兼容性数据转换为 SQLite 数据库](#item-7) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [研究人员使用 AI 和成像技术读取整卷赫库兰尼姆古卷](https://scrollprize.org/firstscroll) ⭐️ 9.0/10

研究人员首次使用先进的成像和人工智能技术成功读取了一整卷赫库兰尼姆古卷，为历史和考古研究开辟了新的可能性。 这一突破使历史学家和考古学家能够访问和分析以前无法阅读的古代文本，可能揭示过去的新见解，并增强我们对历史背景的理解。 研究人员结合使用了先进的成像技术和人工智能算法来检测和重建古卷上的文字。该项目是维苏威挑战赛的一部分，该挑战赛提供 100 万美元的奖金以激励这项技术的进一步发展。

hackernews · verditelabs · Jun 25, 15:48 · [社区讨论](https://news.ycombinator.com/item?id=48675179)

**背景**: 赫库兰尼姆古卷是公元 79 年维苏威火山爆发时被埋葬并碳化的古罗马文献。这些古卷非常脆弱，展开时容易造成损坏。为了在不物理展开的情况下阅读这些文本，已经开发了诸如 X 射线计算机断层扫描（CT）和机器学习等先进成像技术。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nationalgeographic.com/premium/article/herculaneum-scrolls-vesuvius-challenge-seales">AI just deciphered part of the Herculaneum Scrolls | National Geographic</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1296207424001377">Advanced imaging to recover illegible text in historic ...</a></li>

</ul>
</details>

**社区讨论**: 社区对此技术的潜力表现出高度的热情和兴奋。一些成员表达了找到更多古卷甚至整个图书馆的希望，而其他人则赞赏人工智能对历史研究和技术领域的积极影响。

**标签**: `#AI`, `#Archaeology`, `#Historical Research`, `#Imaging Technology`

---

<a id="item-2"></a>
## [IBM 推出亚 1 纳米芯片技术](https://newsroom.ibm.com/2026-06-25-ibm-debuts-worlds-first-sub-1-nanometer-chip-technology) ⭐️ 8.0/10

IBM 宣布推出世界上首个亚 1 纳米芯片技术，该技术采用革命性的 0.7 纳米（或 7 埃）节点晶体管架构。 这一突破标志着半导体制造领域的重要进展，有望使晶体管密度翻倍，并实现更强大和高效的芯片。 这种新芯片可以在指甲大小的芯片上集成近 1000 亿个晶体管，几乎是 IBM 上一代芯片技术密度的两倍。

hackernews · porridgeraisin · Jun 25, 15:33 · [社区讨论](https://news.ycombinator.com/item?id=48674967)

**背景**: 半导体器件制造是一个复杂的过程，涉及光刻、薄膜沉积和蚀刻等多个步骤，在晶圆上创建电子电路。业界一直在推动小型化的极限，每个新的节点代表更小的物理尺寸和更高的晶体管密度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://newsroom.ibm.com/2026-06-25-ibm-debuts-worlds-first-sub-1-nanometer-chip-technology">IBM Debuts World’s First Sub-1 Nanometer Chip Technology</a></li>
<li><a href="https://arstechnica.com/gadgets/2026/06/ibm-claims-worlds-first-sub-1-nanometer-chip-technology/">IBM claims world’s first sub-1 nanometer chip technology - Ars Technica</a></li>
<li><a href="https://research.ibm.com/blog/sub-1nm-node-chips">IBM introduces the smallest computer chip in the world - IBM Research</a></li>

</ul>
</details>

**社区讨论**: 一些社区成员对“亚 1 纳米”的确切含义表示怀疑，并指出这里的“纳米”指的是制造技术的一代，而不是确切的物理尺寸。还有人担心 IBM 过去经常做出大胆声明的历史，以及其对“亚 1 纳米”定义的不明确。

**标签**: `#semiconductor`, `#chip-technology`, `#IBM`, `#nanotechnology`

---

<a id="item-3"></a>
## [Zig 改进 bitCast 和 LLVM 后端](https://ziglang.org/devlog/2026/#2026-06-25) ⭐️ 8.0/10

Zig 引入了新的 bitCast 语义，并对其 LLVM 后端进行了改进，确保在不同字节序下行为一致，并增强了低级操作。 这些变化提高了低级编程的一致性和易用性，使 Zig 对于处理位打包数据和跨平台应用的开发者来说更加可靠和用户友好。 新的 bitCast 语义与字节序无关，这意味着该操作在所有目标上表现一致。LLVM 后端的改进包括对 comptime 执行和其他低级操作的更好支持。

hackernews · kouosi · Jun 25, 14:19 · [社区讨论](https://news.ycombinator.com/item?id=48673825)

**背景**: Zig 是一种通用编程语言，旨在构建健壮、优化且可重用的软件。Zig 中的@bitCast 函数用于将一种类型的位重新解释为另一种类型。LLVM 是一组模块化和可重用的编译器和工具链技术，广泛用于构建、优化和生成代码的中间表示。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ziglang.org/devlog/2026/">Devlog ⚡ Zig Programming Language</a></li>
<li><a href="https://en.wikipedia.org/wiki/LLVM">LLVM - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区讨论是积极的，用户赞赏这些变化并讨论其影响。一些用户强调了处理位打包二进制头文件的好处，而其他人则赞扬开发日志中提供的深入技术解释。

**标签**: `#zig`, `#low-level-programming`, `#llvm`, `#bit-manipulation`, `#language-features`

---

<a id="item-4"></a>
## [Mac OS 9 新应用 OS9Map](https://yllan.org/software/OS9Map/) ⭐️ 7.0/10

一款名为 OS9Map 的新应用程序已为 Mac OS 9 开发，集成了现代功能，并引起了复古计算和开发的兴趣。 这一开发突显了复古计算的持续兴趣，并展示了仍有一个活跃的社区在为旧操作系统开发软件，这可以激发进一步的创新和保护工作。 该应用程序需要 16 MB 的 RAM，建议使用 32 MB。它集成了诸如 TLS、HTTP/2 和 Unicode 支持等现代功能，使其成为经典 Mac OS 9 生态系统中的一个重要补充。

hackernews · LaSombra · Jun 25, 15:01 · [社区讨论](https://news.ycombinator.com/item?id=48674484)

**背景**: Mac OS 9 是经典 Mac OS 操作系统的第九个也是最后一个主要版本，于 1999 年 10 月 23 日发布。它在 2001 年被 Mac OS X 取代。复古计算是指当前使用旧计算机硬件和软件，通常作为一种爱好和为了保存目的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mac_OS_9">Mac OS 9</a></li>
<li><a href="https://en.wikipedia.org/wiki/Retrocomputing">Retrocomputing</a></li>

</ul>
</details>

**社区讨论**: 社区成员对该项目表示了热情，一些用户分享了他们的经验，并表达了对源代码和底层细节的兴趣。总体上，大家对这项努力表示赞赏，并希望看到更多这方面的开发。

**标签**: `#retro-computing`, `#mac-os-9`, `#software-development`, `#community-interest`

---

<a id="item-5"></a>
## [《半条命 2》现在可以在浏览器中游玩](https://hl2.slqnt.dev/) ⭐️ 7.0/10

《半条命 2》的网页版已经创建，允许玩家直接在浏览器中游玩，展示了令人印象深刻的技术能力。 这一成就展示了 WebAssembly 和 Emscripten 等网络技术的潜力，使复杂的游戏能够在各种设备和平台上运行。 这个网页版使用了 WebAssembly 和 Emscripten 来编译游戏，但渲染质量被指出低于其他可用选项，一些着色器缺失，包括角色的眼睛。

hackernews · panza · Jun 25, 06:00 · [社区讨论](https://news.ycombinator.com/item?id=48669534)

**背景**: WebAssembly（Wasm）是一种基于栈的虚拟机的二进制指令格式，设计为高级语言编译的目标。Emscripten 是一个基于 LLVM/Clang 的编译器，可以将 C 和 C++代码编译成 WebAssembly，从而在浏览器中高效执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>
<li><a href="https://en.wikipedia.org/wiki/Emscripten">Emscripten</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了其他经典游戏如《雷神之锤 3》和《虚幻竞技场》的网页版链接，并讨论了这些项目更广泛的影响，包括在各种平台上运行复杂软件的能力，甚至是在支持有限的平台上。

**标签**: `#web-technology`, `#gaming`, `#browser-ports`

---

<a id="item-6"></a>
## [Hacker News 的谷歌趋势工具追踪了 18 年的评论](https://hackernewstrends.com/) ⭐️ 7.0/10

一名用户通过索引 18 年的评论，创建了一个名为“Hacker News 的谷歌趋势”的工具，允许用户随时间跟踪特定术语的频率。 这个工具提供了对 Hacker News 上趋势和讨论的宝贵见解，帮助用户了解近二十年来话题和兴趣的变化。 该工具允许用户输入特定术语并查看其随时间的频率，但它遇到了一些技术问题，如超时和速率限制。

hackernews · ytkimirti · Jun 25, 14:08 · [社区讨论](https://news.ycombinator.com/item?id=48673671)

**背景**: Hacker News 是一个流行的技术和创业新闻网站。术语频率跟踪是数据分析中常用的技术，用于了解数据集中某些词或短语的普遍性。该项目利用这种技术提供了对讨论的历史视角。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.numberanalytics.com/blog/ultimate-guide-term-frequency-text-mining">Mastering Term Frequency in Text Mining - numberanalytics.com</a></li>
<li><a href="https://rstudio-pubs-static.s3.amazonaws.com/1173909_9501416218664790b77dc665743fba4c.html">Basic term frequency analysis in R</a></li>

</ul>
</details>

**社区讨论**: 社区成员提供了反馈、替代解决方案，并指出了潜在的问题，例如搜索数据和已发布文本之间的差异，以及超时和速率限制等技术错误。

**标签**: `#Hacker News`, `#Data Analysis`, `#Trend Tracking`, `#Web Development`

---

<a id="item-7"></a>
## [Simon Willison 将 MDN 浏览器兼容性数据转换为 SQLite 数据库](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 7.0/10

Simon Willison 创建了一个 GitHub 仓库，将 MDN 的浏览器兼容性数据转换为 SQLite 数据库，并通过 GitHub CDN 使其易于访问。 这个工具使浏览器兼容性数据更易于访问和查询，对于处理跨浏览器兼容性问题的网页开发者来说非常有价值。 该仓库包含一个使用 sqlite-utils 生成的 Python 脚本（由 Claude Code for web (Opus 4.8) 生成），以及一个 GitHub Actions 工作流，用于构建数据库并将其推送到具有开放 CORS 头的孤儿分支。

rss · Simon Willison · Jun 24, 23:59

**背景**: MDN（Mozilla 开发者网络）提供了全面的浏览器兼容性数据，这对于网页开发者确保其应用程序在不同浏览器上正常运行至关重要。新的 MDN MCP 服务旨在将这些数据直接引入编辑器或 IDE 中。SQLite 是一种轻量级的基于文件的数据库引擎，广泛用于中小型数据集。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/blog/introducing-mdn-mcp-server/">Introducing the MDN MCP server - MDN Web Docs</a></li>
<li><a href="https://github.com/simonw/sqlite-utils">GitHub - simonw/sqlite-utils: Python CLI utility and library for manipulating SQLite databases · GitHub</a></li>

</ul>
</details>

**标签**: `#browser-compatibility`, `#sqlite`, `#web-development`

---

