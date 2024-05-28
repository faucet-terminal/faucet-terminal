
# 1. 概述
Faucet-ATM 是由 OpenBuild 开发者社区发起的一个面向开发者的开源水龙头聚合器，我们希望降低开发者在开发中获取测试网 Token 的门槛，使他们开发体验更加顺畅。

### 问题
因为我们在过往的很多课程/活动中发现开发者会因为测试网 Token 的问题而有一个很糟糕的开发体验：
目前很多项目提供的默认水龙头是面向所有用户的，而开发者对于测试 Token 的需求高于普通用户，所以默认情况下获取的测试 Token 可能不够用
通用性的反女巫策略，导致很多测试网 Token 被羊毛党获取，真实的开发者可能获取不到
搜索引擎搜索出来的很多水龙头并不可用，甚至会出现钓鱼网站情况（新手开发者无法辨别）

### 解决方案
而 Faucet-ATM 则将具有以下特性：
面向开发者，可以针对使用场景(交易/部署等)获取不同推荐数量的测试网 Token
基于 Github 历史记录评分的反女巫策略，更好的筛选真实的开发者
基于 OpenBuild OAuth 数据可以帮助提供测试 Token 的项目获取画像精准的开发者（OAuth 需开发者授权）

目前已经有 **10+**开发者参与到此项目的贡献中，已经支持 **12+** 链，且正在快速拓展中，我们预计在 6 月中旬正式上线一个版本。 <br/>

Faucet-ATM 测试地址：https://faucet-front-end.vercel.app  <br/>

Faucet-ATM Github： https://github.com/Faucet-ATM <br/>

Facuet-ATM Core Contributors: 
![alt text](image-1.png)
![alt text](image-2.png)

# 2. 为什么要参与
我们相信开发者通过参与开源贡献不仅可以提高技术能力，也可以在社区建立更好的个人影
响力，因此我们鼓励开发者参与到开源项目的贡献中，**不用担心自己的能力如何，可以从
最简单的做起，及时不是代码，最最重要的是走出第一步**。推荐大家看看这篇文章：[为
什么要参与到开源社区
中？](https://shardingsphere.apache.org/blog/cn/material/open_source_community/)

当然除了上面提到的开源"礼物"，我们也会提供不同类型的物质激励给到大家，真切的感谢
大家的贡献！

**但请注意，我们不希望大家只是抱着能赚钱的态度来**，
而是觉得参与开源和社区对自己的长期成长是有益的，更是认可这个项目的价值。

## 2.1 悬赏激励
我们会将一些开发任务作为 [Task
Issues](https://github.com/Faucet-ATM/Faucet-ATM/issues)
发布出来，打上 Task 标签 🏷️，感兴趣的小伙伴可以在对应的 issue里评估开发时间（小
时为单位），我们将从里面选出最合适的开发者，并将任务 Assign 给他，**任务完成并通
过 PR 后，我们将按照 $5/时 给于奖励💰**。

每个 Task 拥有 3 个状态：

- recruiting: 表示任务尚未开始，开发者进行评估中
- building: 表示任务已经在开发中
- completed: 表示任务已经完成

> 奖励会在 PR 完成后 3 日之内发放，通过 USDT 发放。
>
> 奖励金额后续可能会根据情况变更，但不影响进行中或已完成的任务。


## 2.2 OpenBuild SBT 激励

对于积极参与贡献（>=40小时）的开发者，我们将发放 OpenBuild SBT，持有 OpenBuild
后续可以享受以下权益：

- OpenBuild 定制周边
- OpenBuild 平台 Bounty / 招聘绿色通道
- 助力打造个人技术影响力
- 开发者成长礼包（高价值教程、技术书籍、各种开发平台的 Credits / License等）
- 潜在的合作伙伴空投
- 其它


# 3. 如何参与贡献
贡献提交流程遵循 Github PR 标准流程，可参考 [如何在 GitHub 提交第一个 pull
request](https://www.freecodecamp.org/chinese/news/how-to-make-your-first-pull-request-on-github)。

同时如果你有任何建议，也欢迎通过 issue 提供我们，请打上 Proposal 标签。