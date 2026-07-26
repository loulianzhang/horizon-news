# Horizon Daily - 2026-07-26

> From 7 items, 4 important content pieces were selected

---

1. [Proposal to Eliminate Cookie Banners by Setting Browser Privacy Preferences](#item-1) ⭐️ 7.0/10
2. [Ruff v0.16.0 Released with 413 Default Rules](#item-2) ⭐️ 7.0/10
3. [Go Team Releases Modular Static Analysis Framework](#item-3) ⭐️ 7.0/10
4. [GrapheneOS Enhances Data Protection with BFU Reboot Feature](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Proposal to Eliminate Cookie Banners by Setting Browser Privacy Preferences](https://killthecookiebanner.eu/) ⭐️ 7.0/10

A proposal has been made to eliminate cookie banners by setting privacy preferences in the browser, allowing users to manage their consent once and for all. This change could significantly improve user experience by reducing the annoyance of frequent cookie banners and potentially enhancing web privacy, while also impacting the revenue models of websites that rely on tracking. The proposal suggests that users set their privacy preferences in the browser, which would then be applied to all websites, eliminating the need for individual cookie banners. This approach is being debated, with some arguing it could undermine the effectiveness of informed consent.

hackernews · rapnie · Jul 26, 11:53 · [Discussion](https://news.ycombinator.com/item?id=49057175)

**Background**: Cookie banners are pop-ups that seek visitor permission for cookie usage, as mandated by privacy laws like GDPR. They are used to inform users about the collection and use of their data, but they can be intrusive and often go unread. Modern browsers already offer privacy settings, such as tracking prevention, which can be customized to different levels.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cookie_banner">Cookie banner</a></li>
<li><a href="https://usercentrics.com/knowledge-hub/cookie-banner/">What is a Cookie Banner? Shortly Explained | Usercentrics</a></li>
<li><a href="https://www.osano.com/articles/cookie-banner">Cookie Banner: What Is It & Why Do You Need One? | Osano</a></li>

</ul>
</details>

**Discussion**: Community members have mixed opinions, with some supporting the elimination of cookie banners for a better browsing experience, while others are concerned about the impact on website revenue and the effectiveness of informed consent. Some suggest that the focus should be on stopping unnecessary data tracking altogether.

**Tags**: `#web-privacy`, `#user-experience`, `#browser-settings`, `#data-tracking`

---

<a id="item-2"></a>
## [Ruff v0.16.0 Released with 413 Default Rules](https://astral.sh/blog/ruff-v0.16.0) ⭐️ 7.0/10

Ruff v0.16.0 has been released, increasing the number of default rules from 59 to 413, significantly enhancing code quality and catching more issues. This update is significant for Python developers as it improves code quality and helps catch more potential issues, making the development process more efficient and reliable. The new version includes a wide range of linting rules, many of which are inspired by popular tools like Flake8, isort, and pyupgrade. Ruff re-implements these rules in Rust, providing faster performance.

hackernews · vismit2000 · Jul 26, 09:01 · [Discussion](https://news.ycombinator.com/item?id=49056112)

**Background**: Ruff is a high-performance Python linter and code formatter written in Rust. It can replace multiple static analysis tools and executes 10-100x faster than existing linters and formatters. Ruff supports over 700 lint rules and can be configured through a `pyproject.toml` file.

<details><summary>References</summary>
<ul>
<li><a href="https://astral.sh/ruff">Ruff, an extremely fast Python linter | Astral</a></li>
<li><a href="https://github.com/astral-sh/ruff">GitHub - astral-sh/ruff: An extremely fast Python linter and ... Python code quality with Ruff - Part 1 | Airbus Static Code Analysis in 2026: Best Linters, SAST Tools, and ... The Ruff Linter | Ruff - Astral Ruff: Extremely Fast Python Linter — Here’s Why - Medium Building a Robust Prototyping Environment with Poetry and ...</a></li>
<li><a href="https://docs.astral.sh/ruff/rules/">Rules | Ruff - Astral Docs</a></li>

</ul>
</details>

**Discussion**: Community feedback is generally positive, with users noting that the new rules improve code quality. Some users, however, express concerns about the arbitrary nature of some rules and the challenges of updating Ruff at scale.

**Tags**: `#Python`, `#Code Quality`, `#Static Analysis`, `#Tooling`, `#Software Development`

---

<a id="item-3"></a>
## [Go Team Releases Modular Static Analysis Framework](https://pkg.go.dev/golang.org/x/tools/go/analysis) ⭐️ 7.0/10

The Go team has developed a modular static analysis framework, which is available at golang.org/x/tools/go/analysis, to enhance code quality and maintainability. This framework allows developers to create custom analyzers, making it easier to enforce coding standards and improve the overall quality of Go projects. The framework is already used by many linters and can be integrated into existing Go projects. It supports the creation of custom analyzers and can be extended with additional checks.

hackernews · AbuAssar · Jul 26, 12:21 · [Discussion](https://news.ycombinator.com/item?id=49057398)

**Background**: Static analysis is a method of evaluating code without executing it, which helps in identifying potential issues and improving code quality. The Go language, known for its simplicity and strong tooling, benefits from such frameworks to maintain high standards in software development.

<details><summary>References</summary>
<ul>
<li><a href="https://arslan.io/2020/07/07/using-go-analysis-to-fix-your-source-code/">Using go / analysis to fix your source code</a></li>

</ul>
</details>

**Discussion**: The community has provided positive feedback on the framework, with users highlighting its effectiveness in improving code quality and reducing the need for manual code reviews. Some users have also noted that the framework is not new but is widely used and appreciated.

**Tags**: `#Go`, `#Static Analysis`, `#Code Quality`, `#Tooling`

---

<a id="item-4"></a>
## [GrapheneOS Enhances Data Protection with BFU Reboot Feature](https://discuss.grapheneos.org/d/40700-grapheneos-protections-against-data-extraction-from-locked-devices) ⭐️ 7.0/10

GrapheneOS has introduced a feature that reboots the device to Before First Unlock (BFU) mode after 18 hours, enhancing data protection on locked devices. This feature is significant for users concerned about data privacy and security, as it prevents unauthorized access to sensitive information even if the device is physically seized. In BFU mode, encryption keys are not available, making it extremely difficult to extract data. This feature complements other GrapheneOS security measures, such as sandboxed apps and enhanced permission models.

hackernews · Cider9986 · Jul 26, 05:57 · [Discussion](https://news.ycombinator.com/item?id=49055169)

**Background**: GrapheneOS is an open-source mobile operating system focused on security and privacy, built on the Android Open Source Project (AOSP). It includes various features to enhance user privacy and security, such as defense in depth improvements and attack surface reduction. BFU mode refers to a state where the device has been powered off or reset and has not been signed back into using the screen lock passcode, making it more secure against data extraction.

<details><summary>References</summary>
<ul>
<li><a href="https://blogs.dsu.edu/digforce/2023/08/23/bfu-and-afu-lock-states/">BFU and AFU Lock States – Blog | DigForCE Lab - DSU</a></li>
<li><a href="https://en.wikipedia.org/wiki/GrapheneOS">GrapheneOS</a></li>

</ul>
</details>

**Discussion**: Community members discussed the importance of the BFU reboot feature, noting its effectiveness in protecting data. Some users suggested additional features, such as a complete backup and restore solution, to further enhance security and usability.

**Tags**: `#security`, `#privacy`, `#mobile-os`, `#grapheneos`

---

