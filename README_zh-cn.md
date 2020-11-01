# 可视化数据报表展示

这个 GitHub 仓库列举了一些我所设计的可视化报表，出于数据安全原因，使用的都为已公开或经过模拟的数据。

数据报表可以通过可视化展现的方式方便快速地追踪公司和团队的核心指标，及时发现异常变化，并可以通过数据拆解发现背后可能的原因和潜在的改进机会。目前市面上有许多可视化工具，可以帮助分析师快速地搭建数据报表，展现通俗易懂的可视化图形，或基于设置时间自动更新报表数据。接下来我将展示一些案例：

### 使用 Mode 为 Yammer 搭建日常运营数据报表

Mode 是一个在线 BI 分析工具，它同时支持 SQL, Python 和 R。在这个项目展示中，我将示范如何为 Yammer 搭建数据报表，帮助其分析日常运营数据。*为了保护数据安全，这个项目使用的是模拟数据，但其对应的趋势是相似的。*


> [Yammer](https://en.wikipedia.org/wiki/Yammer)（在 2012 年被微软收购）是一个服务于公司内部员工的社交网络平台。员工可以在上面分享文档、动态或关于业务新的想法。Yammer 作为一个社交网络平台，这份数据报表将帮助它非常方便地了解在获客和留存上的表现。在这个案例中，我将展现可视化数据报表如何帮助你快速定位异常数据变化（在这个案例中为 WAU 下降），并缩小范围找出问题背后的原因（在这个案例中为邮件推广出现问题）。
> 
> 你可以点击[这里](https://app.mode.com/wctjerry/reports/0b4c0dbe4dab/runs/68f70c1d4180)查看完整的动态报告，以及所使用的 SQL 代码。如果以上链接打不开，可以点击[这里](Yammer.pdf)查看静态版本的报告。


### Tableau

Tableau 是一个简单易用的 BI 工具，它不需要编写任何代码（包括 SQL），就可以做出许多好看的图表。即使是它默认的颜色配置，也比 Python 或 R 的好看很多。不过，虽然它使用起来比较方便，但它在某些情况下有一些限制。相对来说，Python 和 R 更加灵活。我之前写过一篇对比 R 和 Tableau 的文章，可以点击[这里](https://wctjerry.github.io/r_vs_tableau/R_vs_Tableau.html)查看。

> [这个报表](https://public.tableau.com/profile/jerry5570#!/vizhome/SuperstorePerformanceMonitor_16042004765830/SuperstorePerformanceMonitor) 监控了 Superstore 的销售数据表现，并进一步分析了潜在的提升机会。它同时使用了 RFM 分析框架进行用户分群，并拉取了分群用户信息供不同市场策略针对性推广。
> 
> [这个报表](https://public.tableau.com/profile/jerry5570#!/vizhome/social-media/Theriseofsocialmedia)受 Esteban Ortiz-Ospina 启发，探索了社交网络平台发展的一些趋势。这个报表中的最后一张图非常有趣，它对比了社交网络对比其它技术普及（渗透）的速度，从中可以看出社交网络的渗透效率真的非常高。
> 
> [这个报表](https://public.tableau.com/profile/jerry5570#!/vizhome/21550/sheet0)展现了老罗第一次直播带货的数据。其中，我最喜欢的是第一张瀑布图，它非常形象地展现了累计销售额随时间逐步累加的变化趋势。
