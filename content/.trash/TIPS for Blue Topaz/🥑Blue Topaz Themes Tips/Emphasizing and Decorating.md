---
cssclass: colorful-highlight
---
In your notes, you probably want to emphasize or decorate some of your texts.  You can simply replace ==*your texts*== below and you will see what happens.

> [!info] Read and try, if you are first come here, make a copy of this to a new note, so you can always be back here again!
>While you are in the ==**Source Mode**== replace ==*your texts*== between the ==** \* **==     below, 
>
>>\*your texts(replace it here, switch to Source Mode, you may have trouble to find me here😊)\*
>
>Do this in ==**Source Mode**== or ==**Live Preview**== mode, please be reminded, if you are with  ==**Live Preview**== mode, the first \* and the last \* is disappeared.
>
>Switch back and forth within the 3 modes, (==**Reading, Source Mode, Live Preview**==) to see the differences,  get familiar with this will make your notes taking a piece of cake!

Then you will get something like this in ==**Reading**== mode or ==**Live Preview**== mode

*Type any words here to replace these text between the first \* and the last \* . Do not leave any blank after the first \*. in ==**Reading**== mode, you only see text without any **markdown marks**, including the first and the last \*.*

Amazing! You got it!

You can also try to begin type double ==** \* **==  and followed ==*your text*== and then ended with same double   ==** \* **== ,  like  \*\* ***your text***\*\*.  It will show up in ==** Reading **== mode like this:

**your texts**

You can also play with ==**What you typed**==: (combinations of some  ==** \= **== and ==** \* **== , and so on)

| What you got       | What you typed       |
| :--------: | :-------------------: |
| ==your words==       | \=\=your words\=\=   |
| ==*your words*==     | \=\=\*your words\*\=\=     |
| *==your words==*     | \*\=\=your words\=\=\*     |
| ==**your words**==   | \=\=\*\*your words\*\*\=\=   |
| ==***your words***== | \=\=\*\*\*your words\*\*\*\=\= |
| **==your words==**   | \*\*\=\=your words\=\=\*\*   |
| ***==your words==*** | \*\*\*\=\=your words\=\=\*\*\* |
> [!info] Read above table only in ==**Reading**== mode. 😁


Please ignore the appearances varies while you play with above combinations of ==** \= **== and ==**\* **== while you are typing, you will see the magics when you switch to ==**Reading**== or ==**Live Preview**== mode.

> [!warning] Please do not input the ==** "\\" **== while you are typing, though you can surely see it in the ==**Source mode**==!

You man probably noticed that double ** "==" ** will highlight your texts.


````ad-question
title: Want to custmize your highlight colors？It is pice of cake!
collapse: true
Save the below css snippet codes with any filename you would like to use, and put it in .obsidian\snippets in your vault, then enable it, it will be actived. Need more readings?[How to use CSS snippt](obsidian://open?vault=Obsidian%20Help&file=%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97%2F%E6%B7%BB%E5%8A%A0%E8%87%AA%E5%AE%9A%E4%B9%89%E4%B8%BB%E9%A2%98)
```css
/* Make more customized hightlight colors
colorful highlights 1     _==foobar==_  
colorful highlights 2     __==foobar==__
*/
.markdown-preview-view em > mark, span.cm-em.cm-highlight {
  background-color: rgb(255, 248, 152);
}

span.cm-strong.cm-highlight, .markdown-preview-view strong > mark {
  background-color: rgb(147, 255, 228);
/* Change the values inside parenthesis(value from 0 to 255), the color will change accordingly. */ 
/* cuman,能不能将这里也放一个可以调色的小方块，在VS Code中那样，点击拖动就可以调整颜色？*/
}
```
````

---

```ad-tip
Although playing with these combinations will make your note taking more colorful and fun, it is advised to **DO NOT** use them abusely.

Gaving some meanings to certain colors and fonts, using them in your notes, will make your notes more tidy and neat.

**Fianlly, Do add **==cssclass: colorful-highlight==** into the **==YAML==** of your notes, if you like colorful note-taking** #important 
```
