---
streak: 1
lastClicked: 2025-09-21
banner: https://i.pinimg.com/1200x/50/df/2a/50df2a87e9383eb90312eb202eee169b.jpg
icon: https://i.bobopic.com/small/89300338.jpg
---

```search-bar
show recent files
```
***

> [!dashboard] Dashboard
> > [!stats] 
> > > [!stat] Tasks Completed
> > > 0
> > 
> > > [!stat] Total Notes
> > > ```dataviewjs
> > > dv.paragraph(dv.pages("").where(p => p.file.ext === "md").length)
> > > ```
> > 
> > > [!stat] Vocabs
> > > ```dataviewjs
> > > dv.paragraph(dv.pages("").where(p => p.file.ext === "md" && p.file.path.includes("Vocabs")).length)
> > > ```
> > 
> > > [!stat] Streak
> > > ```dataviewjs
> > > dv.paragraph(dv.current().streak)
> > > ```
>
> > [!main]
> > >[!left-column,]
> > > >[!box] Quick Links
> > > > [[AP Statistics]]
> > > > [[Precalc]]
> > > > 
> > > > [[AP Bio]]
> > >
> > > > [!box]+ Links
> > > > ~~~tabs
> > > > tab: General
> > > > [ChatGPT](https://www.chatgpt.com)
> > > > ###
> > > > [Schoology](https://nsd.schoology.com)
> > > > [Grade Book](https://gradevue.org/grades)
> > > >   
> > > > tab: Math
> > > > [Desmos](https://www.desmos.com/calculator)
> > > > ###
> > > > [Precalc Textbook](https://drive.google.com/drive/u/1/folders/1F3p_P8snIwua8kjgYH9hu4FnqIQ48jYb)
> > > > 
> > > > [Stats Textbook](https://drive.google.com/drive/u/1/folders/1-lD0k192rCd4hF8gI9hXj9mVJnjG87aO)
> > > > ~~~
> > 
> > > [!right-column]
> > > > [!box] Todo [[TODO|→]]
> > > > ~~~tabs
> > > > tab: Current
> > > > a
> > > > 
> > > > tab: Planned
> > > > b
> > > > ~~~
> > >
> > > > [!box] Recently Modified
> > > > ```dataview
> > > > TABLE file.mtime AS "Last Modified"
> > > > FROM ""
> > > > WHERE file.name != "Home" AND file.name != "TODO"
> > > > SORT file.mtime DESC
> > > > LIMIT 5
> > > > ```
 
*** 
<iframe src="https://jandee.vercel.app/StormBlackthorn" width="100%" height="275px"></iframe>