---
UID: 202111071913
alias: Customized Table Styles 
tags: Tables, CSS snippets, obsidian 
source: https://forum.obsidian.md/t/custom-css-for-tables-5-new-styles-ready-to-use-in-your-notes/17084

created: 2022-04-07 15:08
updated: 2022-04-07 15:08
---

##   Customized Table Styles

### Purple Red Title Table

`cssclass:purpleRed`

![](https://forum.obsidian.md/uploads/default/original/2X/2/2a323ac1ae04363c67a3888ae1017048e61a358c.png ")

### Three Lines Title Table (Latex-like Table)

`cssclass:academia`

![](https://forum.obsidian.md/uploads/default/original/2X/3/3698b05ba1686f75edd818d83ee8004521f7b97f.png )

### Black Text on Yellow Title Table

`cssclass: yellowCab`

![](https://forum.obsidian.md/uploads/default/original/2X/4/496148820a573990ba86cdde2787626b646635db.png )

### Red Text on White Title Table

`cssclass: whiteRed`

![](https://forum.obsidian.md/uploads/default/original/2X/8/89b4baf17cd86e43df53f4b267b156f12bb78dec.png )

### Flat Blue Title Table

`cssclass:flatBlue`

![](https://forum.obsidian.md/uploads/default/original/2X/5/5450179846690297d479cd1334fb99982af366f5.png)

### Round-Conner Title Table

`XXX-rounded`
With adding more CSS declaration,  round-conner title tables are also available, such as you put `cssclass: whiteRed, whiteRed-rounded, wideTable` in `YAML`

![](https://forum.obsidian.md/uploads/default/original/2X/8/8966ab854b8c103e23c8a532b0e4bd16453692e5.png )

```ad-info

Please not `wideTable` will set the talbe to take all the widthness of your page(notes) , it can be used will all these `YAML`s together to get desirable resaults
```

Other  `YAML "cssclass:" ` includes:
###  `leftAlign` 
-   `leftAlign`- Some themes using `RTL` in tables, with this `YAML` you can force text left aligned.
- ###  `centerAlign`
-   `centerAlign`- as it says.
### First Column Width Fixed Table
-   `fixedFc`- Using it to fix the first column width. Especially when date or short texts in the first column. **Please NOTE it can not be used with `wideFc`!**
### Widen the First Column Table 
-   `wideFc`- if the first column with long text, and you do not want to wrap it, use `wideFc`.  for example, the dataview get file name to show at first column. **Please NOTE it can not be used with `fixedFc`!**
### Margins between Tables     
-   `customMargin`- will have some blanked margins between table and content.

---

**HOW to Use These Customized Style Tables**：

1.  Put the file `TableStyles.css` in to your `css snippets` folder, `app/YourValutName/.obsidian/snippets/
2. Enalbe it in `Settings`>`Apperences`>`CSS Snippets`>`TableStyles`
3.  Make declaration in note `YAML` with `cssclass:` *code* like below:
   
```
---
   cssclass: purpleRed, fixedFc
---
```

## Examples of Tables
### Default style table
![[01 - Default Table]]
### Purple Red style table
![[02 - PurpleRed]]
### Flat Blue style table
![[03 - FlatBlue]]
### Latex-like Three lines style table
![[04 - Latex like]]
### White Red Round-Connery style table
![[05 - White red rounded]]
### White Red style table
![[05 - White red]]
### Black Text on Yellow style table
![[06 - Yellow cab]]
### Default Centered style table
![[07 - Center Table]]