### Cycles: 3015, Size: 16, Activity: 10

#### XA
```
LINK 800
LINK 800
LINK 800

COPY 6 T
MARK SPAWN
REPL MOVE
SUBI T 1 T
TJMP SPAWN

MARK MOVE
ADDI T 800 T
LINK T
COPY #CASH T

MARK DISPENSE
COPY 20 #DISP
SUBI T 1 T
TJMP DISPENSE
```
