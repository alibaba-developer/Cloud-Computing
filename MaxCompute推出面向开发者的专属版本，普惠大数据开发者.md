MaxCompute推出面向开发者的专属版本，普惠大数据开发者.md

3月20号，阿里云正式对外宣布推出MaxCompute产品的新规格-开发者版。MaxCompute开发者版是阿里云大数据计算服务发布的开发者专属版本。区别于原有的按量付费、按CU预付费规格，开发者版是面向开发者群体的优惠套餐，为开发版项目免费提供500GB的存储空间和每月100元的免费计算费用。

<div style="text-align:center" align="center">
<img src="/images/MaxCompute推出面向开发者的专属版本，普惠大数据开发者1.png" align="center" />
</div>
</br>

开发者版作为MaxCompute的一个售卖规格，除了在计算/存储资源、支持的作业类型方面有所限制，底层的权限体系、操作管理使用方式、配套的生态工具等其他方面与其他规格完全相同。同时，用户可以随时根据需要，将开发者版升级为其他规格，项目中的数据、Dataworks中的作业不会受到影响。
为什么推出开发者版？
普惠大数据计算服务
开发者版是MaxCompute产品面向开发者的一档优惠套餐。开发者版提供了固定额度的免费存储和计算资源，为数据开发者进行大数据的开发学习、产品体验试用、业务构想快速低成本验证提供便利。同时，这是一项长期的、普惠的服务，将有机会让更多的人学习、测试、验证构想。
推广和繁荣MaxCompute生态
通过连接开发者，培养更多的MaxCompute开发人员，满足越来越多的企业对具备MaxCompute开发能力的人才需求，促进MaxCompute以及阿里云大数据生态的健康、繁荣。
开发者版有哪些约束限制？

开发者版有如下约束，使用前请注意：
每个Region仅能创建1个开发者版项目；
开发者版项目可以升级为其他产品规格，但其他产品规格的项目不能转入开发者版项目；
开发者版项目的最大作业并发为5个，单作业最大使用10CU计算资源(1CU为1Core/4GB)；
支持的任务类型：开发者版赠送的计算费用目前仅用于MaxCompute SQL(支持使用UDF)、PyODPS作业任务，暂不支持MapReduce、Spark任务；
作业按照数据扫描量计费，0.15元/GB。赠送的100元相当于每月可免费执行扫描666GB数据的作业量，超出部分将按照0.15元/GB计费；
项目最大500GB存储空间(含临时数据大小)，超出部分不能写入;
连续6个月的开发者版非活跃(连续6月无任何计算作业，不论是存储数据)项目，项目自动释放，项目内资源及数据自动清除；
如需使用交互式分析(Lightning)服务会额外计费；
如何开通、使用？
1.进入阿里云MaxCompute产品首页，单击立即购买。
在购买页面中，切换页面上方的TAB页面为”按量付费”，并选择您需要开通的区域，同时选择规格类型为”开发者版”，点击右侧”立即购买”按钮进行购买开通。

<div style="text-align:center" align="center">
<img src="/images/MaxCompute推出面向开发者的专属版本，普惠大数据开发者2.png" align="center" />
</div>
</br>

2.进入阿里云MaxCompute产品首页，单击管理控制台，进入Dataworks工作空间列表，点击“创建工作空间”

<div style="text-align:center" align="center">
<img src="/images/MaxCompute推出面向开发者的专属版本，普惠大数据开发者3.png" align="center" />
</div>
</br>

选择MaxCompute” 开发者版”计算引擎服务。

<div style="text-align:center" align="center">
<img src="/images/MaxCompute推出面向开发者的专属版本，普惠大数据开发者4.png" align="center" />
</div>
</br>

创建成功后，项目列表中可以查看到有Lite标签的项目，项目创建成功。

<div style="text-align:center" align="center">
<img src="/images/MaxCompute推出面向开发者的专属版本，普惠大数据开发者5.png" align="center" />
</div>
</br>

理使用方式、配套的生态工具等其他方面与其他规格完全相同。请参考MaxCompute文档，使用不同工具对创建的项目进行开发、管理。
