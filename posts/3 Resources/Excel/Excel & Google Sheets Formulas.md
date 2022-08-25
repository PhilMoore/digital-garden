
# Excel & Google Sheets Formulas

### Copy all text after X

`=MID(A1,FIND(“X”,A1)+1,256`

X is the character to copy text after A1 = is the cell to query

### Copy all text before X

`=LEFT(A1,(FIND("X",A1,1)-1))`

X is the character to copy text before A1 = is the cell to query