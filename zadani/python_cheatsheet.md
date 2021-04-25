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
- for
``` python
# for variable in range(number):
#     body of cycle

for i in range(4):
  print(i)

# -> 0, 1, 2, 3

# for variable in range(min, max, step):
#     body of cycle
  
for i in range(2, 9, 2):
  print(i)
  
# -> 2, 4, 6, 8

# for element in someting_iterable:
#     body of cycle

# strings or arrays are iterable

s = "abc"
for letter in s:
  print(letter)

# -> a, b, c
```

