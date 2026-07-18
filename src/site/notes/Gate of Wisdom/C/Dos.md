---
{"dg-publish":true,"permalink":"/gate-of-wisdom/c/dos/","tags":["D","C"],"dg-note-properties":{"tags":["D","C"],"Bible-References":null}}
---


These are the Do commands. 

Usually the do commands carry a blessing when they are done. 

```dataview
TABLE L.text AS "Tagged Line"
FROM #Dos OR #dos
FLATTEN file.lists AS L
WHERE contains(L.tags, "#Dos") OR contains(L.tags, "#dos")
```



