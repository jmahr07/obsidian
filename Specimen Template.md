---
created: <% tp.file.creation_date() %>
tags:
  - specimen
parent: "[[Specimen Collection]]"
---
# [[<% tp.file.title %>]]
| `=this.genus` `=this.species`                                                                        | `=this.common-name`                                                                                                                                                                                                                                                                                                             |
| :--------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `=choice(this.photo, replace(string(this.photo), "]]", " \| 200]]"), "This specimen has no photo.")` | This specimen was collected at `=join(list("[", this.latitude, ",", this.longitude, "](https://gps-coordinates.org/my-location.php?lat=", this.latitude, "&lng=", this.longitude, ")"), "")` on `=dateformat(this.collection-date, "MMMM dd, yyyy")`.<br><br>**Location Description:**<br><br><br>**Specimen Description:**<br> |
> [!taxon]- Taxonomic Information
> Kingdom:: 
> Genus:: 
> Species:: 
> Specimen:: 
> Common Name:: 

> [!collection]- Collection Information
> Collection Date:: 
> ID:: [[<% tp.file.title %>]]
> Latitude:: 
> Longitude:: 
> Captive:: 

> [!photo]- Photos
> Photo::
