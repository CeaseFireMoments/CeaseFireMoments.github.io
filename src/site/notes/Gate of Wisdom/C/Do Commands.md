---
{"dg-publish":true,"permalink":"/gate-of-wisdom/c/do-commands/","tags":["#C","#D"],"dg-note-properties":{"tags":["#C","#D"],"Bible-References":null}}
---







```dataview
TABLE WITHOUT ID 
    link(file.link, file.name) AS "Source File", 
    item.text AS "Tagged Line"
FROM #Dos
FLATTEN file.lists AS item
WHERE contains(item.tags, "#Dos") OR contains(item.tags, "#dos")
```
