# 重磅发布：阿里开源 OpenJDK 长期支持版本 Alibaba Dragonwell.md

3 月 21 日北京阿里云峰会，阿里巴巴正式宣布对外开源 OpenJDK 长期支持版本 Alibaba Dragonwell。作为 Java 全球管理组织 Java Community Process (JCP) 的最高执行委员会的唯一中国代表，以及 Oracle 之外的 Java 生态中为数不多的 OpenJDK 定制者，Alibaba Dragonwell 的开源是阿里巴巴向全球 Java 开发者的重磅献礼。

<div style="text-align:center" align="center">
<img src="/images/重磅发布：阿里开源 OpenJDK 长期支持版本 Alibaba Dragonwell1.png" align="center" />
</div>

</br>

<div style="text-align:center" align="center">

北京阿里云峰会宣布 Alibaba Dragonwell 开源现场

<b>这就是 Alibaba Dragonwell</b>
</div>



Alibaba Dragonwell 是一款免费的 OpenJDK 发行版。它提供长期支持，包括性能增强和安全修复。Alibaba Dragonwell 目前支持 X86-64/Linux 平台，在数据中心大规模 Java 应用部署情况下， 可以大幅度提高稳定性、效率以及性能。Alibaba Dragonwell 与 Java SE 标准兼容，用户可以使用 Alibaba Dragonwell 开发和运行 Java 应用程序。


<div style="text-align:center" align="center">
<img src="/images/重磅发布：阿里开源 OpenJDK 长期支持版本 Alibaba Dragonwell2.png" align="center" />
</div>

</br>


此次，阿里巴巴发布的 Alibaba Dragonwell 8 预览版本对应 OpenJDK 8 的版本。Alibaba Dragonwell的开源为全球 Java 开发者提供了新选择。同时对于阿里云，Alibaba Dragonwell 会针对 LTS 的两个版本 Java 8 和 Java 11 随阿里云 VM 镜像发布，免费提供给阿里云客户使用。




<div style="text-align:center" align="center">
<b>AJDK 的优势继承者——Alibaba Dragonwell</b>
</div>
</br>
Alibaba Dragonwell 的前身是阿里巴巴内部使用的 AJDK(Alibaba/AlipayJDK)。早在 2010 年，阿里巴巴就开始了基于 OpenJDK 开源软件的开发，并在 2015 年着手 OpenJDK 8 的优化和定制工作。


AJDK 作为阿里巴巴 Java 应用的基石，支撑了阿里经济体内所有的 Java 业务，经受了多次双十一考验,积累了大量业务场景下的实践经验。作为在 Oracle 之外的 Java 生态中的 OpenJDK 定制者， 阿里一直不遗余力持续开拓 Java 新疆界：

- 2015 年 10月，AJDK8.0.0 发布，实现多租户，支持高密度部署以及资源隔离。

- 2016 年 5月，AJDK 8.1.1 发布，支持 JWarmup,支持 Java 应用在运行时提前编译。

- 2016 年10月，AJDK 8.2.4 发布，实现Wisp协程 ，有效提升 Java 应用性能 30% 以上。

- 2018 年 1 月，AJDK 8.4.7  发布，根据阿里大数据场景的定制版 ZenGC (G1 based)发布。

- 2018 年 2月，发布基于 AJDK 的 Java Profiling 工具 Java Event Tracing(JET) 。



作为 AJDK 的开源版本， Alibaba Dragonwell 沿袭了 AJDK 的技术优势以及实践场景下的技术经验。开源后，Alibaba Dragonwell 的每次发布都将会同步 OpenJDK 8 的最新更新(OpenJDK 8u)，并将基于阿里的工程实践，加入阿里的'value-add' 功能。Alibaba Dragonwell 版本会通过 JCK 兼容套件测试，确保 Java 的兼容性。


<div style="text-align:center" align="center">
<b>Alibaba Dragonwell 与 OpenJDK</b>
</div>
</br>
Oracle 宣布 Java8 在 2019 年 1月之后停止更新，另外 Java11 及以后版本将不再提供免费的 long-term support (LTS) 支持。可以预见，未来将有越来越多 Java 开发者转向使用 OpenJDK。阿里巴巴长期致力于与 Java 技术推进的聚集地——OpenJDK 社区密切合作，Alibaba Dragonwell 将保持与社区版本的同步，并充分融合阿里巴巴业务实践与技术经验，为 Java 开发者提供一个良好的应对方案。



Alibaba Dragonwell 8 的优势
- 移植上游 Java 11 的 Java Flight Recorder (JFR) 功能，Java 开发人员可以通过 JFR 收集 JVM 运行过程中的详细的 profiling 信息，配合 Java Mission Control(JMC),  大幅提高 Java 应用的问题诊断及性能优化效率；

- 集成 AJDK 的 JWarmup 技术，JWarmup 已作为 Java Enhancment Proposal(JEP) 在 OpenJDK 立项，未来有望加入 Java 的标准发行版中。JWarmup 在数据中心可以结合应用的流量调度时机，动态预编译Java 代码，可以有效减少由于传统的 Just-in-Time 的预热(Warmup)导致的 CPU load 过高，rt 超时等问题。

- 提供在 GC 问题诊断 Servicibility 方面的提高， 详细信息参考 Alibaba Dragonwell 8 User Guide <https://github.com/alibaba/dragonwell8/wiki/阿里巴巴Dragonwell8用户指南>


<div style="text-align:center" align="center">
<b>Alibaba Dragonwell Roadmap</b>
</div>
</br>
作为 OpenJDK 的下游，Alibaba Dragonwell 将在每季度发布新版本主要包含：

- 社区上游安全/关键 bug 修复

- 阿里定制的功能，Bug修复等。

- 基于阿里工程实践的 Java 8 以后版本的功能移植



我们计划逐步把阿里巴巴内部使用 AJDK 积累的技术创新开源出来贡献给社区。同时，我们预计 2019 年年底发布 Alibaba Dragonewell 11。



Github Link：https://github.com/alibaba/dragonwell8


<div style="text-align:center" align="center">
<b>Alibaba Dragonwell FAQ</b>
</div>
</br>
在宣布开源前夕，InfoQ 记者对阿里云智能基础产品事业部资深技术专家李三红、阿里云智能基础产品事业部研究员 Kingsum Chow (周经森)进行了采访，以下就大家关心的问题做一下整理。


Q1.Alibaba Dragonwell 命名有什么由来？
“Dragonwell”中文译为龙井，象征着中国的茶文化，又恰好是杭州特色（阿里巴巴总部所在地）；“well”一词通常被描述为水源汇聚在一起供大家享用，我们希望可以集合所有开发者的力量不断完善该项目并最终贡献给所有用户。

Q2.开源的 Alibaba Dragonwell 与阿里内部使用的 AJDK 是一个东西吗？
本次开源的 Alibaba Dragonwell 与阿里内部使用的 AJDK 还是有差异的。Alibaba Dragonwell 是 AJDK 的开源版本，AJDK 技术的继承者。目前开源的版本并未包含 AJDK 的所有功能，比如多租户，Wisp 协程，ZenGC 等。之后，会考虑将 AJDK 的功能逐渐过渡到 Alibaba Dragonwell。

Q3.Alibaba Dragonwell 与 OpenJDK 关系是怎么样的？阿里巴巴是否会持续维护 OpenJDK 社区？
Alibaba Dragonwell 一定是 OpenJDK 的下游，每个 Alibaba Dragonwell 发行版都会同步上游最新更新，并经过阿里巴巴内部大规模的应用集群测试。同时，阿里巴巴也会积极将 AJDK 上的技术积累贡献到 OpenJDK，积极参与社区的项目更新和维护。我们期待与 OpenJDK 社区密切合作，共同推动 OpenJDK 的发展。

Q4. 如何看待Java 版本的升级？ 如何看待 Oracle JDK 与 OpenJDK 的关系？
Java 8 是目前最被广泛使用的版本，并且其群体非常坚守。在 Java 圈内，你会发现一个很有趣的现象：无论新版本给出的更新多么诱惑，大部分 Java 开发者似乎并不感兴趣，依旧坚持自己的选择。确实，Java 8 是一个非常成功的版本，以至于很多开发者并不认为需要更新其他版本，这可能与长期养成的习惯和固有信任有关系。Java 这么多年发展过来，大多数开发者已经习惯信任官方 Oracle JDK，对社区 OpenJDK 版本关注不够，所以从 Oracle JDK 到 OpenJDK 的切换需要一个过程。但随着这些国际科技大厂的努力，OpenJDK 的生态一定会越来越完善，功能也会更加齐备，面对持续的安全更新和众多大厂的深度参与，这个项目应该会成为 Java 生态中的重要公共资源。

a href="https://yq.aliyun.com/articles/694603">原文链接</a>
