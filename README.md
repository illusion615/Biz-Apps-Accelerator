# 商业应用加速器（#Biz Apps Accelerator#）

> **免责申明**
> 所有加速器内容均来自日常售前方案所归纳出来的常见场景。已经进行了脱敏脱毛处理，无行业特性，无客户机密，请随意取用。

基于Microsoft Power Platform的一系列应用加速器。

在企业中存在很多长尾应用，也可以认为都是些鸡肋应用，所谓立项嫌贵，不做又累。但正是这些看似渺小却又茫茫然遍布企业的业务需求，构成了传统数字化转型“最后一公里"涵待解决的问题。

服用低代码平台的药效之一，就是用来快速将这些日常沉没在Excel和SharePoint，甚至笔记本记事贴上的应用转变为真正数字化的“业务应用"。所谓的快速，如果不能在一周产出第一个可供用户使用的版本，那就是服用方式不对。当然，并非所有人都生而为“专家"，也不是所有人知道“低代码开发"与“开发"的区别。所以，这里的“商业应用加速器"的初衷就是希望可以给出一个示范，或者是一个参考，或者是一个起点。来帮助你快速的为你的客户将上周告诉你的一个想法变成一个看得到摸得着的应用。

# 关于作者

微软中国商务应用产品事业部产品解决方案专家，在行业浸淫二十数载，自认为走过的山路十八弯，对山里沟里的事事物物还是具备一些“略懂“的见解。擅长听君一席话，助君信息化。

# 如何使用这些项目

谁适合使用这些应用加速器？

* 如果你是合作伙伴，可以以此作为架构参考，或者基于此构建更加垂直化的行业解决方案，最好可以减少第一期项目的服务费用，还利于“客户"；
* 如果你是客户，我鼓励你将其作为企业内部试行低代码平台的起步项目，希望可以帮助你省时省力，让你的第一个项目更容易。也希望可以因此帮助你开拓新的职场机会；

# 技能要求

作为低代码开发人员并不需要太过于专业的IT技能，但具备程序化的设计思想和程序员思考问题的方式可以帮助你更好的理解方案架构以及进行必要的修改。

此外，这里假设你已经具备如下能力。如果不会也不要紧，我会在后面给出微软官方的培训课程站点，你所需要的就是按部就班的去阅读并实践即可。

如果你需要安装、部署并运行该加速器方案，你需要具备如下技能：

* 在Power Platform中创建环境（可用培训：[Create and manage environments in Microsoft Dataverse - Learn | Microsoft Docs](https://docs.microsoft.com/zh-cn/learn/modules/create-manage-environments/)）
* 导入并发布解决方案（可用培训：[Manage solutions in Power Apps and Power Automate - Learn | Microsoft Docs](https://docs.microsoft.com/zh-cn/learn/modules/manage-solutions-power-automate/)）
* 配置安全角色（可用培训：[Manage permissions and administration for Microsoft Dataverse - Learn | Microsoft Docs](https://docs.microsoft.com/zh-cn/learn/paths/manage-permissions-administration-common-data-service/)）

如果你需要改写、扩展该加速器方案，则需要具备如下技能：

* Dataverse模型设计（可用培训：[Get started using Microsoft Dataverse - Learn | Microsoft Docs](https://docs.microsoft.com/zh-cn/learn/paths/get-started-cds/)）
* Power Apps开发
  * Model Driven App（可用培训：[Create a model-driven application in Power Apps - Learn | Microsoft Docs](https://docs.microsoft.com/zh-cn/learn/paths/create-app-models-business-processes/)）
  * Canvas App（可用培训：[Create a canvas app in Power Apps - Learn | Microsoft Docs](https://docs.microsoft.com/zh-cn/learn/paths/create-powerapps/)）
* Power Automate开发（[Automate a business process using Power Automate - Learn | Microsoft Docs](https://docs.microsoft.com/zh-cn/learn/paths/automate-process-power-automate/)）

# 注意事项

* **正确的期待** - 我知道很多人都期待一个拿来就用的东西。但如果真有这样的东西，那现在的IT行业应该早就秋风凋零，因为你所能想到的点子肯定都有前人想到了。所幸现实中并没这样一种“银弹"可以解决所有麻烦，所以这个行业才无时无刻不在进行着方方面面的创新。这也佐证工具是需要与时代共进的。因此抱着拥抱变化的态度比期望一劳永逸更加不会让你失望。
* **修改不如重造** - 是否觉得改别人的东西似乎比自己从头造一个更花时间？不要怀疑，这样的事情在低代码时代总在发生。当技术门槛大大降低的时候，也许你需要的只是别人应用中带给你的“点子"，道路千万条，何必重蹈前人路？

# 绝世武功的……目录

这里列出了一些常见业务场景的列表，后续会逐渐更新，包括可供下载的Solution方案包以及相关演示材料。

千里之行始于足下，路还是要一步一步来。敬请耐心期待，同时也欢迎留言或提出建议。

## #1 基于状态机的可配置任务流转方案

说中文就是：公文流转。这是国内大量集团客户、国有企业、政府机构所常见的任务流转机制。其特点是：没有预先约定的流程，只有流程流转的规则。因此基于该规则可以实现任意流程的设计。是不是很自描述的感觉？

### 背景故事

集团公司发文给部门及下属分公司，下属公司收文并分派正确人员处理，期间可以选择转发其他部门或下属子公司。当所有审批完成后汇总上报上级公司。

![1651766536763.png](image/README/1651766536763.png)

### 方案特点

* 支持无限层级下发汇总上报
* 支持一人多岗

### 方案详情

[跳转查看方案详情](State-Machine-Task-Assignment-Solution/README.md)

### 更新日志

## #2 培训/活动注册管理

Coming soon...

## #3 资产领用、维护及管理解决方案

Coming soon...
