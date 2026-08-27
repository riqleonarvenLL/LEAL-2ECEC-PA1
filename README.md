# 💻 LEAL_EXP-1-ECE2112

## ECE2112 - Introduction to Python 

##I. Intended Learning Outcomes
At the end of this laboratory activity, the student should be able to:
1. use basic Python functions, operators, and string operations;
2. manipulate strings using indexing, slicing, and built-in string methods;
3. apply sequence unpacking to manipulate the elements of a list; and
4. construct simple Python functions that return a specified result.

---
## 🚀 Getting Started
1. Open **Jupyter Notebook**
2. Create the codes needed for each question
3. Run each code cell



# PROBLEM 1 WORD ROTATION PROBLEM

#Problem 1
def rotate_word(text):
    # if only one letter, just return it
    if len(text) == 1:
        return text
    
    # move the first character to the end
    rotated = text[1:] + text[0]
    return rotated

# test cases
print(rotate_word("Python"))   # ythonP
print(rotate_word("Logic"))    # ogicL
print(rotate_word("Code"))     # odeC
print(rotate_word("A"))        # A

