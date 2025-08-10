 **1. Creating Strings**
```Python
s1 = "Hello"
s2 = 'World'
s3 = """Multi-line string here"""
```
---
 
 **2. Changing Case**
```Python
text = "hello world"
print(text.upper())   # HELLO WORLD
print(text.lower())   # hello world
print(text.title())   # Hello World
print(text.capitalize())  # Hello world
```
---

**3. Removing Spaces & Characters**
```Python
txt = "   Afrid   "
print(txt.strip())   # removes spaces: "Afrid"
print(txt.lstrip())  # removes spaces from left
print(txt.rstrip())  # removes spaces from right
```
---

**4. Joining Strings**
```Python
words = ["I", "love", "Python"]
print(" ".join(words))  # I love Python
print("-".join(words))  # I-love-Python
```
---

**5. Splitting Strings**
```Python
sentence = "I-love-Python"
print(sentence.split("-"))  # ['I', 'love', 'Python']
```
---

**6. Replacing Text**
```Python
text = "I like Java"
print(text.replace("Java", "Python"))  # I like Python
```
---

**7. Finding Text**
```Python
text = "Hello World"
print(text.find("World"))  # 6
print(text.find("Afrid"))  # -1 (not found)
```
---

**8. Checking Content**
```Python
word = "Python3"
print(word.isalpha())   # False (because of the '3')
print(word.isdigit())   # False
print("123".isdigit())  # True
print("hello".isalpha()) # True
print("abc123".isalnum()) # True
```
---

**9. String Slicing**
```Python
text = "Hello World"
print(text[0:5])   # Hello
print(text[:5])    # Hello
print(text[6:])    # World
print(text[-5:])   # World
```
---

**10. String Formatting**
```Python
name = "Afrid"
age = 20
print(f"My name is {name} and I am {age} years old.")
print("My name is {} and I am {} years old.".format(name, age))
```
---
