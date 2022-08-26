---
company: 
location: 
email: 
aliases: 
languages: 
publish: false
---
<% await tp.file.move("2 Areas/People/Contacts/" + tp.file.title) %>
# [[<% tp.file.title %>]]


## Info & Links



## Meetings

```dataview
TABLE summary as "Summary" from "2 Areas/People/Meetings"
where contains(attendees,"<% tp.file.title %>")
sort date desc
```