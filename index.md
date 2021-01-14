## 欢迎来到我的个人库

正在搭建中，先来了解了解GitHub吧

## GitHub简介

### 发展历程

2008年4月10日，GitHub正式上线。

2014年1月23日，联合创始人汤姆·普雷斯顿-维尔纳（Tom Preston-Werner）从另一位联合创始人克里斯·万斯特拉斯（Chris Wanstrath）手中接过总裁职位，后者也将接过普雷斯顿-维尔纳留下的CEO位置。

2018年6月4日晚，微软宣布，通过75亿美元的股票交易收购GitHub。 [2] 10月26日，微软以75亿美元收购GitHub交易已完成。10月29日，微软开发者服务副总裁奈特·弗里德曼(Nat Friedman)将成为GitHub的新一任CEO。 [3] 

2020年3月17日，Github宣布收购[npm](https://baike.baidu.com/item/npm/23807941)，GitHub现在已经保证npm将永远免费。 [4] 

## 基本功能

[![img](https://bkimg.cdn.bcebos.com/pic/0dd7912397dda1445da42dedbab7d0a20df486c4?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/Github/10145341/0/0dd7912397dda1445da42dedbab7d0a20df486c4?fr=lemma&ct=single)

[![github](https://bkimg.cdn.bcebos.com/pic/5bafa40f4bfbfbedac5eef1d78f0f736afc31f48?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/Github/10145341/0/72ccb7773e285f49b051b9aa?fr=lemma&ct=single)github

作为开源代码库以及版本控制系统，Github拥有超过900万开发者用户。随着越来越多的应用程序转移到了云上，Github已经成为了管理软件开发以及发现已有代码的首选方法。

如前所述，作为一个分布式的版本控制系统，在Git中并不存在主库这样的概念，每一份[复制](https://baike.baidu.com/item/复制)出的库都可以独立使用，任何两个库之间的不一致之处都可以进行合并。

GitHub可以托管各种git库，并提供一个web界面，但它与外国的[SourceForge](https://baike.baidu.com/item/SourceForge/6562141)、[Google Code](https://baike.baidu.com/item/Google Code)或中国的[coding](https://baike.baidu.com/item/coding/8921246)的服务不同，GitHub的独特卖点在于从另外一个项目进行分支的简易性。为一个项目贡献代码非常简单：首先点击项目站点的“fork”的按钮，然后将代码检出并将修改加入到刚才分出的代码库中，最后通过内建的“pull request”机制向项目负责人申请代码合并。已经有人将GitHub称为代码玩家的MySpace。

在GitHub进行分支就像在[Myspace](https://baike.baidu.com/item/Myspace)（或[Facebook](https://baike.baidu.com/item/Facebook)…）进行交友一样，在社会关系图的节点中不断的连线。

[![img](https://bkimg.cdn.bcebos.com/pic/5366d0160924ab181d75807d34fae6cd7b890b1c?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/Github/10145341/0/5366d0160924ab181d75807d34fae6cd7b890b1c?fr=lemma&ct=single)

GitHub项目本身自然而然的也在GitHub上进行托管，只不过在一个私有的，公共视图不可见的库中。[开源项目](https://baike.baidu.com/item/开源项目)可以免费托管，但私有库则并不如此。Chris Wanstrath，GitHub的开发者之一，肯定了通过付费的私有库来在财务上支持免费库的托管这一计划。

通过与客户的接洽，开发FamSpam，甚至是开发GitHub本身，GitHub的私有库已经被证明了物有所值。任何希望节省时间并希望和团队其它成员一样远离页面频繁转换之苦的人士都会从GitHub中获得他们真正想要的价值。

在GitHub，用户可以十分轻易地找到海量的[开源](https://baike.baidu.com/item/开源/20720669)代码。

## 版本历史

2012年12月24日，GitLab 4.0 RC2 发布，[开源](https://baike.baidu.com/item/开源/20720669)的 Github[克隆](https://baike.baidu.com/item/克隆)。

## 内幕信息

Chris Wanstrath还向记者分享了关于GitHub的一些内幕信息︰

GitHub主要用Rails实现。我们在进行的post-commit集成小应用完全使用Merb编写。我们使用了[Python](https://baike.baidu.com/item/Python/407313)的Pygments来做格式高亮显示，另外，还用了Ara T. Howard's Bj加上一些Ruby[脚本](https://baike.baidu.com/item/脚本)来做我们的[排队系统](https://baike.baidu.com/item/排队系统)。当然，我们用了Ruby Grit库来和Git进行交互。

GitHub已经有了一组引人注目的特性，除了命令式的库[浏览器](https://baike.baidu.com/item/浏览器)和一个项目Wiki，GitHub甚至还包括了一个GitHub gem，以使通过shell方式使用GitHub更为方便。更多的未来特性已经在计划中︰

许多人都希望能有一个条目系统，因此一个简单的条目系统已经在开发中。此外，正如我前面所言，我们尚在进行[RubyGems](https://baike.baidu.com/item/RubyGems)服务器和一些之前留出的post-commit钩子方面的[工作](https://baike.baidu.com/item/工作)。如果你不能或就是不想托管一个你自己的[守护进程](https://baike.baidu.com/item/守护进程)，你可以使用我们所提供的。

我们还在开发一些特性来帮助公司在使用Github时可以停留在sync之上。

最后，我们也在进行[API](https://baike.baidu.com/item/API)发布方面的[工作](https://baike.baidu.com/item/工作)。我们很快就会发布一些只读性的API，随后是一些很强大的“写”集成。你可以使用API将新的事件发布到新闻feed中，发消息和做其他许多很酷的事情。

GitHub尚未设定官方版本的发布日期，不过估计在三月底（GitHub已经上线，但只能通过邀请注册）。更多关于GitHub的信息可以参见GitHub官方网站或GitHub博客。通过GitHub进行代码管理的开源项目列表也已经可以查阅。

## Windows应用

[![GitHubA主界面](https://bkimg.cdn.bcebos.com/pic/21a4462309f790523315f59a07f3d7ca7bcbd508?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/Github/10145341/0/21a4462309f790523315f59a07f3d7ca7bcbd508?fr=lemma&ct=single)GitHubA主界面

GitHub 使用 git 分布式版本控制系统，而 git 最初是 LinusTorvalds 为帮助[Linux](https://baike.baidu.com/item/Linux)开发而创造的，它针对的是 Linux 平台，因此 git 和 Windows 从来不是最好的朋友，因为它一点也不像 [Windows](https://baike.baidu.com/item/Windows)。GitHub 发布了GitHub for Windows，为 Windows 平台开发者提供了一个易于使用的 Git 图形客户端。

GitHub for [Windows](https://baike.baidu.com/item/Windows) 是一个 Metro 风格[应用程序](https://baike.baidu.com/item/应用程序)，[集成](https://baike.baidu.com/item/集成)了自包含版本的 Git，bash 命令行 shell，PowerShell 的 posh-git 扩展。GitHub 为 Windows 用户提供了一个基本的图形前端去处理大部分常用版本控制任务，可以创建版本库，向本地版本库递交补丁，在[本地](https://baike.baidu.com/item/本地)和[远程](https://baike.baidu.com/item/远程)版本库之间同步。[微软](https://baike.baidu.com/item/微软)也通过[CodePlex](https://baike.baidu.com/item/CodePlex)向开发者提供 git 版本控制系统，而 GitHub 创造了一个更具有吸引力的 Windows 版本。

## 配置管理

GitHub上已自动配置的[Mac](https://baike.baidu.com/item/Mac/173)[笔记本电脑](https://baike.baidu.com/item/笔记本电脑)，一个工具，可以转换设置[Linux](https://baike.baidu.com/item/Linux/27050)或Windows机器。

BOXEN是GitHub的自动化工具，设置和配置的Mac笔记本电脑[软件开发](https://baike.baidu.com/item/软件开发)或其他类型的工作，正在使用他们的开发人员，律师，设计师，付货人，等。我们的想法是准备系统以自动方式和作为无差错尽可能用最少的干预工作。根据GitHub上，与一个新的开发机器上，他的Mac系统成立，并准备在30分钟内提交代码。

BOXEN的基础上收集了大量的几十个木偶模块，使设置的各种软件，如卡桑德拉，MongoDB中，Java软件中，[Python](https://baike.baidu.com/item/Python/407313)和[Ruby](https://baike.baidu.com/item/Ruby/11419)开发中，节点，[JS](https://baike.baidu.com/item/JS/10687961)，[nginx](https://baike.baidu.com/item/nginx/3817705)的，[Skype](https://baike.baidu.com/item/Skype)公司，甚至[MINECRAFT](https://baike.baidu.com/item/MINECRAFT)。虽然机器上配备了一个预配置，每个用户都可以调整它的配置应有的作用。

## 融资

[![Github吉祥物Octocat](https://bkimg.cdn.bcebos.com/pic/8b13632762d0f703d0ad4cbe08fa513d2697c5b1?x-bce-process=image/resize,m_lfit,w_220,limit_1)](https://baike.baidu.com/pic/Github/10145341/0/0db2c9ca3ae9e614f21fe7d2?fr=lemma&ct=single)Github吉祥物Octocat

全球最大的社交[编程](https://baike.baidu.com/item/编程)及代码托管网站GitHub以其开创性的新型软件开发方式并且能高效利用有限的资源通过自力更生实现公司盈利和300%的年收入增长成功的吸引知名风投机构Andreessen Horowitz一亿美金的投资。新的资金注入将帮助GitHub平台得到进一步的改进和扩展。

事实上，这不仅对首次接受外部投资的GitHub意义重大，同样对于投资方Andreessen Horowitz而言，这也是其迄今为止进行过的最大一次单笔投资案。作为投资案的一部分，Andreessen Horowitz的[合伙人](https://baike.baidu.com/item/合伙人)Peter Levine将入主GitHub董事会。

根据GitHub官方解释，这笔资金除了用于扩充员工队伍，改进现有服务并移植到[移](https://baike.baidu.com/item/移)动平台之外，还将服务对象从原来的编程爱好者和专业软件开发人员拓展至企业、[设计师](https://baike.baidu.com/item/设计师)、文字[工作](https://baike.baidu.com/item/工作)者等更广泛的客户群体。

GitHub有170万名软件开发人员的忠实用户，他们平均每天更新8万个并新建7千个[软件库](https://baike.baidu.com/item/软件库)。对GitHub网站上托管的总计超过300万个软件库，其联合创始人Chris Wanstrath曾经形象地称其为“[程序员](https://baike.baidu.com/item/程序员)的[维基百科](https://baike.baidu.com/item/维基百科)全书”。
