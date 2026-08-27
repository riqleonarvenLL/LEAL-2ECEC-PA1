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

def rotate_word(text):
    
    if len(text) == 1:
        return text
    
  
    rotated = text[1:] + text[0]
    return rotated


        print(rotate_word("Python"))   
        print(rotate_word("Logic"))    
        print(rotate_word("Code"))     
        print(rotate_word("A"))        


# PROBLEM 2 USERNAME BUILDER PROBLEM


def make_username(first_name, last_name):

    first = first_name.lower()
    last = last_name.lower()
    
    first = first.replace(" ", "")
    last = last.replace(" ", "")
    
    return first + "." + last


        print(make_username("Arven", "Leal"))        
        print(make_username("Raiya", "Aestelle"))         
        print(make_username("Clarence Jasmine", "Gadacho"))   

# PROBLEM 3 BOOKEND SWAP PROBLEM

        def swap_bookends(items):
    
    first, *middle, last = items
    
    return [last] + middle + [first]

        print(swap_bookends([10, 11, 12, 13, 14, 15]))      # [15, 14, 13, 12, 11, 10]
        print(swap_bookends(["Digital", "Signals", "Communication"])) # ["Communication", "Signals", "Digital"]
        print(swap_bookends([7, 6]))                   # [6, 7]

