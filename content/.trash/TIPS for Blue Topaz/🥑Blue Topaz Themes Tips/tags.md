## Colorful Tags and Enhanced Tags

There are nine colors of tags within the ==***Blue Topaz***==, all of them are  listed as in the first line below.  The color of tags will vary in accordingly with its positions, no matter of the contents of the tags. 

#tag-1 #tag-2 #tag-3 #tag-4 #tag-5 #tag-6 #tag-7 #tag-8 #tag-9 
#tag-1                    #tag-3 
#tag-1                                                         #tag-5                        
#tag-1 Switch to ==***Live Preview***==  and try type ==**#tag-5***== here, and see what color it will be.
#tag-1                                                                                                  #tag-8

You can customize the colors in ==***Style Settings, 2.1.3 Tag Color***== if you prefer some other colors of tags.

![[Style Settings 2.1.3.png]]

```ad-info
There also some specific tags for ==*ideas*==, ==*important*==, ==*dailynote*==, ==*weeklynote*==,==*questions*==,==*completed*==, ==*inprogress*== , using these tags by adding a ==*\#*== before these words will make your tags special. 


```

For example , if you type: ==*\#ideas*==, you will get the tag #ideas .  

 #important #dailynote #weeklynote
#ideas #questions
#important #complete #inprogress

---
````ad-example
title: Example of A CSS Snippet Example of Customized #noideas
 
You may replace the "noideas" with "your words" and the icons to make your own `#your words` tag.

```
.tag[href^="#noideas"] {
  background-color: var(--tag-noideas-bg) !important;
  font-weight: 600;
  font-family: var(--font-family-special-tag) !important;
  color: var(--white) !important;
  border: none;
}

.tag[href^="#noideas"]::after {
  content: ' 😊❓';
  font-size: var(--font-size-emoji-after-tag);
}

.cm-s-obsidian .CodeMirror-line span.cm-tag-noideas:not(.cm-formatting-hashtag)::after {
  content: ' 😊❓';
}

.cm-s-obsidian .==**CodeMirror-line**== span.cm-hashtag.cm-meta.cm-hashtag-end.cm-tag-noideas:not(.cm-formatting-hashtag) {
  font-family: var(--font-family-special-tag) !important;
  font-weight: 600;
  background-color: var(--tag-noideas-bg);
  color: var(--white) !important;
  border: none;
}

/* end */
/* 我看Tips里说CodeMirror插件会和Blue Topaz有冲突，这里的代码里还有它，是从0502的示例库抄来的代码 */

/* below is copied by myself from Blue Topaz CSS but not background color, realy noideas 😒, aslo, if possible, the tag fonts should also be able to be customized with this css snippet, but currently, I do not know how to make it happens! */

.tag[href^="#noideas"] {
    background-color: var(--tag-noideas-bg) !important;
    font-weight: 600;
    font-family: var(--font-family-special-tag) !important;
    color: var(--white) !important;
    border: none;
}

.tag[href^="#noideas"]::after {
    content: ' 😊💡';
    font-size: var(--font-size-emoji-after-tag);
}
.cm-s-obsidian:not([class="markdown-source-view cm-s-obsidian mod-cm6"]) span.cm-tag-noideas:not(.cm-formatting-hashtag)::after {
    content: ' 😊💡';
}
.cm-s-obsidian:not([class="markdown-source-view cm-s-obsidian mod-cm6"]) span.cm-hashtag.cm-meta.cm-hashtag-end.cm-tag-noideas:not(.cm-formatting-hashtag) {
    background-color: var(--tag-noideas-bg);
    font-family: var(--font-family-special-tag) !important;
    font-weight: 600;
    color: var(--white) !important;
    border: none;
    font-size: 0.95em;
}

```

````

```ad-info
Please note that above CSS snippet is only tested with `Blue Topaz` theme, use it with other Obsidian themes **maybe** or **maynot** be working well.
```

```ad-tip
Please reading [How to use tags with your notes with Obsidian](obsidian://open?vault=Obsidian%20Help&file=%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97%2F%E6%A0%87%E7%AD%BE%E7%9A%84%E4%BD%BF%E7%94%A8) for detailed usage of tags.
```

---