# Basic Python Exercise
# This is a simpler lab assignment often given to classes that are not focused on programming. You can use it instead for practice. We will then go through the answers during class.

## Description:
You should answer the questions. You will either need to respond with text, code, or both. 
You can use comments in Python to write text with the # (hashtag symbol).
Or, you can create a markdown block and then write text.
To add code, you can write:

\```python 

Code goes here

\```

# Example Question & Answer:

What is a list, and why is it important? Answer with text and code.

Answer:
Lists are useful because we can group data in a logical way. Without lists, we would need to save everything in individual variables, which is not scalable for an application. For example, what happens if we have 100,000 students, and each needs a variable?

\```python
# Inefficient:
student_1 = "Tobias"
student_2 = "Alfred"
student_3 = "Elina"
student_4 = "Jessica"

# Better
students = ["Tobias", "Alfred", "Elina", "Jessica"]
student_1 = students[0]
\```
