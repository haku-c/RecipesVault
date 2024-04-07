Hard Recipes
```dataview
TABLE WITHOUT ID link(file.link, default(file.aliases[0], file.name)) AS "File"
 FROM #hard
sort desc
```