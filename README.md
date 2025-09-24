**COMM109 Week01 Workshop1b**

Getting started:

 - Create a new GitHub account using your University of Exeter email (for use in your academic work).
 - Sign into the account
 - Goto https://classroom.github.com/a/7UFdGukz and click to accept the assignment
 - Click to Launch in CodeSpaces. You will see a web interface to CodeSpaces (based on VS Code).

When CodeSpaces opens copy and paste the following into the terminal to download the template code files:

```
curl https://github.com/phil-lewis-exe/COMM109_Week01_Workshop1b/blob/44a76037fea0fa76c63d6b875cd735c3eaaa09a1/template_code.zip -o ./template_code.zip 
unzip template_code.zip
rm template_code.zip
```
You should see four files `ex1_variables.py` - `ex4_fstrings.py` in the explorer. Double click on `ex1_variables.py` and follow the instructions below. After completing the activity please follow the instructions on ELE to save and send your work for marking.

# Workshop Week 1b

## TASK 1: Data types

**Add the answers into the template file `ex1_variables.py`. The first answer is completed as an example.**

In each case choose from `int`, `float` or `string`.

Q1. In Python the code below will create what data type?

```python
a1 = 10
```

---

Q2. In Python the code below will create what data type?

```python
a2 = 2.3
```

---

Q3. In Python the code below will create what data type?

```python
a3 = 'ninety-nine'
```

---

Q4. In Python the code below will create what data type?

```python
a4 = 7.0
```

---

Q5. In Python the code below will create what data type?

```python
a5 = 8/4
```


---

Q6. In Python the code below will create what data type?

```python
a6 = "2 + 4.3"
```



## TASK 2: Maths in Python

**Add the answers into the template file `ex2_maths.py`.**

Write Python code to perform each calculation, assigning the result into the named variable.

Display the result after each question, e.g. your code for each answer will look like:

```python
# q1
a1 = ...
print(a1)
```


If you run the code file it should just display the 8 lines of calculation results with no other output. 

---

Q1. Write Python code that performs the following calculation, storing the result as `a1`.

$$2+5+7$$

---

Q2. Write Python code that performs the following calculation, storing the result as `a2`.

$$13 \times 7$$

---

Q3. Write Python code that performs the following calculation, storing the result as `a3`.

$$4 \div 9$$

---

Q4. Write Python code that performs the following calculation, storing the result as `a4`.

$$11 \times \frac{3+8}{9} $$

---

Q5. Write Python code that performs the following calculation, storing the result as `a5`.

$$5^2 + 4$$

---

Q6. Write Python code that performs the following calculation, storing the result as `a6`.

$$\frac{3+5}{9} - 4$$

---

Q7. Write Python code that performs the following calculation, storing the result as `a7`.


$$(23 + 89) \times 6$$

---

Q8. Write Python code that performs the following calculation, storing the result as `a8`.

$$\frac{1,234,567}{89} $$

## TASK 3: Strings

**Add the answers into the template file `ex3_strings.py`.**

The following code defines some text strings as variables `s1`, `s2`, `s3`, `s4` and `s5`:

```python
s1 = "the wizard of oz"
s2 = "i am shouting!"
s3 = "ThIS CasE iS aLl MeSsed uP"
s4 = "\tHello\n\tWorld\n\t  \n"
s5 = "    Goodbyeeee!     "
s6a = "The Godfather"
s6b = "is a great film"
```

Add lines of code to the `ex3_strings.py` file to do the following, in the order given.

When completed, your file should output six lines of text.

Q1. 

Display string `s1` with each word capitalised.

---

Q2. 

Display string `s2` in upper case.

---

Q3. 

Display string `s3` in lower case.

---

Q4. 

Display string `s4` removing any trailing whitespace at the end of the string.

---

Q5. 

Display string `s5` removing any whitespace that is at the start or end of the string.

---

Q6. 

Display the strings `s6a` and `s6b` concatenated so they are joined with a space between them.



## TASK 4: f-strings

**Add the answers into the template file `ex4_fstrings.py`.**

The following code defines some variables.

```python
name = "Colin"
animal = "catepillar"
category = "cake"
flavour = "chocolate"
launch_date = 1990
fat_g = 23.6
weight_g = 625
portions = 10
```

Using f-strings to make Python display the following, inserting the variables or calculations as appropriate:

When dealing with floating point values, use a format specifier `:.1f` to display values to 1 decimal place, e.g.

```python
x = 1/3
print(f"result is {x:.1f}")

# prints
# 0.3
```

When you need to include a calculation do the calculation within the f-string e.g.

```python
print(f"In five cakes there are {5*portions} servings")
```

Q1. 

```
This is a _____ _____ in the shape of a ____.
```
(insert *flavour*, *category* and *animal*)

---

Q2. 

```
It was launched in the year ____.
```

---

Q3. 

```
A single portion weighs ____g.
```

---

Q4. 

```
If you ate a whole cake on each one of your birthdays in the 35 years since it was launched you would have consumed a total mass of ____kg of cake.
```

----

Q5. 

```
It's percentage fat is ______%
```

---

