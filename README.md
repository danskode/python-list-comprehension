# Python List Comprehension

## Formål
Formålet med dette repository er at give en kort og praktisk introduktion til **list comprehensions i Python**.
Det skal bruges som præsentationsmateriale til enmundtlig eksamen i Introduktion til Python.

## Indhold
Projektet kommer til at bestå af jupyter notebooks, der viser:
- Hvad en list comprehension er
- Hvordan den kan erstatte traditionelle `for`-loops
- Simple og letforståelige eksempler

## Forudsætninger
- Et semesters undervisning Intruduktion til Python
- Kendskab til lister og `for`-loops

## Eksempler
Eksempel:
```python
# Traditionel måde
numbers = []
for x in range(10):
    numbers.append(x * 2)

# List comprehension
numbers = [x * 2 for x in range(10)]
