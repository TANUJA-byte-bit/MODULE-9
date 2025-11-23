# Module 9
# 9a)  List Comprehension:Generates all even numbers between 200 and 300
##  AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

##  ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

##  PROGRAM:
```
x=int(input())
n=int(input())
y=int(input())
l=[]
for i in range(x,y+1,n):
    l.append(i)
print(l)
```

## OUTPUT:
<img width="1156" height="243" alt="image" src="https://github.com/user-attachments/assets/d558ce94-4abc-491c-8081-d007622129d2" />

## RESULT:
Program executed Successfully.
