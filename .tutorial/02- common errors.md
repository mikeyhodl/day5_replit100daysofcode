# Common Errors
*Copy each of the code blocks below with 👉 to `main.py`, click run, and see if you can fix them!
Make sure to get rid of any old code from `main.py` before you start the next one.*

## Syntax Error
👉 What is wrong with this code below?

```python
catsOrDogs = input("Are you a cat person? Or a dog person?: ")
if catsOrDogs = "cat":
  print("Meow")
else:
  print("Woof")
```
<details><summary>Answer 👀</summary>

- Our `if` statement must include `==` so it should read:
- `if catsOrDogs == "cat":`
</details>

## Syntax Error...again


👉 What is wrong with this code?

```python
catsOrDogs = input("Are you a cat person? Or a dog person?: ")
if catsOrDogs == "cat"
  print("Meow")
else:
  print("Woof")
```
<details> <summary> Answer 👀</summary>

- Our `if` statement is missing the `:`
</details>

## Indentation Error

👉 Do you see the error here?
```python
catsOrDogs = input("Are you a cat person? Or a dog person?: ")
if catsOrDogs == "cat":
  print("Meow")
else:
print("Woof")
```
<details><summary>Answer 👀</summary>

- As soon as you see a colon, the next line should be indented **one** more than the line above it.
</details>

