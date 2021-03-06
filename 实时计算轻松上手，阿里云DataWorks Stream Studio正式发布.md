# 实时计算轻松上手，阿里云DataWorks Stream Studio正式发布.md

Stream Studio是DataWorks旗下重磅推出的全新子产品。已于2019年4月18日正式对外开放使用。Stream Studi是一站式流计算开发平台，基于阿里巴巴实时计算引擎Flink构建，集可视化拖拽DAG和SQL两种开发模式，支持DAG与SQL互相转换，通过可视化拖拽就可以轻松实现流计算作业开发，适用于实时ETL、实时报表、实时大屏、监控预警以及各类实时在线系统等应用场景。

Stream Studio的推出意味着DataWorks正式对外提供实时计算能力，进入到流、批全覆盖的大数据全功能领域

在现有的实时数据开发领域中，用户普遍面临下面几大问题：
流任务开发复杂

无论是SQL还是Java、python，开发任务必须写代码，而且代码形式不利于后期业务逻辑分析和维护
开发过程中无法调试，只能等全部任务完成，才能上线调试，有问题修改后在上线，反复验证
UDF开发需要单独打包编译上传，跟任务本身属于分割开发状态，容易造成流程繁琐，版本混淆
运维难度大、门槛高

运维门槛非常高，分析问题需要在很多运维指标里抽丝剥茧，如果不是对实时计算引擎了解精深，对运行原理非常熟悉，很难做到有效运维、排查问题。
单点任务开发功能
很多工具只是负责流任务开发和运维，而用户真正要使用的一套数仓服务，还需要用户自己去对接流任务的前后端输入产出
Stream Studio针对现在已有的这些问题，进行了高效的优化：
零代码开发实时任务：全面面向业务维度，提供SQL和DAG两种开发模式，并且支持SQL和DAG互转，在业界尚属首次，非专业人士也能轻松上手。

<div style="text-align:center" align="center">
<img src="/images/实时计算轻松上手，阿里云DataWorks Stream Studio正式发布1.png" align="center" />
</div>
</br>

零学习成本：DAG模式下针对每一种算子进行错误检查以及数据推演，准确辅助用户“手把手”使用DAG进行开发。
所见即所得：为流计算用户提供边开发边调试的功能，解决用户在SQL开发过程中无法调试的痛点
一站式开发：深度打通DataWorks Function Studio，无需依赖任何第三方开发工具，用户可以在线编写UDF，同时支持一键发布到Stream Studio。
丰富的资源库：为用户提供性能卓越的通用UDF，扩充Flink开发边界，避免重复造轮子
低运维成本：将专业的Flink任务运维诊断小白化，支持任务智能故障诊断，提供一键执行任务问题排查的能力，可对任务延迟、任务失败、任务无数据产出等异常场景进行智能分析，并将结果直观的反馈给用户，提示用户修复方案，为流计算用户提供一站式的智能诊断服务体验
