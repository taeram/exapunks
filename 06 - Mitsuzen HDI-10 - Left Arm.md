### Cycles: 241, Size: 23, Activity: 6

#### XA
```
LINK 800

MARK LOOP
COPY #NERV X
TEST X < -120
TJMP LOW
TEST X > 50
TJMP HIGH

COPY X M
JUMP LOOP

MARK LOW
COPY -120 M
JUMP LOOP

MARK HIGH
COPY 50 M
JUMP LOOP 
```

### XB
```
LINK 800
LINK 1
LINK 1
LINK 1
LINK 1
MARK LOOP
COPY M #NERV
JUMP LOOP
```
