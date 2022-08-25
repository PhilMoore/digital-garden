

## Write Dataview Syntax Arguments. 

E.g. file.mtime.day AS Day = this renames the field displaying from file.mtime.day to Day


**Example**
```
dataview
table description as "Description" from "Exandya"
WHERE type "place"
SORT file. name ASC`
```


## Waiting Projects
```dataview
table summary as "Summary" from "1 Projects/Work"
where contains(tags,"waiting")
SORT date ASC
```


## Open Projects
```dataview
table summary as "Summary" from "1 Projects/Work"
where contains(type,"project")
SORT date ASC
```

## Upcoming Projects
```dataview
table summary as "Summary" from "1 Projects/Work"
where contains(tags,"upcoming")

SORT date ASC
```

## Ongoing Projects
```dataview
table summary as "Summary" from "1 Projects/Work"
where contains(tags,"ongoing")

SORT date ASC
```


## Meetings
```dataview
TABLE date as "Date", summary as "Summary" from "2 Areas/People/Meetings"
where contains(type,"meeting")
sort date desc
```
