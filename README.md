# University of Michigan - Introduction to Data Science in Python - notes
University of Michigan - Introduction to Data Science in Python

## This note aims to study the introduction to a data science project and an example of the data model, problem-to-solution, evaluation, programming technique, and communication messages. There are joint co-ordinated of C programming and Python in message communication and pattern events you can observe is build message format this note is created to reveal the secret of transferred knowledge.

### 🧸💬 Problem and expectations.
🧸💬 The capital is the head of the resonance, name, city, sources, map, and method. </br> 
🦭💬 Now you count map 🗺️ and method 🛣️ ⁉️ </br> 
🐯💬 Once we called it harmonic resonances because it presents recognition and reputation in the name we are pronounced. </br> 

### 🧸💬 Regular expressions

```
import re

simple_string = "💂🏽💬 DekDee and their ten principal rules, the work on believe religion and traditional with good trials, they honest to work, parent, friends and responsible to their commitment, they work transparent and result tracing indicated of work and document behaviors ... ";

# 🧸💬 Regular expression, name of person, place, vehicle and objects are 
# express by themself. They can be subject of the sentence and identify
# among group of the same or different purpose.

expression = r'([A-Z][a-z]\w+)'
_temp = re.findall(expression, simple_string)
```

### 🧸💬 Output

```
DekDee
```
