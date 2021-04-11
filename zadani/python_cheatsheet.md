## Basic Python syntax

### Conditions - Podmínky

- konstrukce if .. else
``` python
# if condition:
#   condition True
# else:
#   condition False
```
- condition - comparison
  - ==, <, >, >=, <=, !=

- elif - chaining conditions
``` python
if x == 0:
    # something
else:
    if x > 0:
        # something else
    else:
        # else
        
# can be rewriten as:

if x == 0:
    # something
elif x > 0:
    # something else
else:
    # else
```
- compound conditions
``` python
if a < 0 and a % 2 == 0:
    # something
    
if a < 0 or a % 2 == 0:
    # something
```


### Cycles - Cykly
- while
``` python
# while condition:
#    body of cycle
 
i = 0
while i < 4:
  print(i)
  i += 1

# -> 0, 1, 2, 3
```
