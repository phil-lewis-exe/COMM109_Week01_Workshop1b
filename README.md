**COMM109 Week01 Workshop1b**

Getting started:

 - Goto https://github.com/signup and create a new GitHub account using your University of Exeter email (for use in your academic work).
 - Sign into the account 
 - Goto https://classroom.github.com/a/7UFdGukz and click to accept the assignment
 - Click to Launch in CodeSpaces. You will see a web interface to CodeSpaces (based on VS Code). It may take a couple of minutes to initialise.

When CodeSpaces opens copy and paste the following into the terminal to download the template code files:

```
wget https://github.com/phil-lewis-exe/COMM109_Week01_Workshop1b/raw/refs/heads/main/template_code.zip
unzip template_code.zip
rm template_code.zip
```

You should see four files `ex1_variables.py` - `ex4_fstrings.py` in the explorer. Double click on `ex1_variables.py` and follow the instructions below. After completing the activity please follow the final instructions at the bottom to save and submit your work for grading via GitHub.

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

## Submitting your work

### Committing Your Changes to GitHub via the Terminal

The final step is to save your work back to the GitHub Classroom repository for marking. 

We will do this by typing `git` commands in the terminal. This process is called "committing" and "pushing" your work from your CodeSpace to your GitHub code repository (you can find a list of the code repositories you have created on the http://github.com website. 

1. **Check the Status:** First, we can check the differences between the files you have worked on in the CodeSpaces IDE and the GitHub repository. In your terminal, type the `git status` command to see the files that have been created or modified.
   
   ```bash
   git status
   ```
   This will show you that the files you have worked on have been "modified" or created in which case they are listed as an "untracked file".

3. **Stage Your Changes:** Before you can commit a file, you need to add it to the "staging area". This tells Git exactly which changes you want to include in the next snapshot.
   * To add one specific file, you would use: `git add ex1_variables.py`
   * If you have changed multiple files and want to stage them all, it's more efficient to use a period (`.`), which means "all files in the current directory and subdirectories".
   ```bash
   git add .
   ```

4. **Commit the Changes:** Now, take a snapshot of the staged changes. This is called a commit. It's important to include a descriptive message about the work you did using the `-m` flag.
   ```bash
   git commit -m "Completed workshop 1.1b"
   ```
   Git will confirm that the commit has been made.

5. **Push to GitHub:** The commit is saved locally in your Codespace. The final step is to "push" it up to your personal forked repository on GitHub.com.
   ```bash
   git push
   ```
6. **Check your work has been submitted to GitHub:** Find the repository which should be listed on your http://github.com user page. Check that the files and code have been saved. If there is an issue get in touch with the teaching team who should be able to help. This week your work is not being assessed as part of you portfolio, but in future weeks is will be.
