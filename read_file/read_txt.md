# Read TXT File

<!-- TOC -->

- [Read TXT File](#read-txt-file)
  - [Case 1 - Read line by line](#case-1---read-line-by-line)
  - [Case 2 - Read all lines](#case-2---read-all-lines)

<!-- /TOC -->

## Case 1 - Read line by line 
* use for
```py
with open('file.txt') as f:
    for row in f:
        print(row.strip())
```
* Use while
```py
with open('file.txt') as f:
    row = f.readline()
    while row!='':
        row = f.readline()
```

## Case 2 - Read all lines

```py
with open('file.txt') as f:
    rows = f.readlines()
```