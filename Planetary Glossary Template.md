---
created: <% tp.file.creation_date() %>
tags: planets
---
# [[<% tp.file.title %>]]
#### Definition:
- 
#### See Also:
- 
___
#### Upcoming Events:
```dataview
TASK
WHERE contains(tags, "#planets") AND (start.month = date(now).month OR start.month = date(now).month + 1) AND type = [[<% tp.file.title %>]]
```
___
[[Planetary Glossary]]