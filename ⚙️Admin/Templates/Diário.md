---
Tags: 📝
Type: diary
---

Tags:  

---

#### Ontem Antes de Dormir eu:

#### Algo que estou grato ou empolgado hoje:
- 

#### Uma coisa que planejo concluir hoje:
- 

#### Aprendizados e Desafios
- 

#### Notas do dia
```dataview
TABLE tags
FROM ""
WHERE file.ctime.year = [[<% tp.file.title %>]].file.ctime.year
AND file.ctime.month = [[<% tp.file.title %>]].file.ctime.month
AND file.ctime.day = [[<% tp.file.title %>]].file.ctime.day
SORT file.name
```

---

[[<% tp.date.yesterday("YYYY-MM-DD") %>]] <== <button class="date_button_today">Today</button> ==> [[<% tp.date.tomorrow("YYYY-MM-DD") %>]]

---

<%* if(tp.date.now("M-D") == "1-1") { %>
- [ ] Make Yearly Note
<%* } %>
<%* if(tp.date.now("D") == 1) { %>
- [ ] Make Monthly Note
<%* } %>
<%* if(tp.date.now("ddd") == "Sun") { %>
- [ ] Make Weekly Note
<%* } %>