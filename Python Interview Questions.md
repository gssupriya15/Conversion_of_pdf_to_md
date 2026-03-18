# Python Interview Questions

A list of frequently asked Python interview questions with answers for freshers and experienced are given below.

<!-- Page 1 -->

## 1) What is Python?

Python was created by Guido van Rossum, and released in 1991.

It is a general-purpose computer programming language. It is a high-level, object-oriented language which can run equally on different platforms such as Windows, Linux, UNIX, and Macintosh. Its high-level built-in data structures, combined with dynamic typing and dynamic binding. It is widely used in data science, machine learning and artificial intelligence domain.

It is easy to learn and require less code to develop the applications.

**Statistics:**
- 45.5M users
- 823 Java Try Catch references

**It is widely used for:**
- Web development (server-side)
- Software development
- Mathematics
- System scripting

---

## 2) Why Python?

- Python is an interpreted, object-oriented, high-level programming language with dynamic semantics.
- Python is compatible with different platforms like Windows, Mac, Linux, Raspberry Pi, etc.
- Python has a simple syntax as compared to other languages.
- Python allows a developer to write programs with fewer lines than some other programming languages.
- Python runs on an interpreter system, means that the code can be executed as soon as it is written. It helps to provide a prototype very quickly.
- Python can be described as a procedural way, an object-orientated way or a functional way.
- The Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms, and can be freely distributed.

---

## 3) What are the applications of Python?

Python is used in various software domains some application areas are given below.

- Web and Internet Development
- Games
- Scientific and computational applications
- Language development
- Image processing and graphic design applications
- Enterprise and business applications development
- Operating systems
- GUI based desktop applications

Python provides various web frameworks to develop web applications. The popular python web frameworks are Django, Pyramid, Flask.

Python's standard library supports for E-mail processing, FTP, IMAP, and other Internet protocols.

Python's SciPy and NumPy helps in scientific and computational application development.

Python's Tkinter library supports to create a desktop based GUI applications.

---

## 4) What are the advantages of Python?

Advantages of Python are:

### Python is Interpreted language
**Interpreted:** Python is an interpreted language. It does not require prior compilation of code and executes instructions directly.

### It is Free and open source
**Free and open source:** It is an open-source project which is publicly available to reuse. It can be downloaded free of cost.

### It is Extensible
**Extensible:** It is very flexible and extensible with any module.

### Object-oriented
**Object-oriented:** Python allows to implement the Object-Oriented concepts to build application solution.

### It has Built-in data structure
**Built-in data structure:** Tuple, List, and Dictionary are useful integrated data structures provided by the language.

### Additional advantages:
- Readability
- High-Level Language
- Cross-platform
- **Portable:** Python programs can run on cross platforms without affecting its performance.

<!-- Page 2 -->

## 5) What is PEP 8?

PEP 8 stands for **Python Enhancement Proposal**, it can be defined as a document that helps us to provide the guidelines on how to write the Python code. It is basically a set of rules that specify how to format Python code for maximum readability. It was written by Guido van Rossum, Barry Warsaw and Nick Coghlan in 2001.

---

## 6) What do you mean by Python literals?

Literals can be defined as a data which is given in a variable or constant. Python supports the following literals:

### String Literals

String literals are formed by enclosing text in the single or double quotes. For example, string literals are string values.

**Example:**

```python
# in single quotes   
single = 'JavaTpoint'   
# in double quotes   
double = "JavaTpoint"   
# multi-line String   
multi = '''Java   
           T   
               point'''   
     
print(single)   
print(double)   
print(multi)
```

**Output:**
```
JavaTpoint
JavaTpoint
Java  
           T  
               point
```

### Numeric Literals

Python supports three types of numeric literals integer, float and complex.

**Example:**

```python
# Integer literal     
a = 10     
#Float Literal     
b = 12.3      
#Complex Literal      
x = 3.14j     
print(a)   
print(b)   
print(x)
```

**Output:**
```
10
12.3
3.14j
```

### Boolean Literals

Boolean literals are used to denote Boolean values. It contains either True or False.

**Example:**

```python
p = (1 == True)   
q = (1 == False)   
r = True + 3   
s = False + 7   
     
print("p is", p)   
print("q is", q)   
print("r:", r)   
print("s:", s)
```

**Output:**
```
p is True
q is False
r: 4
s: 7
```

### Special literals

Python contains one special literal, that is, 'None'. This special literal is used for defining a null variable. If 'None' is compared with anything else other than a 'None', it will return false.

**Example:**

```python
word = None   
print(word)
```

**Output:**
```
None
```

---

## 7) Explain Python Functions?

A function is a section of the program or a block of code that is written once and can be executed whenever required in the program. A function is a block of self-contained statements which has a valid name, parameters list, and body. Functions make programming more functional and modular to perform modular tasks. Python provides several built-in functions to complete tasks and also allows a user to create new functions as well.

**There are three types of functions:**

- **Built-In Functions:** copy(), len(), count() are the some built-in functions.
- **User-defined Functions:** Functions which are defined by a user known as user-defined functions.
- **Anonymous functions:** These functions are also known as lambda functions because they are not declared with the standard def keyword.

**Example:** A general syntax of user defined function is given below.

```python
def function_name(parameters list):     
    #--- statements---     
    return a_value
```

---

## 8) What is zip() function in Python?

Python zip() function returns a zip object, which maps a similar index of multiple containers. It takes an iterable, convert into iterator and aggregates the elements based on iterables passed. It returns an iterator of tuples.

**Signature:**

```python
zip(iterator1, iterator2, iterator3 ...)
```

**Parameters:**

iterator1, iterator2, iterator3: These are iterator objects that are joined together.

**Return:**

It returns an iterator from two or more iterators.

**Note:** If the given lists are of different lengths, zip stops generating tuples when the first list ends. It means two lists are having 3, and 5 lengths will create a 3-tuple.

<!-- Page 3 -->

## 9) What is Python's parameter passing mechanism?

There are two parameters passing mechanism in Python:

- Pass by references
- Pass by value

By default, all the parameters (arguments) are passed "by reference" to the functions. Thus, if you change the value of the parameter within a function, the change is reflected in the calling function as well. It indicates the original variable. For example, if a variable is declared as a = 10, and passed to a function where it's value is modified to a = 20. Both the variables denote to the same value.

The pass by value is that whenever we pass the arguments to the function only values pass to the function, no reference passes to the function. It makes it immutable that means not changeable. Both variables hold the different values, and original value persists even after modifying in the function.

Python has a default argument concept which helps to call a method using an arbitrary number of arguments.

---

## 10) How to overload constructors or methods in Python?

Python's constructor: `__init__()` is the first method of a class. Whenever we try to instantiate an object `__init__()` is automatically invoked by python to initialize members of an object. We can't overload constructors or methods in Python. It shows an error if we try to overload.

**Example:**

```python
class student:     
    def __init__(self, name):     
        self.name = name     
    def __init__(self, name, email):     
        self.name = name     
        self.email = email     
          
# This line will generate an error     
#st = student("rahul")     
     
# This line will call the second constructor     
st = student("rahul", "rahul@gmail.com")     
print("Name: ", st.name)   
print("Email id: ", st.email)
```

**Output:**
```
Name:  rahul
Email id:  rahul@gmail.com
```

---

## 11) What is the difference between remove() function and del statement?

The user can use the remove() function to delete a specific object in the list.

**Example:**

```python
list_1 = [ 3, 5, 7, 3, 9, 3 ]    
print(list_1)   
list_1.remove(3)    
print("After removal: ", list_1)
```

**Output:**
```
[3, 5, 7, 3, 9, 3]
After removal: [5, 7, 3, 9, 3]
```

If you want to delete an object at a specific location (index) in the list, you can either use del or pop.

**Example:**

```python
list_1 = [ 3, 5, 7, 3, 9, 3 ]    
print(list_1)   
del list_1[2]   
print("After deleting: ", list_1)
```

**Output:**
```
[3, 5, 7, 3, 9, 3]
After deleting: [3, 5, 3, 9, 3]
```

**Note:** You don't need to import any extra module to use these functions for removing an element from the list.

We cannot use these methods with a tuple because the tuple is different from the list.

---

## 12) What is swapcase() function in the Python?

It is a string's function which converts all uppercase characters into lowercase and vice versa. It is used to alter the existing case of the string. This method creates a copy of the string which contains all the characters in the swap case. If the string is in lowercase, it generates a small case string and vice versa. It automatically ignores all the non-alphabetic characters. See an example below.

**Example:**

```python
string = "IT IS IN LOWERCASE."   
print(string.swapcase())   
   
string = "it is in uppercase."   
print(string.swapcase())
```

**Output:**
```
it is in lowercase.  
IT IS IN UPPERCASE.
```

