# Horizon Daily - 2026-07-16

> From 17 items, 12 important content pieces were selected

---

1. [Kimi K3, a 2.8T Parameter Language Model, Now Live](#item-1) ⭐️ 8.0/10
2. [Thinking Machines Lab Releases Open-Weights Multimodal Model Inkling](#item-2) ⭐️ 8.0/10
3. [Linus Torvalds Embraces AI in Linux Project](#item-3) ⭐️ 8.0/10
4. [xAI's Grok CLI Tool Open-Sourced After Privacy Backlash](#item-4) ⭐️ 8.0/10
5. [Microsoft Comic Chat Open-Sourced](#item-5) ⭐️ 7.0/10
6. [GOES-19 Weather Satellite Enters Safe Hold Mode](#item-6) ⭐️ 7.0/10
7. [Developer Shares Rust-to-Zig Rewrite Experience](#item-7) ⭐️ 7.0/10
8. [Sony Deletes Purchased Movies from User Accounts](#item-8) ⭐️ 7.0/10
9. [Critical Bug in GPT-5.6 Leads to File Deletions](#item-9) ⭐️ 7.0/10
10. [New Tool Renders Mermaid Diagrams as Unicode Box Art](#item-10) ⭐️ 7.0/10
11. [Nostalgia and Cultural Impact of Music Piracy](#item-11) ⭐️ 6.0/10
12. [Technical Guide on Building a Scalable Database Infrastructure](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Kimi K3, a 2.8T Parameter Language Model, Now Live](https://www.kimi.com/en) ⭐️ 8.0/10

Kimi K3, a new language model with 2.8 trillion parameters and 1 million context, has been released, claiming to deliver frontier-level performance. The release of Kimi K3 is significant because it claims to be second only to Claude Fable 5 and GPT-5.6 Sol in overall intelligence, potentially offering a powerful alternative for advanced AI applications. Kimi K3 supports 1 million context tokens and is priced at $3/$15 for 1 million tokens, which is high but justified if the performance claims hold true. The full model weights will be released by July 27, along with a technical report.

hackernews · vincent_s · Jul 16, 14:46 · [Discussion](https://news.ycombinator.com/item?id=48935342)

**Background**: Language models like Kimi K3 are used for a variety of tasks, from text generation to complex reasoning. The 1 million context length is a significant improvement over previous models, which typically had much shorter context windows. This allows the model to handle more extensive and detailed information, making it suitable for a wider range of applications.

**Discussion**: Community members have noted that while the pricing is high, it is justified if the model's performance is truly competitive with top-tier models like Claude Fable 5 and GPT-5.6 Sol. There is also excitement about the upcoming release of the full model weights and technical report, which will provide more details on the architecture and training process.

**Tags**: `#AI`, `#Machine Learning`, `#Language Models`, `#Kimi K3`

---

<a id="item-2"></a>
## [Thinking Machines Lab Releases Open-Weights Multimodal Model Inkling](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Thinking Machines Lab has released Inkling, a 975B parameter multimodal model with an Apache-2.0 license, trained on 45 trillion tokens of text, images, audio, and video. The release of a large, open-weights multimodal model is significant and could have a substantial impact on the field, enabling more innovation and research. Inkling is a Mixture-of-Experts transformer with 975B total parameters and 41B active parameters. It is intended as a strong base model for fine-tuning using their Tinker training platform.

rss · Simon Willison · Jul 16, 15:35

**Background**: Multimodal models are capable of processing and integrating multiple types of data, such as text, images, audio, and video. Mixture-of-Experts (MoE) transformers are a type of neural architecture that uses numerous parallel expert subnetworks to process tokens efficiently, ensuring scalability and efficient compute.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/mixture-of-experts-transformer">Mixture - of - Experts Transformer</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multimodal_model">Multimodal model</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Machine Learning`, `#Open Source`, `#Multimodal Models`

---

<a id="item-3"></a>
## [Linus Torvalds Embraces AI in Linux Project](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds, the top-level maintainer of Linux, has stated that AI is a useful tool and will be embraced in the Linux project. He encouraged those who disagree to fork the project or leave. This stance by Linus Torvalds, a highly influential figure in the open-source community, is significant and likely to influence the broader tech community's approach to AI integration in software projects. Torvalds emphasized that AI is clearly a useful tool, and any doubts about its utility are unfounded. He also noted that while there are other questions around AI, its usefulness is no longer in question.

rss · Simon Willison · Jul 16, 13:26

**Background**: Linus Torvalds is the creator and principal developer of the Linux kernel, which is the core component of the Linux operating system. The Linux project is one of the most prominent open-source projects, and its direction often sets trends in the software development community.

**Tags**: `#Linux`, `#AI`, `#Open-Source`, `#Software Engineering`

---

<a id="item-4"></a>
## [xAI's Grok CLI Tool Open-Sourced After Privacy Backlash](https://simonwillison.net/2026/Jul/15/grok-build/#atom-everything) ⭐️ 8.0/10

xAI's `grok` CLI tool, which was uploading entire directories to xAI's Google Cloud buckets, faced severe community backlash. In response, xAI disabled the problematic feature and open-sourced the entire Grok Build codebase under an Apache 2.0 license. This incident highlights the importance of privacy and security in developer tools. The open-sourcing of the codebase is a significant step towards regaining user trust and ensuring transparency. The Grok Build codebase contains 844,530 lines of Rust, with only around 3% being vendored. The initial release includes a single commit, and the codebase has been configured to respect user data retention preferences.

rss · Simon Willison · Jul 15, 23:59

**Background**: Grok Build is SpaceXAI's terminal-based AI coding agent, designed to understand and manage codebases, execute shell commands, and interact with the web. The recent privacy issue involved the tool uploading sensitive data without user consent, leading to significant concerns among developers.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/xai-org/grok-build">GitHub - xai-org/grok-build: SpaceXAI's coding agent harness and TUI ...</a></li>
<li><a href="https://x.ai/cli">Grok Build | SpaceXAI</a></li>
<li><a href="https://docs.x.ai/build/overview">Grok Build | SpaceXAI Docs</a></li>

</ul>
</details>

**Discussion**: The community expressed strong concern over the privacy violation, with many users reporting that their personal and sensitive data, including SSH keys and password manager databases, were uploaded. The open-sourcing of the codebase was generally seen as a positive step, but some users remain skeptical about the company's commitment to privacy.

**Tags**: `#security`, `#open-source`, `#CLI-tools`, `#privacy`

---

<a id="item-5"></a>
## [Microsoft Comic Chat Open-Sourced](https://opensource.microsoft.com/blog/2026/07/16/microsoft-comic-chat-is-now-open-source/) ⭐️ 7.0/10

Microsoft has open-sourced Comic Chat, a piece of internet history, with the support of its original developer and community enthusiasts. This move is significant for those interested in the history of internet communication and software preservation, as it allows for further development and exploration of this historical software. The open-sourcing was made possible by the efforts of Robert Standefer and Scott Hanselman, with the support of the original developer DJ Kurlander. The project spans a six-year period and highlights the importance of being in the right place at the right time.

hackernews · jervant · Jul 16, 16:06 · [Discussion](https://news.ycombinator.com/item?id=48936426)

**Background**: IRC (Internet Relay Chat) is a text-based chat system for instant messaging, designed for group communication in discussion forums called channels. Comic Chat, originally released in the 1990s, extended the IRC protocol to include graphical avatars and emoting, making it a unique piece of internet history. Software preservation aims to ensure that digital information remains accessible and usable over time, even as technology changes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/IRC">IRC</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software_preservation">Software preservation</a></li>

</ul>
</details>

**Discussion**: Community members have shared personal stories and memories related to Comic Chat, highlighting its impact on their lives and projects. Some recall the mixed reception it received in the early 2000s, while others express enthusiasm about its potential for future development.

**Tags**: `#open-source`, `#internet-history`, `#microsoft`, `#irc`, `#software-preservation`

---

<a id="item-6"></a>
## [GOES-19 Weather Satellite Enters Safe Hold Mode](https://www.spaceweather.gov/news/goes-19-safe-hold) ⭐️ 7.0/10

The GOES-19 weather satellite, which is critical for tracking Atlantic and Gulf Coast hurricanes, has entered Safe Hold mode, affecting its operational capabilities. This issue with GOES-19 could impact real-time hurricane tracking and forecasting, which is crucial for public safety and disaster preparedness in the affected regions. In Safe Hold mode, all non-essential systems are shut down, and only essential functions such as thermal management, radio reception, and attitude control remain active. Engineers are working to recover the satellite and will provide a recovery timeline when available.

hackernews · yabones · Jul 16, 13:30 · [Discussion](https://news.ycombinator.com/item?id=48934286)

**Background**: GOES-19 is part of the GOES-R series of satellites operated by the National Oceanic and Atmospheric Administration (NOAA). These satellites are essential for providing real-time tracking and monitoring of tropical storms and hurricanes in the Atlantic, Caribbean, and Gulf of Mexico. The Safe Hold mode is a precautionary measure to ensure the satellite's safety during anomalies or issues.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Safe_mode_in_spacecraft">Safe mode in spacecraft - Wikipedia</a></li>
<li><a href="https://usradioguy.com/news/goes-19-in-safe-hold/">GOES-19 in Safe Hold - USRadioguy.com</a></li>
<li><a href="https://www.nesdis.noaa.gov/news-events/goes-u-launch/goes-u-benefits-capabilities">GOES-U Benefits & Capabilities | NESDIS | National Environmental Satellite, Data, and Information Service</a></li>

</ul>
</details>

**Discussion**: A former GOES engineer noted that it's not uncommon for these satellites to experience issues, citing past problems with other GOES satellites. Another user explained that 'safe mode' for a satellite typically involves extending solar panels, turning towards the sun, and waiting for further instructions. A community member also mentioned observing the issue in real time while checking visible-light geocolor composite images.

**Tags**: `#satellite`, `#weather`, `#GOES-19`, `#space-technology`, `#hurricane-monitoring`

---

<a id="item-7"></a>
## [Developer Shares Rust-to-Zig Rewrite Experience](https://rtfeldman.com/rust-to-zig) ⭐️ 7.0/10

The author shares their experience and progress on rewriting a Rust project in Zig, discussing the motivations, challenges, and benefits of the transition. This deep-dive provides valuable insights into the practical aspects of transitioning between two modern system programming languages, highlighting the trade-offs and potential improvements. The rewrite aims to leverage Zig's features such as incremental builds and cross-compilation, while addressing memory safety and performance concerns.

hackernews · jorangreef · Jul 16, 11:39 · [Discussion](https://news.ycombinator.com/item?id=48933149)

**Background**: Rust is a system programming language known for its focus on safety, concurrency, and performance. Zig, on the other hand, is designed to be a general-purpose improvement to C, with features like compile-time generic programming and manual memory management. Both languages are used for building robust and efficient software.

<details><summary>References</summary>
<ul>
<li><a href="https://rtfeldman.com/rust-to-zig">How Our Rust-to-Zig Rewrite is Going</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**Discussion**: Community members discussed the necessity of unsafe code in compilers, the effectiveness of Zig's runtime checks, and the advantages of Zig's incremental builds. Some also questioned the choice of Zig over more mature languages like OCaml.

**Tags**: `#Rust`, `#Zig`, `#Compiler`, `#Rewrite`, `#Technical Deep-Dive`

---

<a id="item-8"></a>
## [Sony Deletes Purchased Movies from User Accounts](https://www.techdirt.com/2026/07/15/sony-deletes-a-bunch-more-movies-from-the-accounts-of-people-who-bought-them/) ⭐️ 7.0/10

Sony is deleting movies from the accounts of users who purchased them, raising concerns about digital ownership and consumer rights. This action highlights the ongoing debate over what it means to 'own' digital content and the need for clearer consumer protections in the digital age. The deletion of movies affects users who believed they had purchased the content, leading to discussions about the legal and ethical implications of such practices.

hackernews · nekusar · Jul 16, 12:13 · [Discussion](https://news.ycombinator.com/item?id=48933419)

**Background**: In the digital age, the concept of ownership has become more ambiguous. Unlike physical goods, digital content can be easily removed or restricted by the provider, even after a purchase. This raises questions about the true nature of digital ownership and the rights of consumers.

<details><summary>References</summary>
<ul>
<li><a href="https://law.vanderbilt.edu/gone-but-not-forgotten/">Gone but Not Forgotten: The Digital Ownership Dilemma and the ...</a></li>
<li><a href="https://candorion.com/consumer-rights-in-digital-purchases/">Understanding Consumer Rights in Digital Purchases: Legal ...</a></li>

</ul>
</details>

**Discussion**: Community members are discussing the legality and ethics of selling digital content as if it were a permanent purchase, with some advocating for stronger laws to protect consumers. There is also a sentiment that this practice may drive users away from digital platforms towards physical media.

**Tags**: `#digital rights`, `#consumer protection`, `#gaming industry`

---

<a id="item-9"></a>
## [Critical Bug in GPT-5.6 Leads to File Deletions](https://simonwillison.net/2026/Jul/16/bad-codex-bug/#atom-everything) ⭐️ 7.0/10

Thibault Sottiaux reported a critical bug in GPT-5.6 where files are unexpectedly deleted when certain conditions are met, such as running without sandboxing protections and the model making an error with the $HOME environment variable. This bug is significant because it can lead to data loss, which is a major concern for developers and users of the technology. It highlights the importance of robust security and testing measures in AI systems. The file deletions occur most commonly when full access mode is enabled, and the model attempts to override the $HOME environment variable to define a temporary directory, but mistakenly deletes the $HOME directory instead.

rss · Simon Willison · Jul 16, 17:45

**Background**: GPT-5.6 is a large language model developed by OpenAI, designed to expand user capabilities across various domains including coding, scientific research, and cybersecurity. Codex, integrated into GPT-5.6, is a coding agent that helps users write, review, and ship code faster.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6">GPT-5.6</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT-5.6 Sol: a next-generation model | OpenAI</a></li>
<li><a href="https://openai.com/codex/">Codex in ChatGPT | AI Coding Agents for Software... | OpenAI</a></li>

</ul>
</details>

**Tags**: `#codex`, `#coding-agents`, `#generative-ai`

---

<a id="item-10"></a>
## [New Tool Renders Mermaid Diagrams as Unicode Box Art](https://simonwillison.net/2026/Jul/16/grok-mermaid/#atom-everything) ⭐️ 7.0/10

Simon Willison introduced a new tool, grok-mermaid, which renders Mermaid diagrams as Unicode box art in the terminal, enhancing the utility of Mermaid for text-based environments. This tool is significant because it allows developers to create and view diagrams directly in the terminal, improving workflow efficiency and making it easier to work with text-based interfaces. The tool is written in Rust and can be used via WebAssembly in a browser. It provides controls for adjusting the diagram's width and copying the rendered text or link.

rss · Simon Willison · Jul 16, 00:33

**Background**: Mermaid is an open-source diagramming library that uses a simple markdown-like syntax to generate charts and diagrams. Unicode box-drawing characters are a set of characters used to create borders and lines in text-based interfaces, commonly used in legacy graphics standards.

<details><summary>References</summary>
<ul>
<li><a href="https://mermaid.ai/open-source/">Mermaid | Diagramming and charting tool</a></li>
<li><a href="https://en.wikipedia.org/wiki/Box-drawing_characters">Box-drawing characters - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Mermaid`, `#Rust`, `#WebAssembly`, `#CLI Tools`, `#Developer Tools`

---

<a id="item-11"></a>
## [Nostalgia and Cultural Impact of Music Piracy](https://www.pigeonsandplanes.com/read/music-piracy-what-cd-oink-nine-inch-nails-streaming) ⭐️ 6.0/10

The article reflects on the cultural and social aspects of music piracy, comparing it to the current streaming era. This reflection highlights how music piracy influenced music discovery and personal connections, providing a nostalgic look at a bygone era. The article discusses the unique ways in which music piracy facilitated the sharing and discovery of music, often through personal networks and subcultures.

hackernews · mcgin · Jul 16, 04:46 · [Discussion](https://news.ycombinator.com/item?id=48930454)

**Background**: Music piracy was a significant part of the digital music landscape before the rise of legal streaming services. It involved the unauthorized distribution and downloading of music, often through peer-to-peer (P2P) networks. This practice allowed users to access a wide variety of music that might not have been available through official channels.

**Discussion**: Community members shared personal experiences, noting the cultural buy-in and network effects of music piracy, and the challenges in finding niche music in the current streaming era. Some also highlighted the limitations of streaming services in providing a full archive of music.

**Tags**: `#music`, `#cultural-impact`, `#music-discovery`, `#nostalgia`

---

<a id="item-12"></a>
## [Technical Guide on Building a Scalable Database Infrastructure](https://onatm.dev/2026/07/16/homescale-part-1/) ⭐️ 6.0/10

A technical guide was published, detailing how to build a scalable database infrastructure inspired by PlanetScale, with community feedback highlighting missing components and alternative approaches. This guide provides valuable insights into building scalable databases, which is crucial for handling large-scale data and ensuring high performance and reliability in modern applications. The guide focuses on the infrastructure aspects but lacks details on sharding and zero-downtime operations, which are key features of PlanetScale. Community feedback suggests additional considerations such as bouncers, gateways, and reverse proxies.

hackernews · onatm · Jul 16, 11:58 · [Discussion](https://news.ycombinator.com/item?id=48933303)

**Background**: PlanetScale is a serverless database platform that offers MySQL-compatible databases built on Vitess. It provides features like automated horizontal sharding, database branching for development workflows, zero-downtime schema changes, and high scalability. Building a scalable database infrastructure involves careful consideration of data partitioning, replication, caching, and load balancing.

<details><summary>References</summary>
<ul>
<li><a href="https://planetscale.com/">PlanetScale - the world’s fastest and most scalable cloud hosting for Vitess and Postgres</a></li>
<li><a href="https://www.geeksforgeeks.org/dbms/building-a-scalable-database/">Building a Scalable Database - GeeksforGeeks</a></li>

</ul>
</details>

**Discussion**: Community members pointed out that the guide misses key components like sharding and zero-downtime operations, which are essential for a true PlanetScale-like setup. They also suggested alternative approaches and highlighted the challenges of separating compute and storage.

**Tags**: `#database`, `#infrastructure`, `#scalability`, `#PlanetScale`, `#Postgres`

---

