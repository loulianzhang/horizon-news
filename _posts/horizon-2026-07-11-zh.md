# Horizon 每日速递 - 2026-07-11

> From 5 items, 2 important content pieces were selected

---

1. [PgBouncer 性能提升至四倍吞吐量](#item-1) ⭐️ 7.0/10
2. [爱因斯坦的相对论影响重元素的化学键](#item-2) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [PgBouncer 性能提升至四倍吞吐量](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 7.0/10

作者描述了将 PgBouncer 的吞吐量提升到原来的四倍，社区评论提供了替代工具和配置。 PgBouncer 吞吐量的这一改进对于提高数据库性能非常重要，可以带来更好的应用程序响应性和资源利用率。 设置中使用了 so_reuseport 和对等连接，这是实现四倍吞吐量的关键组件。社区还建议使用 Odyssey 和 pgdog 作为替代方案。

hackernews · saisrirampur · Jul 11, 15:28 · [社区讨论](https://news.ycombinator.com/item?id=48872874)

**背景**: PgBouncer 是一个轻量级的 PostgreSQL 数据库连接池工具，旨在减少建立新连接的开销。Kubernetes 是一个流行的容器编排系统，可以高效地管理和扩展应用程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.pgbouncer.org/">PgBouncer - lightweight connection pooler for PostgreSQL</a></li>
<li><a href="https://kubernetes.io/docs/concepts/workloads/autoscaling/horizontal-pod-autoscale/">Horizontal Pod Autoscaling | Kubernetes</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了 Odyssey 和 pgdog 等替代工具，并分享了在 Kubernetes 上运行多个 PgBouncer 进程的经验。一些人还询问了结合使用 HAProxy 和 PgBouncer 的情况。

**标签**: `#database`, `#performance`, `#PgBouncer`, `#scaling`, `#Kubernetes`

---

<a id="item-2"></a>
## [爱因斯坦的相对论影响重元素的化学键](https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity) ⭐️ 7.0/10

新研究表明，爱因斯坦的相对论在重元素的化学键中起着关键作用，影响它们的性质和行为。 这一发现弥合了基础物理学和化学之间的差距，为重元素的行为提供了更深入的见解，并可能带来新材料和技术的发展。 重元素中的核质量增加导致轨道电子以接近光速的速度运动，在这种情况下，相对论效应变得重要。这导致了诸如自旋-轨道耦合等现象，影响化学键的形成。

hackernews · hhs · Jul 10, 22:30 · [社区讨论](https://news.ycombinator.com/item?id=48866134)

**背景**: 爱因斯坦的相对论描述了高速度和强引力场如何影响物理定律。在重元素的情况下，电子的高速运动意味着经典物理学不再足以准确描述其行为。自旋-轨道耦合是一种量子力学效应，其中电子的自旋和轨道运动是相互依赖的，导致原子能级和化学性质的变化。

**社区讨论**: 社区成员讨论了相对论效应对重元素性质的影响，例如汞在室温下呈液态是因为其内层电子以接近光速 60%的速度运动。一些人还指出，相对论对重元素的影响已经为人所知，例如金的颜色就是由相对论效应引起的。

**标签**: `#Physics`, `#Chemistry`, `#Relativity`, `#Research`

---

