- In array to select the last item, put [-1]
```Python
my_list = [1,2,3]
print(my_list[-1])    #output will be 3
```
---
- `spe` (separate) won't work sometimes. check below.
```Python
print("Afrid"*3, sep = " ")          # output - AfridAfridAfrid
print(" ".join("Afrid" * 3))         # output - A f r i d A f r i d A f r i d
print(" ".join(["Afrid"] * 3))       # output - Afrid Afrid Afrid
```
---
