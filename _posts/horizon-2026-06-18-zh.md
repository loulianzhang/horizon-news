# Horizon 每日速递 - 2026-06-18

> From 14 items, 9 important content pieces were selected

---

1. [Z.ai 发布 GLM-5.2，一个 7530 亿参数的 LLM](#item-1) ⭐️ 9.0/10
2. [诺姆·沙泽尔加入 OpenAI](#item-2) ⭐️ 8.0/10
3. [发现 10,000 个 GitHub 仓库分发特洛伊木马恶意软件](#item-3) ⭐️ 8.0/10
4. [瑞士议会解除新建核电站禁令](#item-4) ⭐️ 7.0/10
5. [Ubiquiti 推出基于 ZFS 的企业级 NAS](#item-5) ⭐️ 7.0/10
6. [医院和大学以 90%更低的成本重新利用药物](#item-6) ⭐️ 7.0/10
7. [康奈尔大学推出自导式高级编译器课程](#item-7) ⭐️ 7.0/10
8. [W 社交平台的推出引发透明度和动机质疑](#item-8) ⭐️ 7.0/10
9. [Modos 彩色电子纸显示器推动显示技术进步](#item-9) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Z.ai 发布 GLM-5.2，一个 7530 亿参数的 LLM](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai 发布了 GLM-5.2，这是一个 7530 亿参数、1.51TB 的纯文本大语言模型，具有 100 万 token 的上下文窗口，并且在 MIT 许可证下开源。 这一发布意义重大，因为它为开源大语言模型设立了新的基准，在各种基准测试中超越了其他领先模型，并在 AI 社区引起了广泛关注。 GLM-5.2 使用了 40 个活动参数（专家混合），并且每项任务消耗 43k 输出 token，这比其他领先的开源权重模型要多。

rss · Simon Willison · Jun 17, 23:58

**背景**: 专家混合（MoE）是一种机器学习技术，其中多个专家网络用于将问题空间划分为同质区域。100 万 token 的上下文窗口使模型能够处理和生成更长的文本序列，使其适用于全仓库代码审查等任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/mixture-of-experts">What is mixture of experts? - IBM</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/long-context">Long context | Gemini API | Google AI for Developers</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Open Source`, `#LLM`, `#Natural Language Processing`

---

<a id="item-2"></a>
## [诺姆·沙泽尔加入 OpenAI](https://twitter.com/NoamShazeer/status/2067400851438932297) ⭐️ 8.0/10

有影响力的论文《注意力就是你所需要的》的合著者诺姆·沙泽尔离开谷歌，加入 OpenAI。 这一举动可能对人工智能研究和发展产生重大影响，因为沙泽尔在变压器模型和自然语言处理方面拥有丰富的专业知识，这些都将带到 OpenAI。 沙泽尔是谷歌的长期研究员，也是 Character.AI 的联合创始人，该公司于 2024 年被谷歌收购。在加入 OpenAI 之前，他最近被任命为谷歌 Gemini 项目的联合负责人。

hackernews · lukasgross · Jun 18, 00:26 · [社区讨论](https://news.ycombinator.com/item?id=48578913)

**背景**: 2017 年发表的《注意力就是你所需要的》论文介绍了变压器架构，这已成为深度学习和自然语言处理领域的基石。诺姆·沙泽尔在这个领域中是一个关键人物，对这些模型的发展做出了重要贡献。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Attention_Is_All_You_Need">Attention Is All You Need - Wikipedia</a></li>
<li><a href="https://www.noamshazeer.com/">Noam Shazeer | AI Scientist, Google Gemini Co-Lead</a></li>

</ul>
</details>

**社区讨论**: 社区成员正在讨论沙泽尔这一举动的意义，一些人提供了关于他的职业生涯和贡献的背景信息。也有人猜测他为什么在回到谷歌不久后就决定离开。

**标签**: `#AI`, `#Research`, `#Industry News`, `#OpenAI`, `#Google`

---

<a id="item-3"></a>
## [发现 10,000 个 GitHub 仓库分发特洛伊木马恶意软件](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 8.0/10

一名研究人员发现了 10,000 个 GitHub 仓库在分发特洛伊木马恶意软件，引发了对开源项目安全性的担忧。 这一发现突显了广泛使用的代码托管和协作平台 GitHub 上的重大安全问题，可能影响到许多开发者和用户。 这些恶意仓库通常看起来是新的，并且经常更新，主要针对自动化系统而不是人类用户。这种策略增加了通过依赖关系感染其他项目的风险。

hackernews · theorchid · Jun 18, 11:45 · [社区讨论](https://news.ycombinator.com/item?id=48583928)

**背景**: GitHub 是一个用于托管和协作软件项目的流行平台。GitHub 上的开源项目经常被用作其他项目的依赖项，这使得它们成为传播恶意软件的潜在途径。特洛伊木马是一种伪装成合法软件以获取用户系统访问权限的恶意软件。

**社区讨论**: 社区成员分享了各种轶事和经历，强调了这个问题的普遍性以及需要更好的安全措施。一些用户对 GitHub 对此问题的反应表示不满，认为该平台需要采取更多措施来解决恶意软件问题的规模。

**标签**: `#GitHub`, `#Security`, `#Malware`, `#Open-Source`

---

<a id="item-4"></a>
## [瑞士议会解除新建核电站禁令](https://www.bluewin.ch/en/news/switzerland/parliament-lifts-ban-on-new-nuclear-power-plants-3257535.html) ⭐️ 7.0/10

瑞士议会解除了新建核电站的禁令，这可能会导致该国能源格局的重大变化。 这一政策变化意义重大，因为它为瑞士提供了多元化能源来源的可能性，并可能减少对化石燃料的依赖，影响能源安全和环境目标。 该决定仍需通过全民公投，左翼和绿党对此有显著反对。预计一旦核心挑战得到解决，小型模块化反应堆（SMR）的初创市场将会增长。

hackernews · leonidasrup · Jun 18, 14:17 · [社区讨论](https://news.ycombinator.com/item?id=48585746)

**背景**: 瑞士历史上一直依赖水力发电、核能和其他可再生能源。在 2011 年福岛核事故后，瑞士实施了新建核电站的禁令，导致重点转向逐步淘汰现有的核设施。

**社区讨论**: 社区讨论中强调了关于核能的误解，一些人强调其潜在的好处，而另一些人则表达了对成本和政治反对的担忧。也有人提到需要就这一话题进行知情和文明的讨论。

**标签**: `#nuclear-power`, `#energy-policy`, `#switzerland`, `#environment`

---

<a id="item-5"></a>
## [Ubiquiti 推出基于 ZFS 的企业级 NAS](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 7.0/10

Ubiquiti 推出了基于 ZFS 的企业级 NAS 解决方案，配备了双 25 千兆 SFP28 端口和冗余电源以提高可靠性。 这一新的 NAS 解决方案非常重要，因为它利用了以数据完整性和高级功能著称的 ZFS 文件系统，使其在企业存储市场中成为一个强有力的竞争对手。 该 NAS 解决方案包括支持高速数据传输的双 25 千兆 SFP28 端口和冗余电源，以确保持续运行。其售价为 3999 美元。

hackernews · ksec · Jun 18, 14:24 · [社区讨论](https://news.ycombinator.com/item?id=48585866)

**背景**: ZFS（Zettabyte 文件系统）是一种结合了文件系统和逻辑卷管理器的技术，提供了数据压缩、去重、快照和自愈等功能。SFP28（小型可插拔 28）是一种用于 25 千兆以太网的收发器，为数据中心和其他网络环境提供高速连接。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ZFS">ZFS</a></li>
<li><a href="https://en.wikipedia.org/wiki/SFP28">SFP28</a></li>

</ul>
</details>

**社区讨论**: 社区成员普遍对 Ubiquiti 进入企业级 NAS 领域持积极态度，称赞其使用 ZFS。然而，一些人对企业环境中 Ubiquiti 的可靠性和使用机械硬盘时 ZFS 的实际性能表示担忧。

**标签**: `#Storage`, `#ZFS`, `#Enterprise Solutions`, `#Network Attached Storage`

---

<a id="item-6"></a>
## [医院和大学以 90%更低的成本重新利用药物](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 7.0/10

医院和大学正在以显著更低的成本重新利用现有药物来治疗各种疾病，这可能彻底改变医疗保健。 这种方法可以大幅降低医疗成本，并提高对各种疾病（包括罕见病和常见病）的治疗可及性。 例如，抗癌药物贝伐单抗（Avastin）被用于治疗黄斑变性，其成本仅为专门包装用于眼部注射的兰尼单抗的一小部分。

hackernews · giuliomagnifico · Jun 18, 10:33 · [社区讨论](https://news.ycombinator.com/item?id=48583386)

**背景**: 药物再利用或重新定位是指将现有药物用于新的治疗目的。由于基因组学和其他生物科学的进步，这种方法比从头开发新药更具成本效益，因此越来越受到关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Drug_repurposing">Drug repurposing</a></li>
<li><a href="https://www.fda.gov/news-events/press-announcements/fda-advances-drug-repurposing-address-unmet-medical-needs">FDA Advances Drug Repurposing to Address Unmet Medical Needs</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了关于药物再利用的具体例子，如使用贝伐单抗治疗黄斑变性，以及像 Cures Within Reach 这样的组织在为罕见病资助再利用药物研究时面临的挑战。

**标签**: `#healthcare`, `#drug-repurposing`, `#cost-savings`, `#innovation`

---

<a id="item-7"></a>
## [康奈尔大学推出自导式高级编译器课程](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 7.0/10

康奈尔大学发布了一门自导式在线高级编译器课程，涵盖了并行化、即时编译和垃圾回收等主题。 这门课程提供了来自知名机构的高质量、深入的内容，对于对编译器设计和优化感兴趣的学生和专业人士来说是一个宝贵的资源。 该课程使用 LLVM 和 Bril 进行实际任务，并涵盖通用编译器主题和研究导向的主题。然而，一些社区反馈指出，该课程可能没有涵盖领域内最前沿的话题。

hackernews · ibobev · Jun 18, 11:04 · [社区讨论](https://news.ycombinator.com/item?id=48583606)

**背景**: 编译器是软件工程中的重要工具，将高级编程语言翻译成机器代码。高级编译器技术专注于优化这一过程，以提高性能和效率。并行化和即时编译（JIT）等主题对于现代计算环境至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/">CS 6120: Advanced Compilers: The Self-Guided Online Course</a></li>
<li><a href="https://en.wikipedia.org/wiki/Optimizing_compiler">Optimizing compiler - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员提供了混合的反馈。一些人赞赏课程内容的全面性和可获得性，而另一些人则建议课程可以包含更多前沿话题，如类型反馈和推测。还有人将其与其他资源，如 Nora Sandler 的《编写 C 编译器》进行了比较。

**标签**: `#compilers`, `#online-education`, `#software-engineering`

---

<a id="item-8"></a>
## [W 社交平台的推出引发透明度和动机质疑](https://blog.elenarossini.com/w-social-public-institutions-and-the-theater-of-european-digital-sovereignty/) ⭐️ 7.0/10

新的欧洲社交网络 W Social 的推出受到了关于其透明度和潜在动机的批评和质疑。 这一新闻很重要，因为它突显了在欧洲建立新的社交平台所面临的挑战和担忧，特别是在数字主权和信任的背景下。 W Social 是一个有限责任公司，背景涉及金融领域，有人担心它可能会通过广告和付费功能来盈利。社区成员还指出，与其他开源替代品如 Eurosky 相比，W Social 缺乏透明度。

hackernews · nemoniac · Jun 18, 12:46 · [社区讨论](https://news.ycombinator.com/item?id=48584497)

**背景**: 数字主权是指一个地区通过开发和控制关键技术、数据和基础设施，在数字世界中独立行动的能力，同时减少对非本地提供商的依赖。W Social 的推出是欧洲在这方面努力的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://digital-strategy.ec.europa.eu/en/policies/eu-tech-sovereignty">Strengthening Europe’s Tech Sovereignty | Shaping Europe’s ...</a></li>
<li><a href="https://www.atlanticcouncil.org/in-depth-research-reports/report/digital-sovereignty-europes-declaration-of-independence/">Digital sovereignty: Europe’s declaration of independence?</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了对 W Social 透明度和动机的怀疑，一些用户指出创建多个账户的容易性以及对更透明替代品的媒体关注度不足。还有人担心 W Social 可能更像是一个政治工具，而不是一个真正的社交平台。

**标签**: `#Social Networks`, `#Digital Sovereignty`, `#European Tech`, `#Transparency`, `#Community Discussion`

---

<a id="item-9"></a>
## [Modos 彩色电子纸显示器推动显示技术进步](https://spectrum.ieee.org/modos-e-paper-monitor) ⭐️ 7.0/10

一家两人创业公司 Modos 正在开发一款 13.3 英寸的彩色电子纸显示器，分辨率为 3,200 x 2,400，支持触摸输入，并具有 60Hz 的刷新率。 这一电子纸显示技术的进步可能会显著影响便携设备和替代显示解决方案领域，提供更好的可读性和更低的功耗。 Modos Flow 电子纸显示器具有 60Hz 的刷新率，这比典型的电子墨水屏幕有了显著改进，使得滚动和交互更加流畅。

hackernews · Vinnl · Jun 18, 11:41 · [社区讨论](https://news.ycombinator.com/item?id=48583897)

**背景**: 电子纸是一种旨在模仿普通纸上墨水外观的显示技术。与传统显示器不同，电子纸不需要背光，可以在直射阳光下阅读。这项技术已被用于电子阅读器和其他低功耗设备中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Electronic_paper">Electronic paper - Wikipedia</a></li>
<li><a href="https://www.ijert.org/e-paper-technology">E-Paper Technology – IJERT</a></li>
<li><a href="https://www.visionect.com/blog/electronic-paper-explained-what-is-it-and-how-does-it-work/">Electronic paper explained: what is it and how does it work? - Visionect</a></li>

</ul>
</details>

**社区讨论**: 社区对这款设备的潜在应用和规格感到兴奋，讨论了其尺寸以及它为户外和低功耗使用场景带来的可能性。

**标签**: `#e-paper`, `#display-technology`, `#innovation`

---

