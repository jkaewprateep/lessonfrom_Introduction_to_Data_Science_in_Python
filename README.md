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

### 🧸💬 Communication message, using by C and Python to create communication communicates the message as a string.

🐑💬 ➰ When debugging some programmers ask me why I am using string columns as communication message templates, that is because of my understanding communication messages match string conversations working for services and programs in the solution. I had someone help me with development and he proposed the idea of using a dictionary for communication messages. </br> 
🐆💬 I have knowledge in telecommunication and this is from C programming master. </br> 
🥺💬 I am a fan of the developer's website, I read and saw that you compared for column string method and dictionary about 15 years ago and compared of composed message communication APIs they had developed. </br> 
🐐💬 This course is a good course he added programming and experience into assignments you need to learn and follow. </br>

```
message = {}
if len(hostname.strip()) > 0:
    message["host"] = hostname.strip();
else:
    message["host"] = '-'
if len(username.strip()) > 0:
    message["user_name"] = username.strip();
else:
    message["user_name"] = '-'
message["time"] = temp;
message["request"] = request.strip();

result.append(message)
```

### 🧸💬 From the course validation method.

```
assert len(logs()) == 979

one_item={'host': '146.204.224.152',
  'user_name': 'feest6811',
  'time': '21/Jun/2019:15:45:24 -0700',
  'request': 'POST /incentivize HTTP/1.1'}
assert one_item in logs(), "Sorry, this item should be in the log results, check your formating"
```
