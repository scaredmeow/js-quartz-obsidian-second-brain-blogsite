---
title: Demo of split collums
updated: 2022-05-02 10:03
---
## Adding more **ad-** types of in Admonition plugin
By adding more **Ad-** types into Admonition plugin, more customized formats will be available for use.

Currently,  Blue Topaz has incorporated with following  **ad-** types:

| ad- types | Description             | How to use in code block        |
| ------------ | -------------- | --------- |
| blank        | transparent           | ad-blank  |
| def          | definition | ad-def    |
| thm          | theorem    | ad-thm    |
| lem          | lemma     | ad-lem    |
| cor          | corollary | ad-cor    |
| pro          | proposition | ad-pro    |
| hibox        | auto-hide         | ad-hibox  |
| col2         | two columns        | ad-col2   |
| col3         | three columns        | ad-col3   |
| col4         | four columns        | ad-col4   |
| kanban       | prsedo-kanban, unordered lists aside     | ad-kanban |
| flex         | automatically adopt width of columns        | ad-flex   |

In order to use these **ad-** types in your Admonition plugin, please
> - Update your `Blue Topaz` theme to the newest one
> - Install `Admonition Plugin` and enable it, and adding **ad-** types to it, such as blank,col2,flex etc.
> - Install `style settings` plugin and enable the item 3.2

- Following below to add **ad-** types in `Admontion` plugin.

![](https://gitee.com/cuman/imgbed/raw/master/images/202112110950732.png)

- If you see this shows, it means you added the **ad-** types successfully

![](https://gitee.com/cuman/imgbed/raw/master/images/202112111509290.png)

- By default, the admonition collapse is set up in closed.

![[Pasted image 20211215202628.png]]

- Please do remember to enable it in `style settings`

![](https://gitee.com/cuman/imgbed/raw/master/images/202112111001232.png)

---
## Types of Splitted Column

There are two types of splitted columns:  `ad-colX`  and  `ad-flex`

- `ad-colX`  for splitting of articles and lists (including unordered lists)
- `ad-flex`  for element blocks, and could be splited according to `div` to adopt width automatically. For examples, use it for varied query results of dataview
  
## Show-off the Splitting Columns

Here comes some demos for the Splitting Columns. Hopefully you will find it usable for your notes.

It is difficult to guess how widely will this theme spread out, so if you happen to  know well the `QQ` 🐧, then you may find us at **908688452**.

You can also find us at github 😊


### Manually Using Splitting Columns such as: col2, col3, and col4
```ad-col2
collapse: open
title: ◑ Two split-column by using: `ad-col2` 
color: 89, 78, 126
>Contents will be splitted into two columns automatically

This is a `Demo Vault` of `Blue Topaz Theme` which you are currently in using the right one of **Obsidian Themes**, you can always get the latest updates of the vault from the **Obsidian Community Themes** and/or the [**Link Here**](https://github.com/cumany/Blue-topaz-examples)  


Here shows the most attractive features of `Bule Topaz` and how to make that happens in your Obsidian notes. Hope you will enjoy and like it.

`Style Setting` and `enhanced Admonition` come with the `Blue Topaz`, you can find certain custom settings there and easily to fine tune the `Blue Topaz` to your own tasts, also, you will probably find the `enhanced Admonition` Plugin's features are more delighted.

It is difficult to guess how widely will this theme spread out, so if you happen to  know well the `QQ` 🐧, then you may find us at **908688452**.

Major Features of the **QQ** 🐧 community  `Blue Topaz` 

1. Members care of
2. Chattings
3. All topics about Obsidian and Blue Topaz
4. Reporting bugs and personalized CSS
5. Play funs with Obsidian
6. Take notes is not the key point of Obsidian, make Obsidian love is.
7. Beautiful theme is more important than anything!😊


```

```ad-col3
title: ◮ Three Split-columns by using: `ad-col3` 
color: 78,15,6
collapse: close
- This demos the three split-columns
- It shows in three columns
- Is this an egg?
- I don't know!
- Say somethings
- Do you use The Blue Topaz?
- Of course, I DO!
- This is `ad-col3`
- Use it with admonition plugin
- Great!
- My Love!
- Oh, My!
```

```ad-col4
title: ▥ Four Split-columns by using: `ad-col4`
color: 198,155,64
collapse: close
1. **This demos the four split-columns**
2. It shows in four columns
3. Is this an egg?
4. I don't know!
5. Say somethings
6. Do you use The Blue Topaz?
7. Of course, I DO!
8. This is `ad-col4`
9. Use it with admonition plugin
10. Great!
11. My Love!
12. Oh, My!
```

`````ad-col2
title: ◆ Manually adding `ad-blank` split columns
color: 99,178,129
collapse: open

````ad-flex
title: Pay attentions to the usage of `ad-blank`

````
```ad-blank
>人生语录

人生本来是苦的，苦的根源在于各种欲望。
钱多了还想再多，官做大还想更大，房子宽了还想更宽，出了名还想更出名，欲望过多、过强就成了贪病。贪病犹如喝盐水，越喝越咸，越咸越要喝。
当贪的欲望超越人的理性，凌驾生活的所有追求之时，就会成为阻断快乐的根源。

```
```ad-blank
> 人生完成清单

- [ ] Todo1
- [x] Todo2
- [ ] Todo
- [ ] ...
```
`````

````ad-col4
title: 💷 Records of Watched Moives（Example for four split columns by using: `ad-col4`）
color: 98,155,64
collapse: open
```ad-note
title: 🤔 Classic
color: 178,155,64
> “Classic” Movies list

- 🏨 2014.布达佩斯大饭店

- 🌲 2010.挪威的森林

- 🐕‍🦺 009.忠犬八公的故事

- 🏃‍♂️ 1994.这个杀手不太冷

- 👩‍❤️‍💋‍👨 1993.霸王别姬

```

```ad-note
title: 😏 日常
color: 99,188,76
> “日常”的电影列表

- 😴 2010.盗梦空间

- 👁 1994.肖申克的救赎

- 🌌 2014.星际穿越

- 💠 2001.哈利·波特与魔法石

```

```ad-note
title: 🥰 Watched
color: 178,22,164
> Wached Movies 

- 🎖 功勋

- 🇨🇳 我和我的祖国

- ❄ [[长津湖]]

- 🛹[[让子弹飞]]



```

```ad-note
title: 🤩 Going to Watching
color: 139,65,06
> Going to Watching

- [ ] 🚩 no  ...

- [ ] 💡 none ...

```
````

```ad-col2
title: 🖼 Mixed text and Images, split columns by using: `ad-col2`
color: 215,155,255
collapse: close

## 大雁塔
![](https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=844264797,2996895276&fm=26&gp=0.jpg)

大雁塔位于唐长安城晋昌坊（今陕西省西安市南）的大慈恩寺内，又名“慈恩寺塔”。唐永徽三年（652年），玄奘为保存由天竺经丝绸之路带回长安的经卷佛像主持修建了大雁塔，最初五层，后加盖至九层，再后层数和高度又有数次变更，最后固定为今天所看到的七层塔身，通高64.517米，底层边长25.5米。

## 兵马俑
![](https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=844264797,2996895276&fm=26&gp=0.jpg)

兵马俑，即秦始皇兵马俑，亦简称秦兵马俑或秦俑，第一批全国重点文物保护单位，第一批中国世界遗产，位于今陕西省西安市临潼区秦始皇陵以东1.5千米处的兵马俑坑内。
兵马俑是古代墓葬雕塑的一个类别，俑作为古代墓葬的一种陪葬品而出现， 兵马俑即制成兵马（战车、战马、士兵）形状的殉葬品。

1961年3月4日，秦始皇陵被国务院公布为第一批全国重点文物保护单位 。1974年3月，兵马俑被发现。1987年，秦始皇陵及兵马俑坑被联合国教科文组织批准列入《世界遗产名录》，并被誉为“世界第八大奇迹” ，先后有200多位外国元首和政府首脑参观访问，成为中国古代辉煌文明的一张金字名片，被誉为世界8大古墓稀世珍宝之一。

## 西岳华山
![](https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=844264797,2996895276&fm=26&gp=0.jpg)

中国著名的五岳之一，中华文明的发祥地，“中华”和“华夏”之“华”，就源于华山。

## 广仁寺

![](https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=844264797,2996895276&fm=26&gp=0.jpg)

西安广仁寺位于西安明城墙内西北角，为中国唯一绿度母主道场，也是陕西地区唯一的一座藏传格鲁派寺院，是清康熙四十四年（1705年），玄烨皇帝来陕西巡视时，拨专款敕建。
```

---

```ad-col4
title: 🔰 # Masonry Images layout by using: `ad-col4`
color: 215,155,255
collapse: close
![](https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=844264797,2996895276&fm=26&gp=0.jpg)
![](https://i.pinimg.com/564x/13/1f/e4/131fe4d97e3be0a49a5d07431a917d31.jpg)
![](https://i.pinimg.com/564x/84/6c/1c/846c1cab0d47dd7970f9a008eeebd68f.jpg)
![](https://i.pinimg.com/564x/a4/94/01/a494019c68ed85630de16cf8f32523f0.jpg)
![](https://i.pinimg.com/736x/5c/de/98/5cde98c0b4cf3747cfabf3b28d1fbee4.jpg)
![](https://i.pinimg.com/564x/c5/0f/09/c50f09d991dfcfdbea600ff139739fd8.jpg)
![](https://tse1-mm.cn.bing.net/th/id/OIP-C.ZzQgNeKKbo3PybLVZrPmxwHaEK?pid=ImgDet&rs=1)
![](https://i.pinimg.com/564x/fc/59/ea/fc59ea49c6e3d32412d54652ef18f64a.jpg)
![](https://i.pinimg.com/564x/a5/a0/70/a5a070e5146456893c16e3fc1f7ebc46.jpg)
```

---
### Auto adopt width by using `ad-flex`
````ad-flex
collapse: open
title: ◼ Demos of automatically adopt widith by using:`ad-flex`
color: 178,22,164
```ad-note
title: 📝 To-Do's 
color: 158,42,15
- [ ] New Year's Flag
- [ ] Keep in shap
- [ ] Marathon
- [ ] ...
- [ ] ...
```

```ad-tip
title: ✅ Done
- [x] Go learning
- [x] 2021 Goals
- [ ] ...
- [x] ...
```
```ad-example
title: ⏳ Doing
- [ ] Studying
- [x] Reading
- [ ] ...
- [ ] ...
```
````

```ad-flex
collapse: open
title: ◼ Using `<div>` to manually split columns
color: 178,22,164
>>Using `<div></div>`to manually split columns, **`<div>` must followed by a blank line.**
>>Using `>` to cancel the split columns
<div>

### List one
- 蛋蛋
- 小强
- 小风
- 张三
- 李四
</div>

<div>

### List two
- 蛋蛋
- 小强
- 小风
- 张三
- 李四
- 王老五
- 隔壁老王
</div>
```

```ad-flex
collapse: open
title: ◼ Using `<div>` setting up differenc width for columns - first column width fixed. Second automatically adopted.
color: 178,22,164
>>Using `<div></div>`to manually split columns, **`<div>` must followed by a blank line.**
>>Using `>` to cancel the split columns
>>First column width fixed. Second automatically adopted

<div style="width:150px;flex: none;">

## 心得
这个世界不会因为你的付出就必须给予回报，也不会因为你以怎样的方式对待别人，就要求他人同等对待你。人活在这世上，最难的就是保持一份谦卑和平和，而这份谦卑，来源于内心的真诚和踏实的努力。
</div>

<div>

## 《人生笔记》
不要羡慕别人的成功，那是牺牲了安逸换来的；不要羡慕别人的才华，那是私底下的努力换来的；不要羡慕别人的成熟，那是经历与沧桑换来的。可以欣赏，但不要嫉妒，因为那都是别人应该得到的。
 努力了、珍惜了、问心无愧就好，不期待突如其来的好运，只希望所有的努力终有回报。
 人生中要走很多路，有一条路不能回头，就是放弃的路；有一条路不能拒绝，就是成长的路；有一条路不能迷失，就是信念的路；有一条路不能停滞，就是奋斗的路；有一条路不能忘记，就是回家的路；信心满满的走好脚下的每条路，祝你生命中的每一天都很精彩。
</div>
```

```ad-flex
collapse: open
title: ◼ Using `<div>` set up varied width columns
color: 178,22,164
>>Using `<div></div>`to manually split columns, **`<div>` must followed by a blank line.**
>>Using `>` to cancel the split columns
>>There columns can be set to differece width by using ` <div style="width:20%;flex: none;">`

<div style="width:20%;flex: none;">

## First column
This colum takes 20% of the widthness. This colum takes 20% of the widthness.This colum takes 20% of the widthness. This colum takes 20% of the widthness. 

</div>

<div>

## Second column
This column takes rest of the widthness. This column takes rest of the widthness. This column takes rest of the widthness. This column takes rest of the widthness.
</div>

<div style="width:30%;flex: none;">

## Third column
This column takes 30% of the widthness. This column takes 30% of the widthness. This column takes 30% of the widthness. This column takes 30% of the widthness.
</div>
```

````ad-flex
title: 🎫 Using `ad-flex` to automatically adopt width
collapse: open
color: 78,22,64
> 健身是一个需要长此以往坚持的生活习惯，每个时期的目标各不相同，我们可以制定个长期的倒计时来督促鼓励自己~
```ad-note
title: 5️⃣ 五年目标
collapse: closed
color: 78,122,64

- [ ] 体重维持在102斤
- [ ] 有一项或几项喜欢并能坚持的运动
- [ ] ...
- [ ] ...
- [ ] ...

```

```ad-note
title: 4️⃣ 四个月目标
color: 255,255,255
- [ ] 有一项或几项喜欢并能坚持的
- [ ] 体脂率在23%
- [ ] ...
- [ ] ...

```

```ad-note
title: 3️⃣ 3周目标
color: 255,255,255
- [ ] 每天拉伸
- [ ] 建立规律运动的节奏
- [ ] 不熬夜、按时吃饭
- [ ] ...

```

```ad-note
title: 2️⃣ 2日目标
color: 255,255,255
- [ ] HIIT打卡1次
- [ ] ...

```

```ad-note
title: 1️⃣ 1小时目标
color: 138,122,188
- [ ] 举铁打卡1次 💪 
- [ ] 喝水...
- [ ] 伸展...

```
````

---
## Pseudo Kanban - Multi-Nested Task list
```ad-kanban
title: 📈 Using `ad-kanban` for Pesdu-Kanban, Multi-Nested Task List
color: 55,205,75
collapse: closed
- [ ] 紫色鸡蛋
	- [ ] Obsidian其实是紫色鸡蛋
	- [ ] 不断灌输这个，他们就当真了
	- [ ] 不能告诉他们真相
- [ ] 其实那是鸭蛋
	- [ ] 事实太过残酷
	- [ ] 不忍直视
- [ ] 说笑的，那真是鸡蛋
	- [ ] 不信我也没办法
	- [ ] 信鸡蛋，得永生
- [ ] 说笑的，那真是鸡蛋
- [ ] 不信我也没办法
- [ ] 信鸡蛋，得永生
- 不加勾选框也可以
	- 不影响是不是鸡蛋的问题
	- 但是有序列表不可以
- 没有子项的列表
	- 3333
- 没有子项的列表2
- 测试3没有子项的列表2
- 没有子项的列表2没有子项的列表2
- 没有子项的列表2没有子项的列表2没有子项的列表2
- 没有子项的列表2没有子项的列表2没有子项的列表2

```

```ad-kanban
title: 📈 Using `ad-kanban` for unordered list
color: 55,205,75
collapse: closed
- 蛋蛋
- 小强
- 小风
- 张三
- 李四
- 王老五
- 隔壁老王
- 蛋蛋
- 小强隔壁
- 小风
- 张三
- 李四
- 王老五
- 隔壁老王
```
### Pseudo Kanban - Nested Split Columns
````ad-kanban
title: 📈 Pseudo Kanban with nested `ad-col2`
color: 55,205,75
collapse: closed
> for column height fixed
```ad-col2

### 订单一
- 蛋蛋
- 小强
- 小风
- 李四
- 隔壁老王
- 333333

### 订单二
- 蛋蛋
- 小强
- 小风
- 张三
- 李四
- 王老五
- dddd
- 隔壁老王


```
````

````ad-kanban
title: 📈 Pseudo Kanban with nested `ad-flex`
color: 55,205,75
collapse: closed
> for column height varied, use ad-flex +`<div>` 
```ad-flex
<div>

### 订单一
- 蛋蛋
- 小强
- 小风
- 李四
- 隔壁老王
- 333333
</div>

<div>

### 订单二
- 蛋蛋
- 小强
- 小风
- 张三
- 李四
- 王老五
- dddd
- 隔壁老王
- 333
- 4444
</div>
```
````

---
## Latex Syntax Supported
The  **`ad-`** type of added to admonition plugin supports **Latex** syntax.  

```ad-def
title:The two order determinant
$$
\begin{cases} 3x+2y=7\\ 4x+3y=10\\ \end{cases}
$$
```

Operation Results

```ad-lem
title: Operation Resaults
$$
\left|
\begin{array}{cccc} 
    3  &  2   \\ 
   4  &  3  
\end{array}
\right| 
=
3*3-2*4
$$

```


```ad-thm
title: Quadratic Equitions
$$
x = \frac{7*3-2*10}{3*3-2*4}
$$

$$
y = \frac{3*10-7*4}{3*3-2*4}
$$
```
## Auto Hide Boxes
```ad-hibox
This is a demo of automatically hide box. Hover mouse to show.
```
## Examples of MOC
> Using `ad-col3` and `ad-col4` or  `ad-flex` according to contents.

````ad-col3
```ad-blank
>Personal Notes
- ✔ 待办事项
- ✅ 已完成事项
- ▶ 观影记录
- 📙 阅读记录
- ...

```

```ad-blank
>Working Notes
- 🚩工作计划
- 🏳 未完成的计划
- ☢ Bug清单
- 🔀 API接口文档
- ...

```

```ad-blank
>Class Lesson Notes
- ♎课程管理
- 📝 写作计划
- ✏ 实验记录
- ...

```
````

````ad-flex
```ad-blank
>Personal Notes
- ✔ 待办事项
- ✅ 已完成事项
- ▶ 观影记录
- 📙 阅读记录
- ...

```

```ad-blank
>Working Notes
- 🚩工作计划
- 🏳 未完成的计划
- ☢ Bug清单
- 🔀 API接口文档
- ...

```

```ad-blank
>Class Lession Notes
- ♎课程管理
- 📝 写作计划
- ✏ 实验记录
- ...

```
````
