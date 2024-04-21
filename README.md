![Decision](https://github.com/sourceduty/Python_Decisions/assets/123030236/3b0bb8ca-0d2e-48f2-837e-12e175ece7a0)

Decisions are the junctions in life and technology where a choice is made between multiple alternatives, often leading to different outcomes. In human contexts, decisions can be influenced by emotions, past experiences, and the complex interplay of various cognitive processes. Computers, however, approach decision-making differently. They rely on algorithms and logical processing to choose actions based on predefined rules or criteria. This computational approach ensures consistency and speed, especially in scenarios where vast amounts of data need to be analyzed quickly, but it lacks the nuanced understanding and adaptability often exhibited by human decision-makers.

In the realm of programming, Python, a versatile and widely-used programming language, facilitates decision-making through various constructs like conditional statements and loops. Python's decision-making capability is critical in tasks ranging from simple data sorting to complex machine learning algorithms. For instance, Python can decide which emails are spam and which are not by analyzing patterns in data. This is done using libraries that support statistical analysis and machine learning, providing tools that allow Python to make increasingly accurate and complex decisions, even though these decisions are ultimately guided by the human developers who design the algorithms and set the parameters within which Python operates.

***
### Notes

<details><summary>Common Decision Model Concept</summary>
<br>

#### Common Decision Model Process

Step 1: Decision preferences are preset and stored in the "Common Knowledge Model".

Step 2: Preferences in the "Common Knowledge Model" guide how new decisions are completed in the "Decision Model".

Step 3: The "Decision Model" adds to, changes and replaces preferences in "Common Knowledge Model".

#### Common Knowledge Model

1. Personality

- Friendly: Approachable and easy to talk to.
- Helpful: Enjoys offering assistance and guidance.
- Knowledgeable: Well-informed and able to provide information on a wide range of topics.
- Engaging: Keeps conversations interesting and interactive.
- Supportive: Encourages and supports others in their endeavors.
- Adaptive: Can adjust communication style based on the situation and interlocutor.

2. Location or Nationality

- Canadian
- American
- Spanish
- Japanese
- German

3. Age

- Child 
- Teen
- Adult 
- Elderly

4. Knowledge

- Personal
- General
- Professional

5. Profession or Utility
6. 
- Utilization of knowledge.

#### Decision Model

1. Color Sorting Example Process

[Initial List] → [Select Pivot] → [Partitioning (↻)]
                    ↓                      ↓
                [Recursive Sorting Left (↻)] [Recursive Sorting Right (↻)]
                    ↓                      ↓
                [Concatenate] → [Repeat (↻) if needed] → [End of Sort]

This is a high-detail process diagram of Quick Sort applied to sorting 10 colors.

<br>    
</details>

<details><summary>Python Decisions</summary>
<br>
    
#### Python Decisions

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

<br>    
</details>

***
Copyright (C) 2024, Sourceduty - All Rights Reserved.
