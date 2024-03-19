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
🐆🐾💬 I have knowledge in telecommunication and this is from C programming master. </br> 
🥺💬 I am a fan of the developer's website, I read and saw that you compared for column string method and dictionary about 15 years ago and compared of composed ```message communication APIs``` they had developed. </br> 
🐐💬 This course is a good course he added programming and experience into assignments you need to learn and follow. </br>
👧💬 🎈 He says he do not know what is the APIs he doing but that creates influence work and continues...  </br>

```
message = {}
if len(hostname.strip()) > 0:                          # 🧸💬 Enclosed variable value fro message communication attributes.
    message["host"] = hostname.strip();
else:
    message["host"] = '-'
if len(username.strip()) > 0:                          # 🧸💬 Enclosed variable value fro message communication attributes.
    message["user_name"] = username.strip();
else:
    message["user_name"] = '-'
message["time"] = temp;
message["request"] = request.strip();                  # 🧸💬 Enclosed variable value fro message communication attributes.

result.append(message)                                 # 🧸💬 Composed message communication for send on current channel or
                                                       # saved to console.log.
```

### 🧸💬 From the course validation method.

```
assert len(logs()) == 979

one_item={'host': '146.204.224.152',
  'user_name': 'feest6811',
  'time': '21/Jun/2019:15:45:24 -0700',
  'request': 'POST /incentivize HTTP/1.1'}
assert one_item in logs(), "Sorry, this item should be in the log results, check your formatting"
```

### 🥺💬 I had took a time on the assignment 2 a lot because I need to read from the requirements data from PDF file and working on assumption before complete the questions assignments and submit at the first round before found that is not the same expectations, now we have guide scopes for second submitting.

🐑💬 ➰ His notes is long and messy but that is because of he study from the examples and working documents. There is no right or wrong questions in real-life we need to summarize, proved and evaluate before present to customer and evaluating from their assumption for development. </br>
🐐💬 There are some remarks points and indicators in the note that may be he needs to see the example or explanation from the source of the project. </br>

```
###########################################################
# CBF_01 – child ever fed breast milk
# Yes : 1
# No  : 2
# Don’t know : 3
# Missing : 4
# * Data has 4 types 
# * Mapping by assuming order label priority
# Sample = { 1, 2, 77, 99}
# ---------------------------------------------------------
# VFC_ORDER – do child’s providers order vaccines for
# children from state/local health department? (introduced
# in 2006)
# All providers : 1.0
# Some but not all providers : 2.0
# No providers : 3.0
# Unknown : 4.0
# * Data has 4 types 
# * Mapping by assuming order label priority
# Sample = { 1.0, 2.0, 3.0, 4.0, NA}
# ---------------------------------------------------------
# REGISTRY - is based on responses to IHQ question 7 and 
# indicates whether the child’s vaccination
# providers reported the child’s vaccinations to a local 
# or state immunization registry (also known as an
# Immunization Information System, or IIS).
# all providers : 1
# some but possibly or definitely not all providers : 2
# no providers : 3
# unknown : 4
# * Data has 4 types 
# * Mapping by assuming order label priority
# Sample = { 1.0, 2.0, 3.0, 4.0, NA}
# ---------------------------------------------------------
# SEQNUMHH and SEQNUMC are the unique household and child identifiers
# variable identifies the children with adequate provider data (PDAT=1)
#
###########################################################  
```

### 🧸💬  Eumurates is a convenience way from their experience.

```
for idx, item in enumerate(EDUC1_data["EDUC1"]):
    EDCU1 = _temp["EDUC1"].loc[idx];
    number = _temp["Number"].loc[idx];
    ratios = number / _total
    data[label[idx]] = ratios;

return data
```

### 🧸💬 Correlation value and possibility values.

🐑💬 ➰ This is a fast way to select variables to work with regression problems to find solutions by varying the input variables. </br>
👧💬 🎈 We have read about confusion matrix, ANOVA, F-scores, and variance, and the correlation is a single variable determination method and they can work with multiple variables by selection method.  </br>

```
import scipy.stats as stats

# 🧸💬 Find correlation and possibility value from data in column 1 and column 2.
corr, pval=stats.pearsonr(new_df["column 1"], new_df["column 2"])
```

### 🧸💬 Create a custom dataset from a custom function.

### 🧸💬 Data cleaning functions.

🐑💬 ➰ It is important to find and match data for tabular data information and data joining, filters, selection, and aggregation are easier in the later step because of no duplicated conditions to create. </br>

### 🧸💬 Digits remover.

🦭💬 Expectations of the name of the country, streets, display and representing name and geographic and world news play some condition require. In some example of the Republic of Congo and Laos, they had many of their names present in experiment datasets and needed to be matched for the data aggregation function to work correctly.  </br>

```
def verify_countrynamestring( DATA ):
    
    DATA["Country"] = DATA["Country"].apply(lambda x: remove_digits(x))
    
    return DATA
```

### 🧸💬 Country name validator.

🐐💬 Monitoring and validate of the input data and aware of updated data from the dataset can be performed on this function, the observation function. Reading though the input validator can create of notification or message log for notice of change from the online sources and update from internal sources if there any change of the scopes will be notified to handles in the correct way or information. </br>

```
def findin_countrynames( string_input ):
    
    country_name =[ "China", "United States", "Japan", "United Kingdom", "Russian Federation", ... ]

    if string_input.strip() in country_name :
        return True;
    else:
        return False;
```

### 🧸💬 Re-name country name.

💃( 👩‍🏫 )💬 This function will require even it is used of string expression and regular expression but the final report is present at the customer end as they can create feedback reports from the result and validate by joining them and work on internal and external data source validation. This function is to make sure that external sources or internal sources have the same expectations for working comfortably for customers. </br>

```
def renamecountry_record( DATA ):

    current_countryname = ["Republic of Korea", "Korea, Rep.", "United States of America", "United States", ... ];
    
    new_countryname = ["South Korea", "South Korea", "United States", "United States", "United Kingdom", ... ];
    
    for idx, countryname in enumerate(current_countryname):
        DATA.loc[DATA['Country'] == current_countryname[idx], "Country"] = new_countryname[idx]
    
    return DATA
```
