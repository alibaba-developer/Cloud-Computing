# 别人家的工程师：阿里巴巴工程师有了新帮手，AI可帮助修Bug.md

<div style="text-align:center" align="center">
<img src="/images/1.png" align="center" />
</div>
</br>
尽管工程师用代码创造了AI，但AI又可以对这些代码点评一番、甚至修复Bug，工程师和AI的关系正在变得微妙。

AI评委引热议，阿里巴巴表示：AI不会取代工程师

4月18日，2019阿里巴巴研发效能峰会——“83行代码挑战赛”决赛现场引入了一位“AI评委”，和专家评委、大众评委配合，对选手提交的的代码做综合评价，这也是全球代码比赛中出现的首位AI评委。

<div style="text-align:center" align="center">
<img src="/images/2.png" align="center" />
</div>
</br>

图为83行代码挑战赛决赛现场排行榜，AI评委、大众评委、专家评委给选手打分

这场面向阿里3万多名工程师的技术大会旨在进一步提升内部的研发效率，而“83行代码挑战赛”可以说是阿里巴巴史上最大规模的代码品鉴会。比赛源自1年前阿里内网一次集体晒83行代码的活动，阿里巴巴集团CTO张建锋、蚂蚁金服CTO程立，甚至马云、彭蕾都有参与。

这位AI评委运行在云端，当选手提交代码后，会从静态分析、运行时分析、群体共性等不同维度对代码快速打分。比赛现场，大屏实时显示选手分数，随着AI评委、专家评委、大众评委的分数依次出现，分数排行榜会根据综合打分实时滚动，一个逻辑语言的处理甚至可能瞬间提高选手排名。

结合现场专家和大众评委的观点来看，AI评委的评分相当准确，且打分最为迅速，几乎是在代码提交后立刻出现结果。

AI评委是谁？

这位AI评委来自阿里巴巴代码平台研发的人工智能系统，其中最重要的一环是集成了Precfix（Patch Recommendation by Empirically Clustering），不依赖测试用例、编译结果，通过非规则化的智能扫描，即可自动定位代码中的Bug，并提供修复建议，速度可达毫秒级，且误报率低。

<div style="text-align:center" align="center">
<img src="/images/3.png" align="center" />
</div>
</br>

Precfix能够发现一些规则检查和人工评审都无法发现的缺陷，根本性地提升代码质量，有效减少开发工程师debug及代码评审时间。同时，Precfix提供的修复建议，能帮助工程师快速理解缺陷和解决问题。

<div style="text-align:center" align="center">
<img src="/images/4.png" align="center" />
</div>
</br>

图为工程师根据Precfix提供的修复建议修复了缺陷

目前，Precfix已被部署到阿里巴巴代码生产环境，用于缺陷检查。工程师写好代码，就提交到线上，Precfix会进行review，指出缺陷代码及相应的修复建议。

据一位工程师透露，过去人工review代码查找bug可能需要几小时甚至几天时间不等，而现在不用一杯咖啡的时间，Precfix就可以review完提交的全部代码，提高了至少20%效率。

未来，Precfix还会随着阿里代码平台的上云，一起为全球开发者服务。
