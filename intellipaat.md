These are taken from https://intellipaat.com/blog/interview-question/python-interview-questions/#11
- What is Python?  
    - Python is a high-level, interpreted, interactive, and object-oriented scripting language. It uses English keywords frequently. Whereas, other languages use punctuation, Python has fewer syntactic constructions.
    - Python is designed to be highly readable and compatible with different platforms such as Mac, Windows, Linux, Raspberry Pi, etc.
- Python is an interpreted language. Explain.
    - An interpreted language is any programming language that executes its statements line by line. Programs written in Python run directly from the source code, with no intermediary compilation step.
- What is the difference between lists and tuples?
    |Lists|Tuples|
    |---|---|
    |Lists are mutable, i.e., they can be edited|Tuples are immutable (they are lists that cannot be edited)|
    |Lists are usually slower than tuples|Tuples are faster than lists|
    |Lists consume a lot of memory|Tuples consume less memory when compared to lists|
    |Lists are less reliable in terms of errors as unexpected changes are more likely to occur|Tuples are more reliable as it is hard for any unexpected change to occur|
    |Lists consist of many built-in functions.|Tuples do not consist of any built-in functions.|
- What is pep 8?
    - PEP in Python stands for Python Enhancement Proposal. It is a set of rules that specify how to write and design Python code for maximum readability.
- What are the Key features of Python?
    - Python is an interpreted language, so it doesn’t need to be compiled before execution, unlike languages such as C.
    - Python is dynamically typed, so there is no need to declare a variable with the data type. Python Interpreter will identify the data type on the basis of the value of the variable.
    - Python follows an object-oriented programming paradigm with the exception of having access specifiers. Other than access specifiers (public and private keywords), Python has classes, inheritance, and all other usual OOPs concepts.
    - Python is a cross-platform language, i.e., a Python program written on a Windows system will also run on a Linux system with little or no modifications at all.
    - Python is literally a general-purpose language, i.e., Python finds its way in various domains such as web application development, automation, Data Science, Machine Learning, and more.

- How is Memory managed in Python?
    - Memory in Python is managed by Python private heap space. All Python objects and data structures are located in a private heap. This private heap is taken care of by Python Interpreter itself, and a programmer doesn’t have access to this private heap.
    - Python memory manager takes care of the allocation of Python private heap space.
    - Memory for Python private heap space is made available by Python’s in-built garbage collector, which recycles and frees up all the unused memory.
-  What is PYTHONPATH?
    - PYTHONPATH has a role similar to PATH. This variable tells Python Interpreter where to locate the module files imported into a program. It should include the Python source library directory and the directories containing Python source code. PYTHONPATH is sometimes preset by Python Installer.
- What are Python Modules?
    - Files containing Python codes are referred to as Python Modules. This code can either be classes, functions, or variables and saves the programmer time by providing the predefined functionalities when needed. It is a file with “.py” extension containing an executable code.
    - Commonly used built modules are listed below:

        - os
        - sys
        - data time
        - math
        - random
        - JSON