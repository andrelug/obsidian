---
Tags: 📝
Type: video
---

Tags:  

---
#### On this day

[[<% moment(tp.file.title).subtract(1, 'year').format("YYY-MM-DD") %>]]

#### Gratidão do dia
==Gratidão==

#### Pensamentos
- 

#### Dificuldades
- 

#### Aprendizados
- 

#### Notas do dia
```dataview
TABLE tags
FROM ""
WHERE file.ctime.year = [[<% tp.file.title %>]].file.ctime.year
AND file.ctime.month = [[<% tp.file.tiele %>]].file.ctime.month
AND file.ctime.day = [[<% tp.file.tiele %>]].file.ctime.day
SORT file.name
```

---

[[<% moment(tp.file.title).subtract(1, 'day').format("YYY-MM-DD") %>]] <== <button class="date_button_today">Today</button> ==> [[<% moment(tp.file.title).add(1, 'day').format("YYY-MM-DD") %>]]

<< [[<% tp.date.now("YYYY-MM-DD",-1,tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD"),"YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD",1,tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD"),"YYYY-MM-DD") %>]] >>