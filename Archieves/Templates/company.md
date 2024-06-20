---
tags:
  - company
career-page: 
link:
---
## Notes

## list of jobs applied

```dataview
TABLE  rows.role as role, rows.status as status
WHERE company =  [[{{title}}]]
SORT file.ctime DESC
GROUP BY dateformat(file.ctime, "yyyy-MM") as month
```