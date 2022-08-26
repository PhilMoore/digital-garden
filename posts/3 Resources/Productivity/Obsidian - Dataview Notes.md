

## Write Dataview Syntax Arguments. 

E.g. file.mtime.day AS Day = this renames the field displaying from file.mtime.day to Day


**Example**
```
dataview
table description as "Description" from "Exandya"
WHERE type "place"
SORT file. name ASC`
```
