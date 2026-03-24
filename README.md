# Python Experiments

## Experiment 1: Even or Odd

### Aim
To write a Python program to check whether a given number is even or odd using if...else statements.

### Algorithm
1. Start  
2. Read a number  
3. Check `a % 2 == 0`  
4. If true, print EVEN  
5. Else, print ODD  
6. Stop  

### Program
```python
a = int(input("Enter a number: "))
if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```

### Output
```
Enter a number: 6
EVEN
```

### Result
Thus, the program to check whether a number is even or odd is executed successfully.

---

## Experiment 2: Boolean Expressions

### Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

### Algorithm
1. Assign `a = (0 == True)`  
2. Assign `b = (False == False)`  
3. Assign `c = (True + True)`  
4. Assign `d = (False + 9)`  
5. Print all values  

### Program
```python
a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```

### Output
```
a is False
b is True
c: 2
d: 9
```

### Result
Thus, the program to evaluate boolean expressions is executed successfully.

---

## Experiment 3: Character Literals

### Aim
To write a Python program to print characters using character literals.

### Algorithm
1. Start  
2. Print 'T'  
3. Print 'a'  
4. Stop  

### Program
```python
print('T')
print('a')
```

### Output
```
T
a
```

### Result
Thus, the program to print character literals is executed successfully.

---

## Experiment 4: Complex Number

### Aim
To write a Python program that reads two integers, creates a complex number, and prints its real and imaginary parts.

### Algorithm
1. Read integer `a`  
2. Read integer `b`  
3. Create complex number `x = complex(a, b)`  
4. Print `x`, `x.real`, and `x.imag`  

### Program
```python
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))

x = complex(a, b)

print("Complex number:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
```

### Output
```
Enter real part: 3
Enter imaginary part: 4
Complex number: (3+4j)
Real part: 3.0
Imaginary part: 4.0
```

### Result
Thus, the program to create and display a complex number is executed successfully.

---

## Experiment 5: Read and Print String

### Aim
To write a Python program to read a string from the user and print it.

### Algorithm
1. Read a string using input()  
2. Print the string  

### Program
```python
men_stepped_on_the_moon = input("Enter a string: ")
print(men_stepped_on_the_moon)
```

### Output
```
Enter a string: Hello
Hello
```

### Result
Thus, the program to read and print a string is executed successfully.
