---
banner_x: 
obsidianUIMode: preview
---
Translator: @心随风动-灵魂如风

## Advices to Obsidian's Newbies

```ad-info
title: If you read below paragrah without any difficults, just follow the link! **Or, _ignore_ it (is in Chinese) and keep reading rest parts**

[本人对bsidian新手的建议（2022版本） - 经验分享 - Obsidian 中文论坛
](https://forum-zh.obsidian.md/t/topic/4040)

```

##  Knowing the ***==Blue Topaz==***, Starts Here!

```ad-tip
- [i] This **[Demo vault of `Blue Topaz` Theme]**(https://github.com/cumany/Blue-topaz-examples) was orginaled by Cuman. All Tips were written by the author of the theme, **3F**
- [i] This **[Demo vault of `Blue Topaz` Theme]** consists of a basic Obsidian vault, which demostrates basic fuctions of Obsidian, it also includes necessary Obsidian plugins (before use it, please update the plugins through the Obsidian Plugin Communitity)
---
Special thanks dedicated to @Johnny @Lillianwho  @lavi @成雙酱  and @锋华, for their contributions to the lessons, tips, and as well as their brilliant and creative throughts.
如果有问题或者建议 请加入Topaz社区[Topaz QQ群](https://jq.qq.com/?_wv=1027&k=TWGhXs40)  [Obsidian频道](https://qun.qq.com/qqweb/qunpro/share?_wv=3&_wwv=128&inviteCode=zHpby&from=246610&biz=ka)  [Cuman的B站](https://b23.tv/2Uqt2dn)
```

## MOC
```ad-kanban
- **Fast Navigation**
	- 👉 `$= '[[#Statistics of Diaries#'+ moment().format("YYYY-MMM") +'|Total of this month\'s diaries]]'`
- **Lessons**
	- [Cuman at Bilibili.com](https://b23.tv/2Uqt2dn)
	- [[Blue Topaz Themes Tips]]
	- [[Admonition Split Columns|💶 Split Columns]]
	- [[Pseudo Kanben, ad and callout declaration EN|📊 Pseudo Kanban]]
	- [[Callout Styles Show-off and Use|🌈Callout Show-off and Use in Blue Topaz]]
	  
```

## Tips
````ad-kanban
```dataview
list from "00-Tips"
```
````


````ad-flex
<div>

### Recent Edited Notes
```dataview
table WITHOUT ID file.link AS "Title",file.mtime as "Edit Time"
from !"template" and !"kanban"
sort file.mtime desc
limit 5
```
</div>

<div>

### Notes Created in 3 Days
```dataview
table file.ctime as "Created Time"
from ""
where date(today) - file.ctime <=dur(3 days)
sort file.ctime desc
limit 5
```
</div>
````

## Blue Topaz Preset `cssclass` Style Declaration
![[Preset cssclass Style of Blue Topaz EN]]

