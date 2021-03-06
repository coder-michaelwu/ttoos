---
categories:
- 开源
- 感悟
date: 2017-11-13T23:10:44+08:00
description: "有数不清的开源软件项目正在变得强大，强大到任何独立的公司都难以承担的地位，如Linux、Hadoop生态等，无论从公司赢利的角度，还是个人成长的视野，以上游为优先参与和贡献都是上上策，可以增加成功的几率。"
keywords:
- Open Source
- Culture
tags:
- 开源文化
title: "开源软件项目的“上游优先”解惑"
date: 2017-11-13T23:10:44+08:00
url: ""
---
## 引子

中国开源年会2017，即将在本周末上海交大举办，为期两日的会议，开源大咖云集，探讨本土开源。我依旧像往年一样，有机会就布道开源。这次带来的演讲题目是《论拿来主义的陷阱——No upstream first的心理和文化分析》，是标题党没错。其实，现实中的我常常遇到的问题不是大家不愿意参与上游，而是无可奈何，一脸无辜的样子。

那么我在分析的时候，是有一个前提的，那就是假设听众都是明白上游是什么?上游能为项目带来的好处也是清晰明了的。但是，若是有人不明白怎么办？好吧，那我就提前写一篇文章讲讲。算是科普一下。

## 什么是”上游”

上游这个词本身来自于河流，意思是理源头较近的地方，也有相对的意思，在河流的任意两点，相对理源头较近的地方就是上游，否则，称之为下游。

在非软件技术领域，如供应链等，则指的是诸如原材料等生产过程较原始的阶段或本成品。

我们这里的上游，特定指的是开源项目，如Linux Kernel、Kubernetes、Docker、Hadoop、Kafaka等，由最初的发起者或非营利性组织的社区所维护，其他人可以自由的为原始项目（上游）做贡献，诸如提交代码、撰写文档、测试、设计等，然后，按照一定的规则，接受贡献或者拒绝，继而形成更大、更完善、能够解决更多问题的软件项目或产品。

## “下游”又指的是什么？

其实，开源软件的项目上、下游也是相对的概念。所谓的下游，指的是某个开发者或某个团队，fork了上游的代码，形成了自己的分支，自行维护分支的更新，即相对于原初的开发者或社区，形成了自己的产品。项目产品的bug、安全漏洞、文档等统统都由自己维护。

下游如果发展良好，可能形成自己独特的分支，如Ubuntu之于Debian，OpenShift 之于 Kubernetes。

## 上游优先的益处

按照人类的直觉，犹如古代一个脍炙人口的成语故事——“刻舟求剑”一样，一个较为成熟的上游项目，我基于某个版本来进行定制，如添加自己理解的功能、增加易用性等，如下图所示：

![](https://community.redhat.com/images/blog/repeated_rebase.png?1478100396)

若是自己的能力大于上游的话，那么有可能发展出胜出原有项目的，不过这个历史上尚未出现过这样的个人或团队。反倒是，浪费了很多的人力无力，最终又回归到主干。著名的商业案例有Google之于Android内核分支、AWS终究还是拥抱KVM，独立维护XEN太吃力。反面例子太多，我这里就不多列举。以下我们就上游优先，讨论下其益处。

### 个人

作为开源的贡献者，尤其是一名开发者，能够参与到开源软件项目中，被全世界的人都可以看到，若是这个项目是常见的、基础性的、流行的，那么更是让人振奋的事情。毕竟，能够被越多的人承认，是人类之所以发展到现在的动力！

个人上游优先，首先的益处就是，能够在众多的同类型的开发者中交流、探讨问题，追随项目的创始人、维护者，学习他们的思路和解决问题的方法，和他们交流，第一时间解决问题，让全球的人受益。第二就是自由的成长了，在社区，通常是没有外界压力，诸如商务、项目周期等，而是做自己愿意做的事，做自己认为正确的事，不走捷径，坚持原则。当然，同样这样也要求你是一个意志坚定的、敢于挑战自我的、能够自律的人。最后，就是让更多的人认识你，互联网的优势就是讲世界拉平了，超越了时间和地域，比如GitHub这样的基于社交的代码托管站点，你所有的贡献，都将是有目共睹的，你的能力不会被某个公司所雪藏。

个人选择下游，独自蒙头苦干，重复制造轮子之余，视野会逐渐变得狭窄，而且若是被超越，失落感、挫折感也将很难承受。

### 公司/企业

对于公司来说，商业其实有时候蛮好解释的，就是一定要赚取利润，有的时候是直接的，有的时候是间接的、绕很大弯子的。那么开源软件项目的上游优先，我随便列举三个理由，就可以让商人们难以拒绝:

1. **降低维护成本**：基于开源项目的某个版本来做自己产品或服务，然后自己来进行bug修复和安全漏洞补丁，甚至是添加新的功能，随着时间的增加，这简直是惨绝人寰的梦魇。没有哪家公司或个人能够独立维护一个巨大成本的开源项目，即使有实力，也要付出相当大的代价，无论是时间成本还是经济成本。而上游优先则不存在这样的问题。
2. **吸引人才**：代码是最好的面试题答案，如果一名开源贡献者所有的代码、文档你都可以看到。这样的人，难道不需要吗？而这些人，需要的就是一个开放、分享、自由的环境。封闭做事，恐难以捕获他们的心。
3. **影响项目走向**：在开源项目中，新的功能和特性来自于贡献者，而这些贡献者则是影响项目走向的关键人物。如果你的公司认为某个功能对于你们很重要的话，那么你就需要有相应的贡献者积极的去做这件事，恐怕有些时候是别人无法代劳的，因为你们更了解自己的业务。而此时，唯有积极的优先上游开发，才能影响项目的整体走向。否则，就又进入了陷阱。

## 后记

现实中遇到的问题，往往更加的复杂。谁都能看到直观的结果，但是过程往往对于很多人来说是黑盒子，一如现实中我们看到的那些奥运会冠军、编程高手、金牌销售、超级管理者等优秀的人，这些人的特征，大家都仿佛能够观察到，诸如坚毅、刻苦、聪明、灵敏等，但是所有的事情，都是有过程的。没有一蹴而就的事情。开源，发展了这么多年，一路滚爬摸打，有成功的公司、有失意的个体，但是失败的居多，成功的寥寥。洞见就在那里，那就是它的过程。它或许看起来是违反直觉的，但是它往往可以让你离胜利更加的接近。

至于说，为什么人们不实行上游优先的策略，这就是要在本周六下午的分享中要谈到的。敬请期待。

> 如果你想打出一记重拳，你首先做的是不得不后退一步。 ————《百万美元宝贝》

## 参考资料

1. [Linux基金会发布的开源指南之参与开源社区](https://www.linuxfoundation.org/participating-open-source-communities/)
2. [Upstream First: Turning OpenStack into an NFV platform](https://community.redhat.com/blog/2015/03/upstream-first-turning-openstack-into-an-nfv-platform/)
3. [Why upstream contributions matter when developing open source NFV solutions.](http://verticalindustriesblog.redhat.com/why-upstream-contributions-matter-when-developing-open-source-nfv-solutions/)
