---
created: <% tp.file.creation_date() %>
tags:
  - walk
---
# <%* let title = tp.file.title 
if(title.startsWith("Untitled")) { 
title = await tp.system.prompt("Date of Walk");
await tp.file.rename(title);
} 
tR += moment(title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %><% tp.file.rename(title + " - Walk") %>
#### Location::
#### Start Time::
#### End Time::
#### Weather::
#### Temperature::
#### Plants::
#### Animals::
## Notes:
- 