# 阿里云云盾IDaaS应用身份服务正式发布，为用户提供5A一体化身份管理平台.md

<div style="text-align:center" align="center">
<img src="/images/阿里云云盾IDaaS应用身份服务正式发布，为用户提供5A一体化身份管理平台1.png" align="center" />
</div>
</br>

随着应用上云和移动互联网的兴起，企业对身份的认证和管理也必须要适配各种复杂的、混合的IT环境。阿里云云盾IDaaS（Identity as a Service）应用身份服务通过集中式的身份管理服务，为用户提供5A一体化身份管理平台，帮助用户解决跨云跨域的企业应用访问及管理难题。

<b>阿里云IDaaS是什么？</b>

IDaaS，是Identity as a Service的缩写，它是一个基于云计算和微服务架构的集中式身份管理服务，首先它会赋予用户一个唯一的身份账号，只要这个账号成功通过身份认证，那么用户就可以自由访问所有被授权的，跨云跨域的任何企业应用，包括部署在公有云、私有云以及企业本地机房中的。
阿里云IDaaS围绕统一的身份账号，为用户构建了集5项主要能力为一体的统一身份平台, 并按照英文缩写简称为5A一体化平台。

阿里云IDaaS所提供的5A一体化平台是什么?
5A一体化平台，包括了统一身份账户（Account）、统一身份认证（Authentication）、集中授权（Authorization）、应用管理（Application）、以及全局透明审计（Audit）五项能力。
其中，统一账户（Account）为企业信息化建设提供唯一的用户身份数据，以及集中的账户生命周期管理；统一认证（Authentication）负责安全的验证用户身份，可集中配置多因子认证，并集成第三方认证源；集中授权（Authorization）可根据用户所在部门或者角色授权其可访问的范围，做到一次配置，全局生效；应用管理（Application）通过集中管理企业的私有云和公有云应用、移动应用甚至数字设备，实现单点登录，并为每个用户提供企业应用门户；透明审计（Audit）详细记录了用户所有行为及管理员操作，让管理者随时掌握企业数字资产的使用情况。

<b>阿里云IDaaS可以帮助企业解决什么？</b>

1、把身份作为IT的公用基础数据，解决员工账户信息孤岛、管理遗漏问题
现代企业的数字化管理，必须由多个应用系统互相配合来完成，而由不同团队或供应商开发的系统又很容易成为一个个信息孤岛，带来员工入职、转岗时流程繁杂耗时，离职后账户权限回收不彻底等问题，这些问题正困扰着越来越多的企业管理者。实现统一的身份账户不仅能为管理者解决以上问题，同时也可使应用的开发者从账户管理的包袱中解脱出来，从而更专注于业务本身。
2、密码的脆弱性问题
虽然每个应用系统都声称自己会保护好用户密码，并有复杂度要求，强制定期修改等安全手段，但从用户角度来看，记住多个不同的密码并保证定期更新，几乎是不个可完成的任务，所以事实上大多数用户会在所有系统上使用相同的密码，这就导致了一点失守全面沦陷的局面；同时用户会在密码中加入一些规律以便于记忆，这也使得撞库破解成为攻击者最常用的手段之一。而IDaaS统一身份认证可以通过多种非密码方式来认证用户，如每30s一变化的动态令牌，人脸，指纹等生物特征等；在认证通过后，再使用非对称加密令牌向应用传递已认证的用户身份，使用户无需再次认证即可访问应用，在确保安全同时带来了工作效率提升。
3、分散的授权和审计问题
在多个应用系统中管理访问授权经常是个麻烦事，这使得管理员对权限的分发变得小心翼翼且流程繁多；而整合不同应用的登录日志更是难以实现，这让管理者对整个企业的数字资产使用情况如同雾里看花，甚至需要额外的研发投入才能做到。有了IDaaS的统一授权管理，管理员可以随时对应用访问权限进行多视角的授权和查看，真正做到一次配置，全局生效。同时IDaaS汇集了员工的入职、转岗、离职、登录登出、企业应用访问等一系列重要审计日志，可以提供多维度的展示报表和快速查询功能，为企业的精细化管理提供可操作的支持。
4、满足多项国家等保合规，以及上市公司内审合规的要求
例如2FA解决方案，在统一认证时，通过组合两种不同识别因素对用户身份进行双重鉴别，帮助企业满足其所在行业等保2.0中对密码二次鉴别的合规要求。通过账号的实名化，彻底解决账号审计的要求。

<b>阿里云IDaaS的产品的技术优势是什么？</b>

以SaaS服务方式提供，企业不需要自身来运维，极大的降低了运维成本。
支持多种账户源，如AD、LDAP、标准SCIM API等，可快速导入企业既有账户。
预集成了阿里云RAM以及业界常用的SaaS服务，无需过多配置即能开通使用。
支持多种认证协议，包括SAML、OIDC、OAuth、CAS等所有标准单点登录协议。
对于非标准应用，也支持采用API、SDK、密码代填的方式进行快速集成。
阿里云IDaaS改善了什么？
对于企业员工来说，IDaaS提供了统一的信息系统入口，单点登录的便捷性，另外集中式的办公门户模式比分散式的体验更好；对于IT管理员来说，IDaaS提供了对全体账号及权限进行集中管理的平台；对于开发者来说，IDaaS平台提供了开放功能及API，可以复用平台的账户管理和认证能力；对企业主来说，IDaaS还支撑了企业生态化的发展，轻松的将供应商、合作伙伴、客户纳入到统一的身份体系中，打通业务发展链的上下游。
