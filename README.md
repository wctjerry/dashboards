# Dashboard Gallery

*[点击切换中文介绍](README_zh-cn.md)*

This repo lists a few data dashboards I've designed based on some public/fake data. 

A data dashboard is a great tool to visually (and always easily) track key metrics across the team and company, identify abnormal trends, and potentially give you some clues to drill down and find opportunities to improve. There are quite a few tools and platforms which we can use to build dashboards, from visualizing to automatically update the data on a regular basis. Below I will show some cases.

### Yammer Dashboard with Mode

Mode is an online BI tool that supports SQL, Python and R. In this demo, I will demonstrate how I use Mode to design a dashboard for Yammer. *(The data used is fake due to privacy protection, but the trends are similar.)*

> [Yammer](https://en.wikipedia.org/wiki/Yammer) (acquired by Microsoft in 2012) is a social network for communicating with coworkers. Individuals share documents, updates, and ideas by posting them in groups. As a social network platform, this dashboard will help Yammer easily understand its performance on user acquisition and retention. In this demo, I've also shown how a dashboard could help you easily identify abnormality (WAU is decreasing), and narrow down possible causes behind the scene (Something wrong with Email compaign). 
> 
> You can view the fully functional and interactive dashboard [here](https://app.mode.com/wctjerry/reports/0b4c0dbe4dab/runs/68f70c1d4180). The queries are written in `SQL` and the visualization is generated by Mode. If that doesn't work for you, you could also take a look at this [static version](Yammer.pdf).

### Tableau

Tableau is a user-friendly BI tool that doesn't need to write any code (even SQL)! It has very much decreased the threshold to build good-looking charts. I especially like its color palettes, even default one! It is way much better than what Python and R have. Although it is easier to follow, it has limitations in some cases. Python and R are much more flexible. I have written a blog comparing between [R and Tableau](https://wctjerry.github.io/r_vs_tableau/R_vs_Tableau.html). Please feel free to take a look if you are interested.

> [This dashboard](https://public.tableau.com/profile/jerry5570#!/vizhome/social-media/Theriseofsocialmedia) explores a few trends of social media. Inspired by Esteban Ortiz-Ospina's work. Personaly I think the most interesting chart is the last one. You can see how social media's adoption line compares to other technologies. 
> 
> [This dashboads](https://public.tableau.com/profile/jerry5570#!/vizhome/21550/sheet0) shows Lao Luo's first live show to promote products. I really like the waterfall chart in this scenario. It intuitively demonstrates the cumulative effect of sequentially introduced values by time (or categories).