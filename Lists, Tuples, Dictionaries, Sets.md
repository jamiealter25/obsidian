#### 1. Lists – _Ordered, Changeable, Allows Duplicates_
- A list can store multiple items.
- Items can be **changed**.
- Keeps the order you put them in.
- Allows duplicates.
```Python
my_list = [1, 2, 3, 2]
print(my_list[0])     # Access first item
my_list[1] = 10       # Change value
print(my_list)        # 1  or  [1, 10, 3, 2]
```
---

#### 2. Tuples – _Ordered, Unchangeable, Allows Duplicates_
- Like lists, but **cannot be changed** after creation.
- Useful for fixed data.
```Python
my_tuple = (1, 2, 3, 2)
print(my_tuple[0])    # 1
my_tuple[1] = 10      # This will give an error
```
---

#### 3. Dictionaries – _Key-Value Pairs, Changeable, No Duplicate Keys_
- Store data in `{key: value}` format.
- Keys are unique; values can be anything.
```Python
my_dict = {"name": "Afrid", "age": 20}
print(my_dict["name"])       # Access value by key
my_dict["age"] = 21          # Change value
my_dict["city"] = "Dhaka"    # Add new key-value
print(my_dict)               # Afrid {'name': 'Afrid', 'age': 21, 'city': 'Dhaka'}
```
---

#### 4. Sets – _Unordered, No Duplicates_
- Store unique items.
- No guaranteed order.
```Python
my_set = {1, 2, 3, 2}
print(my_set)   # Duplicates removed automatically    # {1, 2, 3}
my_set.add(4)   # Add new item print(my_set)          # {1, 2, 3, 4}
```
---

**Quick Summary Table**

|Type|Ordered?|Changeable?|Allows Duplicates?|Syntax Example|
|---|---|---|---|---|
|List|✅|✅|✅|`[1, 2, 3]`|
|Tuple|✅|❌|✅|`(1, 2, 3)`|
|Dictionary|✅(3.7+)|✅|❌(keys) ✅(values)|`{"a": 1}`|
|Set|❌|✅|❌|`{1, 2, 3}`|

---
