---
publish: false 
---
<% await tp.file.move("/2 Areas/Reflection - Phil/Daily/" + tp.file.title) %>
# <% tp.date.now("dddd, MMMM D, YYYY",0, tp.file.title) %>

< [[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>|Yesterday]]

## Daily Review

### 📕 Day Log & Review




### 🗓 Tomorrow, I need to...




## Direction
![[Weekly Review - W<% tp.date.now("ww",-6), %> <% tp.date.now("MMMM") %>#<% tp.date.now("YYYY") %>-W<% tp.date.now("ww",-6), %> Goals]]


---

[[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>|Tomorrow]] >