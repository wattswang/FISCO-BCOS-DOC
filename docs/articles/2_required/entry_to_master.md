# 排除万难，从入门到精通区块链

作者：张开翔｜FISCO BCOS 首席架构师

目前越来越多的人已经进入或准备进入区块链领域，过程中不免抱着各样的疑虑和问题。想起自己之前用几年时间，从“略懂”区块链到all in，同样也经历着类似的心路历程，这个领域确实是有一些门槛的，但万事开头难，摸索路上还远不止八十一难，这里梳理几个概要性的困难和感悟，谨作分享。

## 方向之难

我是谁”、“我在哪”、“我要去哪儿”，一切都源于这么一个哲学三问。区块链是什么？区块链究竟能做什么？为什么区块链这么火？不用区块链行不行？这些问题都充满了终极拷问的意味。

其实很难彻底回答这些问题，因为，并没有标准答案。所有创新的前沿的事物大抵如此，在质疑和动荡中发展，在黑暗和荒芜中摸索，精华和糟粕齐飞，绿洲与韭菜一色，直到引爆点迸发。如果因为充满疑虑而左右摇摆，或者裹足不前，那么在从事相关工作研究的过程，体验会很糟糕，结果也不会好。

分享一点个人体会：区块链领域从一开始就吸引了全世界无数的聪明人，不乏极客、学者、大师, 他们进行了大量的技术和社会实践。这个领域蕴含着数学、计算机、密码学、博弈论、经济学、社会学等学科的精华，这是一个智力飞扬、思想激荡的世界。目前，整个行业更是获得前所未有的关注，包括政府、各行业巨头都在关注，大量注意力和资源持续涌入，区块链迎来了“最好的时节”。

在持续进化、结构多元的现代社会里，分布式商业的理念已经成为现实。人和人、机构和机构之间会产生更多的联系和协作，信息和价值在新型网络模式中快速流转，作为分布式技术代表之一的区块链，很有机会成为新一代基础设施和创新的据点。

所以，方向并不是问题。即使你不把区块链当做“信仰”，只看这个充满魅力的技术本身，以及区块链与实体经济深度融合的机遇，还是可以给我们带来信心。

## 概念之难

在哲学三问中，“区块链是什么”是最晦涩的问题，区块、交易、账户、共识、智能合约、双花...这都是什么？！我自己在刚接触区块链时，也有一种被颠覆了认知的感觉。有一些介绍区块链的文章，往往着眼在区块链的社会和经济效能，从价值理念讲起，这些固然是必要的，但俗话说“科学要定性更要定量”，作为工程技术人员，我们更应该关注的是，区块链里的知识点、基本原理，进而澄清术语、把握架构、处理逻辑和程序流程。

前面提到，区块链蕴含着大量学科的精华，同时，行业也有一句俗语：“**区块链并没有发明什么新技术，都是成熟技术的组合**”。

- 这些成熟的技术包括数据结构，诸如链表、树、图、过滤器等，是大学里数据结构的基础知识；
- 基础密码学，包括HASH和对称非对称加密、数字签名等等，已经是几十年的经典技术，而事关隐私保护等领域的新一代密码学，更给密码学专业人士开拓了一片广阔的发挥空间；
- 分布式网络和系统这门学科本身包罗万象，覆盖了海量服务的知识范畴，许多从事过海量互联网服务技术的同学，都会对区块链的P2P网络和共识算法、并行计算模型、事务性一致性原理如数家珍；
- 博弈论和激励相容是协作方面的知识点，是“区块链思维”的重要组成部分，工科学生可能需要翻翻书，社科经管背景的同学估计会似曾相识吧；
- 至于智能合约，比如solidity语言、WebAssembly等，很少听说吗？其实这些语言以及编程模式学习曲线未必有javascript高，有几年程序基础的同学基本上一周就可以上手，写出顺溜的智能合约来。

区块链让人觉得认知困难，是因为它就像个“筐”，什么都可以往里装，牵涉的技术繁杂，组合方式却和常规技术套路不同。所以学习者一定程度上先要放空自己，避免让自己在原有领域的思维定势干扰了学习，在丰富自己知识面的同时，接受区块链的“群体共识”、“防止篡改”、“不可否认”、“高度一致性”等神奇逻辑，然后潜心进去看每一个独立的概念时，并不会觉得高不可攀。

突破概念之难的要点，是排除来自各种渠道的噪声，有些信息似是而非，或者是各说各话，把同一件事用N种话术讲出来，混淆了定义，模糊了本质，于事无补的同时还带来更多疑问。靠谱的方法是着重阅读权威媒体的正规内容，关注一些主流区块链项目的文档库，认真地、全面地通读技术文档，然后找一个自己感兴趣的领域（如共识算法），结合自身经验知识进行对照研究。

同时，也可以加入活跃的开源社区和技术圈子，和有经验的人多讨论，勇于把问题抛出来，挨个术语，挨个流程讨论透彻。我们在研究区块链的初期，团队经常就一个概念的定义咬文嚼字地争论很久，最后愉快地达成共识时，大家都觉得神清气爽。

在概念阶段，切忌求全责备，不要变成资料收集机，一口吃不成胖子，基于靠谱的学习资料，澄清基本概念，在实践中去验证和发掘新的概念，建立发现问题、解决问题的方法论，慢慢就能举一反三，说不定某一天就能醍醐灌顶了。

## 上手之难

好吧，哲学和概念问题终于不会阻碍我们学习的脚步了，那么怎么继续“二十一天入门到精通”之路。作为技术人员，遇到新的技术平台、软件体系、编程语言...那当然是：“不要怂，就是干！”

几年前，我们刚开始研究区块链时，通读过几个国外流行的开源区块链项目代码，并搭建测试网进行试验剖析，分析如何让这些平台能在复杂的金融业务上用起来。当时有个困惑，如果直接基于底层平台开发应用，当需要实现更多功能时，是不是就得直接修改底层平台代码。

而当看到“智能合约”这个东西时，思路一下就打开了：采用智能合约作为中间层，在合约里编写业务逻辑，并为调用者定义清晰的功能接口，这样，业务可以很好和底层解耦，而底层平台则定位成强大的引擎，通过架构的解耦，使得整个开发过程变得清晰合理、轻松愉快，感觉就像是从“C/S”架构到“B/S”架构的演变，多年互联网海量服务开发的手感又回来了。

另外，我们觉得当时的开源项目主要是公链形态，在安全可控以及合规方面考虑没有那么周全，并不适合金融场景使用。

那么，没有趁手的平台，就想办法造一个。从此，深耕底层技术、迭代应用验证的漫漫之路开启了。这个过程也和开源社区一众伙伴建立了紧密的合作，正是“来自开源并回馈开源”，经过开源工作组几年的打磨，FISCO BCOS已经是一个全面开源、安全可控、高速稳定、易用友好的金融级底层技术平台，面向金融和广大的产业领域，提供丰富的功能和各种操作工具。丰富全面的文档和便捷易用的体验，可以帮助开发者从快速入门到精通，整体的技术门槛和开发成本变得前所未有的低。

有了基础的底层平台之后，下载、安装、配置、运行、阅读使用手册、写hello world和业务应用、Debug和分析日志...都是step by step的工作了。

我们目标是，用户在几分钟内，用一键安装、docker、云服务等方式顺畅无错地搭建出自己的区块链网络，在一周内通过学习就可以写出完整的智能合约，基于支持多款语言的SDK（Java、Node.js、Python、Go...还在增补中）实现业务逻辑，将业务发布上线，保持稳定运行。

为了这个目标，我们一直在持续优化使用文档、开发手册，以及部署和运维工具。众所周知，“码农”们喜欢写代码，而写注释和文档就比较痛苦了，为了向社区交出一份漂亮的作业，大家倾尽了有生以来的语文水平，一次又一次修订，硬是写出了数十万字的文档库。

同时，开源社区推出了一系列的线下线上沙龙、培训,用社区的方式，进行广泛交流和技术支持。在多次的现场学习和黑客松大赛中，我们欣喜地看到,开发者用两三天时间，就能基于FISCO BCOS实现他们精巧的项目设计，而且有开发者将其中和开源项目相关的优化贡献到Github上。

到这个程度，即使是对没有区块链研发经验的开发人员,快速上手已经没有什么问题，即便区块链底层还像一个黑盒子有待探索，但就像在电脑上安装App、使用mysql、tomcat之类的软件一样，足可以用起来，感受区块链的魅力了。

## 深入之难

对技术人员来说，探索技术的内涵永无止境：参与到区块链底层开发，实现大型的区块链应用，为区块链生态增加更多有用的特性、工具，对现有功能性能进行极致优化，这些都是进入“深水区”的路线。

之前提到，区块链系统知识点和框架涉猎广泛，无论是知识面还是深度都有相当的规模。量化一下的话，可以套用一万小时理论：如果每天学习工作8-10小时，一个月足以上手，一年可得小成，两年轻车熟路，三年可成老司机...但老司机要行的前路依旧漫漫。我们希望通过持续的科普、交流、实践，去缩短这个过程，但毕竟学习就是一种最基本的“工作量证明”，并没有什么其他捷径。

学习方法，首先是大量的泛读，每天早上一睁眼到晚上，都可以看到持续更新的行业新闻、公众号文章、技术大咖博客、邮件组讨论组、开源项目......阅读的过程或许会遇到不同观点的碰撞，需要去伪存真，在心态开放的同时，也保持自己的立场和方向。

然后是深入的精读，先选定一两个感兴趣的方向，研读诸如密码学、分布式理论等方面的一些经典论文。FISCO BCOS的核心共识算法使用的PBFT和RAFT算法，是基于对原版论文的研究解读，有了深入的理解再去做的实现和优化。区块链里广泛用到密码学原理，场景和逻辑多变，其原理有可能来自某一篇“顶会”论文。精读深度原理剖析文章和学术论文，基于扎实的理论，才能根据自己的需要进行发挥，创造性地解决工程问题。

其实我们的在线文档已经有数十万字的规模，各种信息应有尽有，技术社区会定期对热点知识进行解读，只要读者认真阅读在线技术文档，接受公众号的体贴推送，并动手进行更多的实践，随着时间推移，必能深度理解区块链的技术原理，参透架构设计的来龙去脉，建立起巩固的知识体系。

最后，精读的对象，自然也包括源代码，毕竟“Talk is cheap, show me the code”，区块链开源项目代码大多是几万到几十万行的级别，阅读代码是达成庖丁解牛水准最直接的方法。在研究区块链的历程里，我们有许多长夜漫漫review代码的日子，当读到一眯眼，眼前都是代码在飞，各种接口和对象翩翩起舞，既优雅又有规律，脉络清晰，那种愉悦简直难以名状。这种体验，之前有，之后也会继续有。

如果已经深入到了这个程度，领域门槛已经基本越过，考验的就是开发者的脑力和体力了吧。 

## 持续之难

在过去几年因为鱼目混珠、政策法规、技术障碍等等一系列情况，区块链会遇到市场波动、应用落地延缓等挑战。未来如何，虽然没有预言家告诉我们，但现在大家已经看到了趋势。这又回到了第一个问题：“方向”，明确清晰的方向，不但能回答“要不要进入这个领域”，同样也能回答“要不要坚持下去”。我们一直在分布式商业模式中开拓场景，为公众提供优质的服务，为行业提供完备和好用的开源技术，这是从开始到现在，乃至未来坚持的方向，从未改变。

再具体一点，如果我们已经用区块链部署上线了业务系统，那么影响系统生命周期和持续性的问题还有：可运维性、可升级性、兼容性、数据容量、业务性能容量等等。

多次和社区朋友交流的过程，他们会提起一些问题，例如，新版本是否能兼容旧版本？随着业务发展，越来越多的数据是否可以迁移和重用？这都是用户的真实声音。我们所构建的平台，一定要走可持续发展的路线，重视软件体系的兼容性，有合理的版本发布节奏，以及周全的数据迁移维护策略，可以更好地保护社区用户利益，也使得用户愿意长期与社区共同发展。

另外，区块链领域还在高速发展中，各种新技术、新思潮、新模式、新政策还在层出不穷，这个领域集结了世界上大量的聪明人，他们不但聪明而且努力，从来都不闲着。于是在这个领域工作，每天都会有新的知识、新的刺激，这一方面是一种幸运，另一方面，也会让人极其焦虑。

如何去消化这么海量的信息，如何去探索和掌握前沿的知识，如何更好满足高速发展带来的用户需求和新挑战，如何做出卓有成效的突破性创新，这真的是一个创新和焦虑并存的世界，让人欲罢不能。

作为从业者，必须持续进行大量阅读，在各种信息流里过滤和吸收，不断地归纳/总结/思考/开拓；每一个需求和用户ISSUE反馈都是一个小目标，每发布一个新版本都会是下一个版本的新起点。区块链的世界和其他技术领域没有什么不同，都必须保持敏锐和奔跑，保持好奇和谦逊，不断学习和实践，修订短板寻求突破，将成果分享给社区。正如系统需要极大的弹性，人也需要极大的韧性。共勉。

#### 推荐链接

[《亲朋好友都能看懂的区块链》](https://mp.weixin.qq.com/s?__biz=MzA3MTI5Njg4Mw==&mid=2247485270&idx=1&sn=5a4a5990cd3229df132da6ecc6cd241d&chksm=9f2ef54aa8597c5cfa558ceb65283488fff972bab6cebcb1cf0c2e8155695f628f6958c7fd58&token=705851025&lang=zh_CN#rd)

[FISCO BCOS开源项目github地址](https://www.github.com/fisco-bcos)

[关键概念阅读](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/tutorial/key_concepts.html)

[《FISCO BCOS零基础入门，五步轻松构建应用》](https://mp.weixin.qq.com/s?__biz=MzA3MTI5Njg4Mw==&mid=2247485305&idx=1&sn=5a8dc012880aac6f5cd3dacd7db9f1d9&chksm=9f2ef565a8597c73b87fd248c41d1a5b9b0e6a6c6c527baf873498e351e3cb532b77eda9377a&token=705851025&lang=zh_CN#rd)

[深入区块链底层平台FISCO BCOS](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/design/index.html)