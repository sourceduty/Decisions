### Python_Decisions

🧠 Making simple decisions using Python.

This software is free and open-source; anyone can redistribute it and/or modify it.
#

### DECISION-MAKING

Specified procedures or decision rules are used to create a decision. Decisions are routine and repetitive. Decisions have traditionally been made by habits or procedures.

#

### OUTCOMES

An outcome defines what will happen when a decision is made. The knowledge of outcome decisions is classified into three categories.

1. Certian Decisions: 

A decision is certian when the outcome of each alternative is fully known. There is only one outcome for each alternative.

2. Risky Decisions: 

A decision is risky when there is a possibility of multiple outcomes for each alternative. A probability of occurrence can be attached to each outcome.

3. Uncertian Decisions: 

A decision is uncertian when there are a number of outcomes for each alternative and the probabilities of their occurrences are not known.

#

### PYTHON DECISIONS

In Python, simple decisions are created using the conditional sentance statements IF, ELSE and ELIF. Conditional keywords AND, NOT and OR are used to combine multiple conditions on boolean values.

Decision examples:

```
colour = "red"

if colour == "red":
    print("is red")
else:
    print("not red")
```
```
number = [0, 12, 17, 28, 30]

for number in numbers:
    if number > 25:
        print("number is above 25")
    else:
        print("number is below 25")
```
```
# Colours
yellow = 1
red = 2
blue = 3

# Input colours
colour_input1 = "1"
colour_input2 = "3"

# Yellow decision
for colour in colour_input1:
 if colour == "1":
    yellow_decision = True
 else:
    yellow_decision = False   
 if yellow_decision == True:
    print ("Yellow")
 break

```

### EXPERIMENT

```

# Decision_Data_Accumulator v1.0
# Sorting alphabetical user input with Python

# Copyright (c) 2023, Sourceduty
# https://about.me/sourceduty

# This software is free and open-source; anyone can redistribute it and/or modify it.


import re

# User input
print ("Decision Data Accumulator V1.0")
print ("------------------------------")
s = user_input = str(input("Colour word entry: "))
print ("------------------------------")

while True:
    
# Alphabetical 
 if not s.isalpha():
   print ("Please enter only alphabetical characters.")
   print ("--------------------")
   print ("Not Alphabetical.")
   print ("--------------------")
   input ("Press enter to exit.")
   decision = False

# Selection menu   
 if re.findall(r"[A-Za-z\-\']+", s):
   print ("Data accepted.")
   print ("--------------------")
   print ("1. View Decision")
   print ("2. View Decision Memory")
   print ("3. Clear Decision Memory")
   print ("-------------------")
   choice = input ("Enter function: ")
   decision = True

#--------------------------------------------------------
   
# Decision

#if decision == True:
   #if (s) == "Yellow":
    #yellow_decision = True
   #else:
    #yellow_decision = False

# Decision record

   #if yellow_decision == True:
    #decision_data = "Yellow"   
    #yellow_decision_data = True
    
#--------------------------------------------------------
    
# User input state  
   if user_input == "":
    print ("No input.")
    print ("--------------------")

    # Check input choice
   if choice in ('1', '2', '3',):
    print ("----------------------")

    if choice == '1':
        print ("Decision data here")
        print ("----------------------")
    elif choice == '2':
        print ("Decision memory here")
        print ("----------------------")
    elif choice == '3':
        print ("Decision memory cleared")
        print ("----------------------") 
        
    else:
        print ("Invalid input")     

 break

input ("Press enter to exit.")
```

### REFERENCES

[Control Statements](https://www.learnpython.dev/02-introduction-to-python/110-control-statements-looping/10-if-else-elif/)
