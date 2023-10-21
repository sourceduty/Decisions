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

An decision is uncertian when there are a number of outcomes for each alternative and the probabilities of their occurrences are not known.

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

### REFERENCES

[Control Statements](https://www.learnpython.dev/02-introduction-to-python/110-control-statements-looping/10-if-else-elif/)
