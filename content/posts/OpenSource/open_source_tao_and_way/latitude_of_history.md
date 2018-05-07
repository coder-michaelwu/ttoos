---
categories:
- 开源
- 感悟
date: 2018-05-05T15:12:24+08:00
description: "2018年4月，开源被无故多事，ZTE被美国政府禁止引出的各种芯片、自主、闭源等各种理论甚嚣尘上，像历史上很多事情一样，真相往往没有被发现和关注。开源之道沉默了很久，试图通过某种表达方式，阐述清楚其中的来龙去脉。情感是最容易做到的，因为这是人类的本能，而能够理性的思考并行动，从来都是少数人做的事情。谨以此文献给那些实际的行动派。"
keywords:
- Open Source
- Culture
- Reading
- News
tags:
- 开源之道
- 本土乱象
title: "历史的维度——开源、拿来主义与自主可控的荒诞"
url: ""
---

> 历史是治病的良方。
>          —— 丹尼尔·J·布尔斯廷 《发现者》

## 引子

硅谷著名投资人 Paul Graham，当然是影响几代程序员的散文集《黑客与画家》的作者，写过一篇散文叫做“时空差异”，意思就是说我们可以回顾过去，将过去的观念和现在的观念diff一下，当然也可以diff这个世界上不同的地方和文化，进而验证自己的想法。而这大概就是每天都会有人通过社交媒体同步华尔街、硅谷、湾区甚至是GitHub到本土的最佳注解。

在纬度发明之前，人类是很早就发现了经度并掌握了它的测量方法的，但是纬度却花了很长的时间，而之后经历了海洋时代，乃至全球化的时代，则花了更长的时间。所谓的时间的纬度，就是人们对于同一时间正在整个世界上发生的许多事情的一种感觉。这更是一项复杂的多得的发现，或许可以说，只有进入了互联网时代才实现的。不过我们首先要确定的一件事情是时间的同步。

几千年来，人们记录其所在地各种事件的发生时间，用的是国王在位的年份，或者用某种具有地方意义的其它事实作为依据。这就是我们读中国古代史的时候，比如《史记》之类的，很难和公元多少年对上号的主要原因所在，我们现在所使用的公元纪年法，其实是在1751年英国人切斯特菲尔德伯爵建议采用的新历——“格列高利历”，之后欧洲逐步采用，也逐步的被世界所用，在中国，一直以来用的是一种以在位君主年号与太阳历相结合的复杂制度，直到1911年成立共和国为止。这时中国终于采用了太阳历，但年份仍从共和国建立之年开始计算。直到1949年，中国政府才照格里高利历实行新历法。

## 另外的一次错愕

用了整整1970年的一个夏天，霍夫在一块芯片上设计出了中央处理器（CPU）。一堆存储器——一个用于数据，另一个用于指令，霍夫的CPU是一小片硅上的一台完整的电脑。一年之后，英特尔公司和花花公子公司同一天上市。这一年生产出了第一款微处理器4004，上面有23000个晶体管，4位CPU，一秒钟进行60000此运算，这距离著名的晶体管发明者、诺贝尔奖得主威廉.肖克利在1939年12月29日做试验时写下的："用半导体做放大器比用真空电子管更合适，这在原理上也可行"已经过去了30年，也距离肖克利在1956年离开贝尔实验室到加州山景城创立晶体管试验室也过去了15年。后来的故事，就是英特尔雇佣了后来彻底改变整个产业的安迪.格鲁夫，倡导只有偏执狂才能生存的优秀商业和管理大师。上世纪70年代是微处理器从诞生到发展的孕育期。

同样是1970年4月，柳传志在经过了8年的颠沛流离，手里拎着放着自己全部家当的一只箱子，从湖南的一个农场回到了中国科学院计算所。稍后，中国的第一台集成电路计算机“111数字计算机”在中科院诞生了，而这是中国的计算机技术的第三代。之后，计算所的1000多人从1976年开始搞“757工程”:1300多块插件、2万多个逻辑元件，分布在一座楼房的上下两层，主机房里有15个机架，辅助机房则是所有外围设备，总计占有至少800平方米的空间。到1984年终于完成。它获得了中国科学院“重大科技成果一等奖”。

> 空气稀薄，大家都睡着。你最先醒了，感到窒息，有一种临死前的恐惧，却发现四周都是铁壁，锤打不开。
>                       ————— 柳传志，联想集团创始人

## 一件改变了世界的"尬聊"和“下海”的可能性试探

1983 年底，Richard Stallman 离开了MIT的人工智能实验室，开始专心的开发他发起的GNU程序，他希望能够”继续使用电脑,也没有违背自己的原则”，让RMS最为伤心的莫过于黑客伦理的日薄西山，商业化让自由可以分享的软件源码成了限制，而这时违背黑客伦理的，尤其是哪一年施乐送给实验室的打印机，没有附带驱动的源码，当RMS试图为打印机添加功能和修复bug而索要源代码的时候，却被拒绝了，理由是嫌涉商业机密。如此的遭遇，让RMS深感绝望，他自己如此称他当时的心情：

> 我就是垂死的黑客文化的唯一幸存者，我并不真正属于这个世界，在某种程度上，我觉得我也应该去世了。

随后在1985年，RMS创立了自由软件基金会，致力于推广自由软件的美国民间非营利性组织。其主要工作是运行GNU计划，开发更多的自由软件。GNU开发了大量的软件，包括编译器、编辑器、命令行等，但是它的内核Hard却一直停滞不前。然而，这并不重要，重要的是RMS的反抗精神。

1980年10月23日，中国科学院第一个辞职的研究员——陈春先创办了中关村第一个民营科技企业——北京等离子体学会先进发展技术服务部。不久，中关村的大街上仿佛雨后春笋一样出现了多家公司，主营计算机零件，其中最著名的有“两通两海”——京海、科海、信通、四通，全都是中国科学院的科研人员创办起来的，到联想在1984年10月创立的时候，中关村的科技企业已经有40家了，并且还有了”电子一条街”的名声。

稍后的一年，发明了称之为“LX-80联想式汉子系统”的倪光南加盟联想，在当时，全国有11万台电脑都是原版进口IBM，只能运行英文环境。这个汉子系统打开了个人计算机在本土的市场。

## 自由软件的瓶颈突破和技术人的虚假希望

GNU的发展还算顺风顺水，自由软件基金会也招聘到了人，也有一些赞助近来，毕竟EMACS还是非常优秀的编辑器，（如果它只是一个编辑器就好了）但是，到1989年，GNU依旧不能算是完整的操作系统，因为它缺少最为核心的部分——内核，GNU也发起了自己的内核项目——Hurd，但是它的发展并没有想象中发展的那么顺利。

1991年，还在赫尔辛基上大学的Linus Torvalds，为了在自己购买的载有80386处理器新PC机上能够做点事情，开始宅在家里鼓捣后来称之为Linux内核的项目，当然也是为了实现他看到的《操作系统实现原理》这本教材上的理论。最初它只能用来访问大学里的大型的Unix服务器的虚拟终端。正如Linus后来所描述的，他当初也没有考虑到Linux能够发展到让全球的所有人都在使用的操作系统。

巧的是，如果再晚几个月， 如果 Linus 知道后来问世的 GNU kernel 或者 386BSD(NetBSD, OpenBSD 和 FreeBSD 的前身)，现在大家可能就见不到 Linux 操作系统了。所以说 Linux 系统的诞生确属是意料之外，确切地说是 Linus 为了解决遇到问题而做的事情。

在这之后，没有多长时间，曾经做过编辑的Bob Young 看到了其中的奥妙，认为喜欢控制权的人们会为Linux买单，并且以亨氏番茄酱的理论打动了自己的姑妈，在1993年创建了RedHat公司。

> 中国人先把科学当作洪水猛兽，后把它当作呼风唤雨的巫术，直到现在，多数学习科学的人还把它看成宗教来顶礼膜拜，而他自己终于体会到，科学是个不断学习的过程。
>          ———— 许悼云

1991年宫敏博士在芬兰教育网上找到了Linux。但当时的linux极不完备，一年后竟有了Linux发行版，宫敏在Download了支持internet的Patch后搞了2天2夜才使linux在自己的机器上工作，宫敏博士回忆起此事时说：“因为有源代码，我可以在Patch上写我的程序，直到问题解决。从那时开始我就热爱上了Linux，以后Linux有新的内核我就Download.”

1993年宫敏博士用手提肩背的方式为中国背回了20盒磁带，有80G容量的自由软件，在国家信息中心有关领导的支持下建立了中国自由软件库，从此国内技术人员接触到了Linux,自由软件（free software）的火种开始在国内传播！

其时，协作大概对于是个陌生的词汇，不仅让人想起了当年马尔嘎尼不远万里送给清朝官员们的钟表，它并不是计量时间的，而是当做一种身份的象征。Linux并没有在中国生根，而是成了激情愤慨的爱国者们，终于敢拍着胸脯说，我也可以刀枪不入了。

## 互联网泡沫期的LAMP商业化和”国产化”软件崛起

自由软件的商业化，曲曲折折，让商人们头痛不已，不过，基于互联网的协作方式，却让Eric.S.Remand灵感迸发，进而写出了天才般的著作《大教堂与集市》，这本书直接奠定了被微软捆绑浏览器打的遍体鳞伤的NetScape的开源——Mozilla项目的诞生，当然，其中的功劳也不得不提法律和软件开发兼备的全才Bruce Perens，从Debian的宣言所衍生出来的开放源代码定义。从此，开源软件一发不可收拾，加上互联网被华尔街看中，Apache 基金会随着Apahce项目的广泛使用也成立了。

这样导致的直接的结果就是一大批，基于开源的软件公司的蓬勃发展，疯狂的IPO，如RedHat、VALinux、蓝点Linux等等。

2001年，还是初出茅庐的、一心想做一个说真话的记者的花姐，”永中慷慨，红旗招展”，带着点亢奋和焦急，采访了一大波公司，写了特别的《中国软件产业浮躁与沉思》洋洋客观的大文，哪里有什么国产，不过是将别家的brand去掉，换上了自家的帽子罢了。

> 辜鸿铭的辫子在头上，中国软件产业的辫子在心里。
>              ———— 葑菲彼岸花

## 开源的崛起与本土集体的国殇

Apache基金会，随着Hadoop生态的形成，也验证“Apache之道”的有效性，孵化的项目越来越多。


这个时候最为郁闷的莫过于适兕了，作为中科红旗的第三代开发人员之一的他，和同事争论参与上游的重要性无果，见证了基于开源的欠债不还之后，同样也看到了逐一消失的Linux发行版和BBS：新华linux、幸福linux、蓝点Linux、Linuxsir、LinuxFans......然而，就在这一年，横空出世的OpenStack，又让另外一批人兴奋不已，弯道超车、下一代云计算平台，一时之间各种“自主知识产权”的云计算平台络绎不绝。然而，基于CentOS替换brand的发行版仍然存在，存在于各种场合。

## 默认开源的时代与自主可控的故步自封

2018年，当Kubernetes 以令人叹为观止的方式树立在世人面前的时候，几乎所有人都惊叹于开源的创新能力和生态的建设。要知道，三年前，还是几家技术框架抢夺Docker编排的市场，然而，洞悉开源的Google，联合Linux基金会推出CNCF，邀请RedHat在内的厂商加入开发，以SIG的形式建设社区，以迅雷不及掩耳之势，征服了所有厂商，最终以AWS加入CNCF为标志性的事件，奠定了Kubernetes的江湖地位。

2018年的开源完全变了，开源成了创新的代名词，微软成了GitHub贡献代码最多的公司，机器学习框架，以TensonFlow为代表的先进技术默认就是开源。

AWS的开源负责人，是如此评价开源的：“”，稍后不久，AWS向外界透漏了自己的营收：

> 中国曾经遗忘过世界，但世界却并未因此而遗忘中国。
>      ———— 刘东 《海外中国研究丛书》主编

作为阿里Linux内核团队的Gavin，在国内的Linux圈混的还算有头有脸，经常也在一些微信群里发送一些招聘启事，比如”我们正在雇用Linux内核开发人员！将您的简历发送到dubo.sgw@alibaba-inc.com或shan.gavin@linux.alibaba.com”，这样的，然而有一天有个人说了一句话：“在中国有两种云，一种是拿来主义的云，另外一种是自主可控的飞天云。”

## 后记

让人不得不接受的一个事实是，不得不分清楚这样一个这边与那边，那边在倡导开放式创新、分享是进步、协作才能走的更远，这边在强调自主、可控、乃至国产，然后刻舟求剑般的基于开源项目开始关门放狗，开源很不幸的成为了一个被利用的对象，或者是被曲解和误读的词汇，当然也是躺枪最多的：开源既是国产的遮羞布，也是自主可控的标靶中的，更是寻租者最好的斗牛红布。但是无可置疑的是，开源是本土崛起的互联网企业的中流砥柱，也是工程师在经济大潮中安身立命的技能，更是那些法律工作者翘首期盼的希望有一天能够回归正途的幻象。

本来应该发生的事情是，开源让中国与世界更加的同步。但是，非得自废武功，历经20年失败而毫无悔改之心。将共享单车放在自己门口，拆掉GPS锁，无疑和利用开源，然后将社区丢在脑后是一样的愚蠢不堪。

所幸的是，时间不会停止，格里高利历也不会被撤销，世界使用着同一个刻度，历史仍然会前行，并按照同一时间记录不一样的事件。再过半个世纪，我们再来重温和回顾，或许有着不一样的轨迹。毕竟这是一片受过血与火洗礼的土地，经历过太多的屈辱和不幸，国民混杂着自卑、自强、腐败、贪婪、自大和变态的复杂心理，治愈和进化需要更多的半个世纪。

> 有没有一种方法，既可以强身健体，又能防身保命，还不用流汗和辛苦训练？
>               ————一位年轻妈妈在咨询某空手道教练时所讲

## 参考资料

1. 《黑客与画家》
2. 《发现者》
3. 《美国创新史》
4. 《黑客》
5. 《联想风云》
6. 《只是为了好玩》
7.  Linux、Git 之父 Linus Torvalds 的别样技术人生 https://mp.weixin.qq.com/s/8i6in1oEX3AmY29Usks0mg