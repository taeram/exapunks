### Cycles: 53, Size: 14, Activity: 2

#### XA
```
GRAB 300
COPY F M
```

#### XB
```
LINK 800
LINK 800
GRAB 237
COPY M X

MARK LOOP
TEST F = X
FJMP LOOP

SEEK -1
VOID F
```
