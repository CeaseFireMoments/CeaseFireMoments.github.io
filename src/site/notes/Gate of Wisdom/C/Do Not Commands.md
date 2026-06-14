---
{"dg-publish":true,"permalink":"/gate-of-wisdom/c/do-not-commands/","tags":["#D","#C"],"dg-note-properties":{"tags":["#D","#C"],"Bible-References":null}}
---





```dataview
TABLE WITHOUT ID 
    link(file.link, file.name) AS "Source File", 
    item.text AS "Tagged Line"
FROM #DoNot 
FLATTEN file.lists AS item
WHERE contains(item.tags, "#DoNot")
```
