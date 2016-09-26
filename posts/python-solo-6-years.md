# Python solo 六年记


人生几何？Python 当歌！


我的博客“绿萝间”里记载了近六年的学习历程，大都是围绕 Python 而做。没有仔细梳理，信号嘈杂，噪音扰民。看我博客的人不多（ Google analysis 分析数据），估计大都是彩民（彩票数据用 Python 分析的）。记得李敖曾经说，看他早期著作的读者，都是在地下色情书刊买错了书的色情狂，想象那些平日里满眼格子的X，见到李敖的嘻笑怒骂，顿然醍醐灌顶，拍案叫绝。还有法国大革命前，巴黎市民读到的哲学，大多混杂于书商斗篷内的诽谤小说，对集权体制的批判与质疑从此开始。学贯中西的公知已经很多，我的博客没那么高大上，都是烂笔头里磨出的一些杂碎。


一切皆是历史，学习就是读史。罗马政治家西塞罗有句名言：一个不知道自己出生前发生了什么事情的人，等于没有长大。而立之年，不能不学历史。学历史方法很多，读书是系统学习的方法之一，也适合我的个性。梁文道说，读书不是为了让你很安静地逃离这个世界，而是为了让你回到这个世界，换一种方式来认知这个世界，接触这个世界。总之，文以载道，不能不读书。知与行，学与思，皆非一日之功，需小锅慢炖，厚积薄发。在工作和生活中，我一直用 Python，简洁、高效、开源，自带电池，开箱即用，快乐多多。沉舟侧畔，几经风霜，颠覆妄想症的时期已经过去。积跬步，做小事，乐生活。＂成功未必在我，功成其中有我＂，足矣。


一切交流，无论表现形式，皆有翻译（信息编码与解码）。翻译是知识传播的重要途径，形式多样。目前，人肉翻译是中国 ICT 领域的主流娱乐形式之一，机器翻译仍然在“信达雅”的入门阶段，值得期待。如果你大学时学过谭浩强书记的《 C 语言程序设计》，很可能被推荐阅读北大教授翻译的经典，如《计算机程序的构造和解释》、《 C++ 程序设计语言》（比 C 还高级），大多数人在阅读过程中会怀疑自己看不懂中文，在自习室看两页正好睡觉。这样的译本，只能加深对编程的恐惧，在图书馆看作者原著之后，发现原文根本没那么拗口，大师写的基础教程，读者众多，一定是大众读物，通俗易懂的；翻译不当，只会误人子弟，不过教授现在也开始写《数据结构与算法：Python 语言描述》了。偶遇图灵社区网站，才知道原来有这么多道友，可谓热闹非凡。翻译书这事儿，合我胃口。一个人静静的做一件复杂的事情，不用开会，没有需求变更，没有线上线下，和我修电脑，修手机，修自行车，是一个套路。以前，很闲很有时间；现在，班车路上时间很长（平均1小时），有时间将看的书整理成文字。我不是科班出身，语言功底薄弱，因此只能简单译。我认为翻译是一种个性化解释器，掺杂了译者习惯，难免信息损失，如果有时间，可以看原文，更接近作者，但中国人终究还是要用中文解释的，好译本是掌握知识的捷径，而且非常便宜。技术翻译应该简洁、直接、骨感，越精确越复杂越容易陷入小我偏离主题。快刀斩乱麻，直截了当，大家都痛快（作者，译者，读者）。具体手法：文章由句子构成，句子=单词+（上下文）+结构。 map 解决单词意思、 filter 解决上下文关联、 reduce 解决句子结构，遇到坑，直接联系作者解决。


六年工作和学习内容最终总结为五本译作。有幸认识图灵社区的老师们，她们专业、高效、开放的做事风格，令人倾佩。三本书已经由图灵社区出版，其中《 Python 网络数据采集》总结如何获取网络数据，存储数据，十分有趣；《 Python 性能分析与优化》重点介绍代码优化方法，提高 Python 程序性能；《 Python 科学计算基础教程》介绍 Python 的科学计算的生态环境，有一章专门介绍 Python 在科学与工程领域的应用案例，让人大开眼界。这三本书构成了 Python 数据分析的基础环境：基于数据库，获取数据，优化性能，科学分析。还缺一环，做成产品，也是我未来继续努力的方向。在学习 Python 的过程中遇到的坑不少，不过前人都已踩过，这些书给了我很多帮助。有段时间，我陷入了性能优化的泥潭，总怀疑性能不佳要优化。我家莉姐一语点破，其实能解决问题就好，优化也要花时间。我家莉姐总能一语中的，吾之大幸。 Python 其实并不慢，Guido 老爹说过。


另外两本书在博客中，纯属自娱自乐。在数据分析方面，尤其感兴趣机器学习，译有《精通 Scikit-learn 机器学习》，介绍了经典的回归，聚类，分类，降维学习方法，用里面的方法协助一位朋友完成了论文，很有成就感。未完成的《 Scikit-learn Machine Learning Cookbook 》，对 scikit-learn 和 theano 的总结，同样很有趣（一本更赞的机器学习书正在翻译中）。在 app 开发方面，翻译有《 Kivy 指南》，Kivy是一款多平台 app 开发框架，在国内没什么声音，可能是 JavasScript 太火，也可能是网络不太方便。 Kivy 跨平台能力强，支持 Windows， Mac OS X， Linux， Android， iOS， WP 系统应用开发，可以借助Python丰富的模块扩展应用功能。另外还有 Kivy Launcher，支持即时代码运行，把代码复制到手机的 kivy 目录下即可在手机上运行 app 。另外，统计学方面翻译有 Jake VanderPlas 的博文《频率主义与贝叶斯主义》四篇，用 Python 对比统计方法，适合教学。在 Python 自动化方面，翻译了 PyAutoGUI 程序包的中文文档，可以控制鼠标、键盘事件。 PyAutoGUI 接口简洁，绝对有潜力成为 GUI（ Autocad， PS ）自动化神器。另外， Selenium 也支持的网页交互功能，在《 Python 网络数据采集》中有介绍。


用 Python 做数据分析的初衷是分析彩票（双色球与大乐透），也是我博客的主要内容，以前用 matlab，装一次费老大劲，速度也比较慢，在手机上没法儿运行，2010年整理维基百科的数据时，遇到了 Numpy， matlab 基本可以无缝过渡到 Python 。复兴数十步，豁然开朗。 Python 的世界更精彩，围绕数据库，前面有高效灵活的数据采集工具（ requests， lxml， aiohttp ），中间有交互式的数据分析与可视化工具（ pandas， scikit-learn， theano， matplotlib， bokeh， seaborn ），后面有简便快捷 webapp 开发框架（ flask， django ）， awesome Python 。博客原来是 WordPress，现在用 Python 的 Nikola 静态页面生成框架，放在 github 上。彩票分析方法在网上都是描述性统计，我用 pandas+scikit-learn，红球样本数据量不大（C 33，6即1107568），神经网络方法简单、随机。如果有100万用户，一人一注，肯定有人中大奖。如果你真中了，记得给我捐点首付哈。如有雷同，纯属巧合。彩票不是随机事件，如果是真随机，停售后立即开奖好了，为什么在20点停售后，到21:15才开奖？因为这段时间里，计算机要枚举所有中奖可能（红球110758，蓝球16，即17721088）与当期销售的上亿订单中奖情况，大矩阵做 MapReduce，计算奖金总数，给用出奖最小的6+1组合，然后让机器把球转出来，最后由冷静的主持人和公证人员秀一下，公正公平公开，您中奖了吗？买彩票也是一种修行，参悟乌合之众的共性，找到与众不同的那注球。未来不可预测，信号与噪声难以识别，《信号与噪声》这本书中文版翻译得挺好，推荐。


有时间读书，是一件幸福的事。几年在国企，确实有时间，可以把以前的基础课程重学一遍，再读经典，开卷有益。以前在学校图书馆看书，常常整天整天的呆着图书馆，后来莉姐也到图书馆工作了，读书方便。引以为傲的，是自己还是读书人，修炼的终极目标依然是扫地僧，有一门手艺，博览群书。重看了 C， C++， java，数据结构与算法，SQL，操作系统和编译原理，还挑战过七周七语言。参与过 swift 中文文档的翻译，梁杰在 github 组织众包翻译，让人印象深刻，是中国程序员团结协作，面向新知识，面向世界，面向开源的典范。看的最多的还是 Python，简洁、优雅、高效，丰富的程序库，非常适合开发网络应用，做数据采集与分析，也适合编程教学。现在国外许多大学已经将 Python 作为编程第一课了，相信未来国内也会如此。文科生不需要指针，也可以快乐的编程。更加重要的是培养小朋友们编程解决问题的能力。如果在工作学习中，需要大量的重复，甚至在100个网页中 Ctrl+C 和 Ctrl+V 任务，那绝对是教育的缺失。既然智能硬件已如此便宜，人人都可以用上智能手机，那么完全可以改变教学方法，网络教学在线互动，让小朋友在游戏互动中学习公式，定理，观察物理化学现象，会大大激发学习热情。兴趣永远是最好的老师。


用编程解决问题是提高工作效率的有效手段。编程这种思维方式，可以快速解决重复问题。人生就是一个循环选择（ for...if...else... ）的过程，而计算机的本质功能就是通过程序让重复变得简单，可靠，持续。科学，工程与商业领域都在不断努力让计算机替代人类做重复的事情，数据的采集与计算成本越来越低，各行各业的数据科学都在快速发展，问题的数据边界渐渐清晰。我非计算机科班出身，专业是物流与工业工程，物流是工业工程的分支，属于科学管理范畴，涉及面广，是一门杂学。科学管理的根源，在于社会分工体系成熟之后，重复劳动现象凸显，一个人的操作时间节省1%，企业都会节省巨大的成本。物流、工业工程与计算机科学以及其他科学的基本任务一致，即努力解决时空稀缺性问题。其流程复杂，节点众多，对数据有迫切需求。随着自动化技术的进步，业务量的集中，大型物流园区兴起，倒逼整个行业从劳动密集型转向技术密集型转变。目前的物流系统仅仅处于聚合数据阶段，标记流程节点，关于作业效率优化，如库存控制，拣选路径，排程系统，配送路由问题，都需要面对具体业务，做深入挖掘，寻找优化方案，这是现代物流应该做的事情。


不管怎么耍一天只有24小时。干什么都不会改变一天的长度，时间一天天的过去，我还是在数据的海洋里寻觅。 Python 就是一支长篙，让我可以向青草更深处漫溯，希望有一天我也可以满载星辉，在星辉斑斓里放歌，希望眼前的苟且与诗和远方能够合理并发（ Concurrency ）。回顾六年青葱岁月，时间都“浪费”在 Python 上了（吴晓波所谓美好事物），工作之余，除了看房子的周末、必须回家过年的假期，几乎所有周末和节日都用在 Python 上，做小项目，翻译，看书，越来越宅。最近也增加了偶尔周末参加一些交流会，每次都有收获， infoQ 有很多有趣的分享，免费哒。听人分享踩过的坑，总结别人的经验，反思自己的错误，如切如磋，如琢如磨。还记得2004年9月大学入学第一天，长辈教诲＂强健体魄，弥补不足，张扬个性＂，依然在耳。吾辈使命应循中外圣贤之心，维普世价值之本，修身齐家，循序渐进，多么励志的人间喜剧。


然而，处在乡土中国与互联网+的并行（ Parallel ）期，激荡三十年的历史情景一次次重演，一切都山呼海啸般，有时让人措手不及，甚至恍惚间又看到百年前的跌荡岁月。今年流传最广的词是“套路”。看郎咸平的《中国经济的旧制度与新常态》，里面总结的一堆的政府套路，今年再次上演，广义货币 M2 在2009年49万亿，2013年110万亿，2016年8月151万亿，三倍。母校120建校周年，贡献之一是现在长河湾房价12万一平米，很多老师都买啦。同学聚会，聊起班主任，仍然是副教授，why？不差钱，长河湾有一套房啊。读书？科研？深造？莫言2012年用诺贝尔文学奖（750万RMB）买的房子价格也快 double 了。瞧！四年时间又挣了个The Nobel Estate Prize，有套房，不用那么辛苦的。屠呦呦教授2015年为中国科学界获得了至高荣誉，获得的诺贝尔生理学奖奖金（不到400万RMB），去年年底能在牡丹园能买60平米，今年9月只能买50平米了。当下，买房致富，创业返贫。下一个中国诺贝尔奖，吾辈能见到吗？