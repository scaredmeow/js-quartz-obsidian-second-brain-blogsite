---
updated: 2022-04-07 11:34
---

> Callouts are available from Obsidian 0.14.2, it incorporated with admonition plugin, and now in according with syntax of *Microsoft Docs*.  
> All admonition text boxes can be converted into Callouts with a single mouse click!

## How to Use Callout
- Press <kbd>**ctrl**</kbd> + <kbd>**P**</kbd>, then input `callout` 
 - If contents existed already, then **select the content**, Press <kbd>**ctrl**</kbd> + <kbd>**P**</kbd>, in the pop window, select **insert callout**.

## Video 
[Farewell to dull Obsidian interface, it can be awesome splendid!  (bilibili.com)](https://www.bilibili.com/video/BV1G5411U7m8/)

## Available Callout Styles
## Official Supported Styles 
### Prompt Callouts
> [!note]
> Here's a callout block.
> It supports **markdown** and [[Internal link|wikilinks]].

> [!abstract]

>[!todo]

> [!info]

> [!tip]

> [!success]

> [!question]

> [!warning]

> [!failure]

> [!danger]

> [!bug]

> [!example]

> [!quote]


Except `info` callouts, below are also supported.
-   note
-   abstract, summary, tldr
-   info, to-do
-   tip, hint, important
-   success, check, done
-   question, help, FAQ
-   warning, caution, attention
-   failure, fail, missing
-   danger, error
-   bug
-   example
-   quote, cite
  
  
### Show-off of Callouts

1. Title only, no content
   [!TIP] Callouts can have custom titles, which also supports **markdown**!

2. Folded
> [!FAQ]- Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden until it is expanded.

3. Customized Callout
Use presetting in CSS snippet as below
```css
.callout[data-callout="my-callout-type"] {
    --callout-color: 0, 0, 0;
    --callout-icon: icon-id;
    --callout-icon: '<svg>...custom svg...</svg>';
}
```

## Customized Callout Styles of **Blue Topaz**
By adding `callout` types, the **Blue Topaz** has the following callouts for use:

>
| Callout Types          | Description                            | How to use                                    |
| --------------------- | ------------------------------- | --------------------------------------- |
| cloze                  | Make texts fuzzy                    | >[!cloze]                               |
| kanban                | Pseudo Kanban for unordered lists             | >[!kanban]                              |
| hibox                 | Auto-hide                      | >[!hibox]                               |
| bookinfo              | Book Info(Book cards in table)      | >[!bookinfo]                            |
| xx%                   | Set Callouts width(xx in10-100)   | >[!30%]                                 |
| right\|left\|center   | Set Callout Alignment                 | >[!right] <br>>[!left]<br>>[!center]    |
| indent                | Indent two full-width characters of the first line               | >[!indent]                              |
| blank                 | Transparent Callout                | >[!blank]                               |
| timeline                      |            Timeline Style                     |    [[timeline callout]]                                     |
```ad-info
title: Please Try 😊
**Conbime these properties together to have more type of Callouts!**
**More examples comming!🤣😂😊**
```

Since Ob 0.14.5, separate `Properties of metadata` with pipe line **`|`** is supported, so such as `> [!note|right]` will create a new callout type。

```ad-info
title: Supported Metadata Properties

| Properties            | Descriptions                         |
| ------------------- | ----------------------------- |
| xx%                 | callout width, xx valued in 10-100 |
| right\|left\|center | callout layout alignments              |
| indent              | indent 2 full-width charactors in first line|
| nowrap              | no text wrap            | 

```


### Fuzzy Text>
[!cloze]
>These texts is becaming fuzzy.

### Pseudo kanban
> [!kanban]+ Callout Pseudo kanban Test
>- [ ] callout Pseudo Kanban Test
>	- [ ] 3333
>	- [ ] 3333
>		- [ ] 333
>		- [ ] 333
>- [ ] Secondary Column
>	- [ ] Sub-lists
>- [ ] Third Column, better to edit in `Source Mode`
>	- [ ] test 333
>	- [ ] test 444
>- [ ]  22222
>- [ ] 2234444
>- 555555
>- 777777

### Auto Hide Box`hibox`
>[!hibox]
>This part of text will hide automatically.
>- 122333
>- [ ] 3333
>	- [x] 33333
>- [ ] 4444

### Info Cards `infobox` (Examples in Chinese)

> [!Infobox|notitle right 45%]+ ## 关羽
>![[Pasted image 20220331161219.png|circle]]
> 
| 本名     | 关羽                          |
|:-------- |:--------------------------------------------- |
| 别名     | 关云长、关公、汉寿亭侯、武圣                 |
| 昵称     | 二爷                                                                 |
| 国籍     | 中国                                       |
| 出生     | 约160年                                |
| 逝世     | 220年（约60岁）               |
| 职业     | 将领                              |
| 活跃年代 | 东汉末年                       |
| 相关人士 | 大哥：刘备<div>三弟：张飞<br></div><div>子女：关平、关银屏<br></div> |

> [!tip|indent] 三国人物--关羽
> 关羽早年因杀人逃离家乡，奔向涿郡，在此处结识刘备与张飞，三人相谈甚欢，恩若兄弟。
> 建安五年（200年）刘备投奔袁绍，关羽被曹操捉拿后担任偏将军，在万军之中斩杀颜良，立下了大功。不过之后关羽离开曹操阵营投奔刘备，曹操并未挽留，而是认为“彼各为其主”，放他离开了。
> 之后关羽跟随刘备投奔刘表，刘表去世后刘备在南逃过程中派遣关羽带领数百艘船前往江陵，并在被曹操追杀后成功与之汇合，一同前往夏口。在刘备平定益州后关羽总督荆州诸事，并在之后进行了刮骨疗毒的壮举。
> 建安二十四年（219年）刘备自封为汉中王，赐关羽前将军之职，之后在樊城之战中一举斩落庞德，威震华夏。但之后由于孙权反水偷袭以及部下倒戈东吴，关羽军队溃散，败走麦城，被孙权部将抓获，同年十二月在临沮被斩杀。
> 之后孙权将关羽的头颅送给曹操，曹操以诸侯之礼下葬于洛阳，孙权则将身躯下葬于当阳。后被蜀后主刘禅追谥为壮缪侯。
> 

### Book Info Cards `bookinfo` (Examples in Chinese)

> [!bookinfo]+ 《从零开始的女性主义》
> ![bookcover|200](https://img2.doubanio.com/view/subject/l/public/s33984963.jpg)
>
| 属性     | 内容                                           |
|:-------|:---------------------------------------------|
|  ISBN  |  9787559652317                              |
|  作者    |   '[日]上野千鹤子/[日]田房永子'                           |
|  出版社   |  北京联合出版公司                           |
|  来源    |  [从零开始的女性主义](https://book.douban.com/subject/35523099/)  |
|  评分    |   8.7                             |
|  页码    |  192                         |

### Customized Width and Alignment 
> Properties of alignment supports `right，center，left`
Properties of Width supports from `10%` up to `100%` of the whole widthness of a column such as in `10%`, `15%`, `20%` etc.


```html
**There are two forms in using**
 > [!note|30%]
 > [!note 30%]
```

> [!note|right 35% indent ]+ TextBox
> With the development of Chinese economy, the world is watching us. More and more foreigners have sensed the great potential market and come to China to seek for cooperation. Chinese film market had been ignored before, but now more Hollywood directors show their willingness to work with Chinese actors, so as to catch more Chinese audiences and increase the box office.   

> [!tips right 35% ]+ Title
>  Indeed, Chinese box office is increasing every year, even surpasses the foreign’s, which makes the foreign directors pay so much attention to Chinese audiences. It also shows that China has influnced the world and it plays more and more important role in the world economy. There is no doubt that more cooperations will happen during foreign enterprises and Chinese business. 

With the development of Chinese economy, the world is watching us. More and more foreigners have sensed the great potential market and come to China to seek for cooperation. Chinese film market had been ignored before, but now more Hollywood directors show their willingness to work with Chinese actors, to catch more Chinese audiences and increase the box office.  
 Indeed, Chinese box office is increasing every year, even surpasses the foreign’s, which makes the foreign directors pay so much attention to Chinese audiences. It also shows that China has influenced the world, and it plays more and more significant role in the world economy. There is no doubt that more cooperations will happen during foreign enterprises and Chinese business.
 With the development of Chinese economy, the world is watching us. More and more foreigners have sensed the great potential market and come to China to seek for cooperation. Chinese film market had been ignored before, but now more Hollywood directors show their willingness to work with Chinese actors, to catch more Chinese audiences and increase the box office.  

### Two full-width characters indents in the first line 
> **Two forms in using**
```html
 > [!note|indent]
 > [!note indent]
```

> [!NOTE|indent] Title
> In China, millions of high school students will take part in the very important exam on June, it is the turning point of their lives, because the exam will decide what kind of university they will enter. Most people believe that it even decides their fates. While it is just the beginning of their new lives.
在中国,数以百万计的高中学生会在6月参加重要的考试,这是他们生活的转折点,因为考试将决定他们将进入什么样的大学。大多数人认为,这甚至决定他们的命运。然而这只是他们的新生活的开端。
When high school students finish their study, it is time to think about what kind of major they need to choose. This is a very significant question, selecting a major needs to consider many factors. The first is about interest. Studying with passion can make a student happy and love what the major. The second is about foreground. The major always decide the future job, so students need to think about the prospect.
当高中学生完成他们的学业,是时候考虑需要选择什么样的专业。这是一个非常重要的问题,选择专业需要考虑很多因素。第一个是关于兴趣。有激情的学习可以让学生感受到快乐和爱。第二个是关于前景。专业总会决定未来的工作,所以学生需要思考前景。


> [!Example|nowrap] Table, Images etc. shown in one line.
> 
![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]![[obsidian_image.png\|+grid|150]]
> 
| Table Title One                                                    | Table Title Two                                                 | Table Title Three                                                                      |
|:-------------------------------------------------------|:-------------------------------------------------------|:-------------------------------------------------------------------------|
| This is a super long line to test whether it wrap or not 这是很长的表格内容看 会不会自动换行                                     | This is a super long line does NOT wrap  这是很长的表格内容不会自动换行                                     | This is a super long line does NOT wrap  这是很长的表格内容不会自动换行                                                      |
| This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。This is a super long line does NOT wrap  这是很长的表格内容不会自动换行。 |
>

### Contents Center Aligned (Exampls in Chinese)
![[Blacken out and Blank (Three syntax)#Example Three in Chinese]]



