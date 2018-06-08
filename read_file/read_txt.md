## Case 1 - Read line by line 
```py
with open('file.txt') as f:
    for row in f:
        print(row.strip())
```

```py
with open('file.txt') as f:
    row = f.readline()
```

## Read all lines

```py
with open('file.txt') as f:
    rows = f.readlines()
```