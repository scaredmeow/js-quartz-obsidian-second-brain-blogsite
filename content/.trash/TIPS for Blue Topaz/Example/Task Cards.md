## Notes
> Task lists can be obtained through dateview syntax, or through tasks plugin
This note shows how to use tasks plugin to get task lists

```ad-tip
Using tasks plugin, by input @ to use nature language date format. Such as:

`@today` 
`@in 3 days`  
`@3 days ago`  
```

## Tasks Lists
`````ad-flex
%% ad 语法格式书写 %%
````ad-caution
title: Overdue Tasks

```tasks
not done
due before  today
path does not include "88-Template"
short mode
```

````

````ad-check
title: Due today

```tasks
not done
due on  today 
path does not include "88-Template"
short mode
```
````
`````

`````ad-flex
%%也可以用callout 格式书写 %%
> [!CHECK] Tasks due in 3 days
> ```tasks
not done 
due after today
due before in 3 days 
path does not include "88-Template"
short mode
>```



````ad-todo
title: Tasks due in 2 weeks
```tasks
not done 
due after today
due before in two weeks
path does not include "88-Template"
short mode

```
````

`````


## Tasks
- [ ] Reading 2 books 📅2022-03-21
- [ ] Hand over works📅2022-04-21 
- [ ] Filing project documentations📅2022-04-27 
- [ ] Finish python 10 lessons📅2022-05-03
- [ ] First draft of paper 📅 2022-05-01 

````ad-example
title: Using dataviewjs to filter overdue tasks

```dataviewjs
function overdue(t) {
  let dValidate = moment(t.text, 'YYYY-MM-DD', true);
  let d = moment(t.text, 'YYYY-MM-DD');
  let containsValidDate = dValidate._pf.unusedTokens.length==0 ;
  let isOverdue = d.diff(moment()) <= 0;
  return (containsValidDate && isOverdue);
}

dv.taskList(dv.pages("").file.tasks
	.where (t => overdue(t))
	.where (t => !t.completed))

```
````


 