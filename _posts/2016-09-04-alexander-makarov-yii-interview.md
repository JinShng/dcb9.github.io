---
title: Alexander Makarov 于 CLOUDWAYS 的面试
tags: 工作,翻译
layout: post
---

<a target="_blank" href="https://github.com/samdark">Alexander Makarov</a> 是一个高级工程师并且他是 <a target="_blank" href="http://www.yiiframework.com/">Yii 框架</a>的核心贡献者之一，同时他还是 <a target="_blank" href="https://github.com/samdark/yii2-cookbook">Yii 2.0 Cookbook</a> 的作者。


Alexander 在 Cloudways 面试中，讲述了他职业路径、对 Yii 框架的贡献以及 Yii 和其它框架的对比，最后他还给学生一些非常好的建议。

<img src="https://www.cloudways.com/blog/wp-content/uploads/Alexander-Makarov-Interview-Banner-1.jpg" />

Cloudways: 跟读者分享一些你的故事吧，你是如何开始你的开发生涯的，是谁促动了你，还有截止现在你觉得自己做的最好的工作是什么？

Alexander: 读者们好！我是 Alexander Makarov 一名来自俄罗斯的 IT 工程师，大部分工作就是 Yii 框架和参与 <a target="_blank" href="http://www.php-fig.org/">PHP-FIG</a>，最近，我全职在 <a href="http://www.stay.com/beijing/guides/" target="_blank">stay.com</a> 上班，只能用我的空闲时间来维护 Yii，你可能在 Github 上见过我 <a target="_blank" href="https://github.com/samdark">@samdark</a>。

当我还是个孩子的时候，我的父亲配置了一台 z80 的电脑，里面运行着 sinclair basic (BASIC 的编程方言)，当然还有游戏。玩游戏玩够了之后，我开始思考它们是怎么工作的，这些游戏是如何运转的。我喜欢自己明白的那种感觉，所以它决定了我需要正确地学习计算机科学。五年在大学获得了硕士学位，让我得到了一份在西门子做 DBA 和 Java/SAP 的工作，在那之后又过了 10 年，自从大学起我就使用 PHP 来做个人项目，因为它比 J2EE 在开发简单的 web 上更合适。

最开始 PHP 还是简单的，后来我使用了 CodeIgniter，很快发现它存在着许多的限制，之后搜索了许多完美的框架，试用了 CakePHP、Zend 和其它的，无意中打开了 Yii 官网（当时还很丑），查看了它的文档。它做地非常地合理，试用完 Yii 后，我发现它运行速度非常地快，并且很好地平衡了复杂难懂和简单的操作，让我的工作流程更舒适。2010 年我加入了 Yii 团队一直到现在，它是我做的最值得关注的开源工作。

Cloudways: 你在 stay.com 主要负责哪些工作？

Alexander: 主要负责开发网站、CMS 和 API，当 Android、服务器、SOLR 需要时，我会去帮忙。

Cloudways: Alexander 你是 Zend 认证的开发者，你为什么会选择 Yii 而不是 Zend 呢？你是如何对比它们的？

Alexander: 我是 ZCE (Zend Certified Developer) 没错，但是你可能把这个证书和 Zend 框架弄混了，ZCE 只是关于PHP 自身的。

尽管这样，Zend 框架我还是很熟悉的，所以可以回答第二部分问题。在选择框架时候，Zend 框架还是第一版，对我来说它太正式了——所有的模式都与 RFCs、设计模式等完全一致。尽管它理论上是最好的编码方式，但是在实际中显得有点过于复杂了。此外 Zend 团队还偏离了 RFCs（我记得有一次关于 Email 的组件）他们拒绝引入 Email 的补丁。

另一方面，Yii 所有东西都源自实践，如果在实践中与 RFCs 存在偏差，框架会根据实际环境对功能进行很好的修补，此外它也比 Zend 快，并且有更漂亮的语法，使你日常编码更舒心。

Cloudways: 你是顶级 PHP 框架 Yii 的核心贡献者之一，你感觉怎么样？

Alexander:通常很不错。当你意识到你正在创造其他开发者正在其日常工作中使用的东西时，这会是一种非常棒的感觉。当有贡献时，你就会感受到社区的精神。我也有喜欢探查编码的怪癖，并且开发一个框架也给了我更多这样的机会。


当然，也有一些不好的部分。维护这样大一个开源项目会疯狂地吸干你的时间。有时，有些无理的人要求你立即修复某些东西。但总体上而言，好的部分会比坏的多。 

Cloudways: 你在 Yii 框架中的主要贡献是什么，还有哪个版本你贡献的最多？

Alexander: 当我来 Yii 之前就用过 J2EE、CodeIgniter 和一些其它框架，在 1.1 时我主要贡献了一些非常好的功能，这些功能都是来自我以前的经验。Yii 2.0 是另一个故事，我从最开始就参与了这个项目，和薛强及团队成员一起设计了整个框架。

Cloudways: According to a 2015 survey by sitepoint, Laravel tops the list of the most used framework, and Yii2 stands on the 4th position. Do you think Yii2 can get the top position in future?

There’s a chance, but I don’t think Yii will be at the top of the list in the US next year. It’s hard to compete in marketing with local US commercial players. Yii is slightly more popular outside US. Especially in Russia, Ukraine and ex-USSR countries which are easily reachable for conferences.

Cloudways: How would you compare Yii with Laravel and Symfony?

Alexander: All three are good frameworks with their own pros and cons.

Laravel has excellent marketing, good public API, lots of cool infrastructure, good events in US. Until recently, it wasn’t really suitable for lengthy projects because new major versions were released one after another and old ones were just dropped. Now it’s much better. The framework management and development is a bit fragile since it depends a lot on its founder but, hopefully, it will change with time.

Symfony has a very long history. It’s mature and is backed by a strong company which could afford full time documentation team, and developers team. The framework community is strong as well. The framework leans slightly towards enterprise solutions and is suitable for really complicated applications. Because of that, some parts of the framework are really complex.

Yii is all about practice. It’s very fast to develop prototypes with, because of Gii code generator and well-made enhanced implementation of ActiveRecord design pattern. Yii provides lots of features out of the box. The community is strong, docs are good, code is stable and we care about backwards compatibility. We cut lots of edges for a reason. As a result, Yii performs better than Laravel or Symfony using the same hardware with the similar application implemented. As for downsides, Yii doesn’t stand in your way much when you’re trying to go against best practices, clean code and domain driven design. Still, if you know what you’re doing, all the tools are there for you.

Cloudways: What are the best features of Yii according to you?

Alexander: Error handling and debug toolbar, code generation, forms, query builder and active record, data providers and data widgets, strong i18n layer, REST API framework.

Cloudways: Alexander, what are your activities when you are not working at all? How do you spend your time?

Alexander: Traveling, bicycling, watching movies, playing games, doing various family activities.

Cloudways: Just for our readers, can you send a picture of your workstation?

Alexander: Here you go!

![Alexander Makarov workstation](https://www.cloudways.com/blog/wp-content/uploads/image00-8-1024x819.jpg)

Cloudways: What advice would you like to give to students who are going to start their career as a developer?

Alexander: Spend time to learn computer science fundamentals. You won’t need it in the first five years, but later there will be no way to get further without a good base and it will make a big difference.

Cloudways: We at Cloudways are providing one click installation for PHP stack and different PHP frameworks. I would like you to check it yourself and share your opinion about the platform. What can we do to further improve the outlook and performance of the platform?

Alexander: Overall, the service is fine. It may save time on setting up everything from scratch. Pricing is reasonable especially for lower tiers. There are downsides, of course:

The default stack is made to meet the needs of many different developers so while it’s OK, custom stack may perform much better.
Some DigitalOcean features aren’t available yet.
As for Yii, all the requirements for Yii 2.0 are OK so it should work fine.

感谢 [@亦清](https://github.com/yiqing95) 帮忙翻译了许多内容

源文链接：<a target="_blank" href="https://www.cloudways.com/blog/alexander-makarov-yii-interview/">https://www.cloudways.com/blog/alexander-makarov-yii-interview/</a>
