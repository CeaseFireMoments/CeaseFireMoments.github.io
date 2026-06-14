---
{"dg-publish":true,"permalink":"/gate-of-wisdom/gate-of-wisdom/","tags":["#home","#GateWisdom"],"dg-note-properties":{"tags":["#home","#GateWisdom"]}}
---

Check out the Index Pages for quicker navigation.

Behind the Gate of Wisdom you'll find general information about various topics. Think Wiki pages.  A variety of Source and Resource listings. Definitions, background information, indexes, etc. 

![Asset Gate of Wisdom.png](/img/user/_Assets/attachments/Asset%20Gate%20of%20Wisdom.png)

```dataview

TABLE WITHOUT ID file.link as "Table of Content"
FROM ""
WHERE dg-publish = true AND contains(file.tags, "GateWisdom") AND dg-home = false AND !contains(file.tags, "TheScrolls")
SORT file.name ASC
```