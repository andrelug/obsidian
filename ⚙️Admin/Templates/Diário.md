---
Tags: 📝
Type: video
---

Tags:  

---
#### On this day

[[<%tp.date.now("YYYY-MM-DD", -365)%>]]

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

[[<% tp.date.yesterday("YYYY-MM-DD") %>]] <== <button class="date_button_today">Today</button> ==> [[<% tp.date.tomorrow("YYYY-MM-DD") %>]]