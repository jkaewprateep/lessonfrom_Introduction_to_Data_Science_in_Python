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

🦭💬 Data input validation and aggregation are important in data processing, these tasks are performed to validate data and tracking of data changes and re-formatting ```verify_countrynamestring```, ```findin_countrynames```, ```renamecountry_record```. By each step is a common and transparent process, adding logging and notification methods is possibly the same as re-use some external sources of data for transform and support of data matching, joining, and data aggregation methods. </br>

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

### 🧸💬 A sample of a custom dataset function.

```
def ScimEn_DATA():

    DATA = pd.read_excel(io=filename_2)
    colnames = ["Rank","Country","Documents","Citable documents","Citations","Self-citations","Citations per document","H index"];
    for i in range(len(colnames)):
        DATA.rename(columns={i: colnames[i]}, inplace=True)
        
    ### Remove none country items
    DATA["boolean"] = DATA["Country"].apply(lambda x: remove_nonecountryrecordfromlist(x))
    DATA = DATA[DATA["boolean"] == True];
    DATA = DATA[colnames]
    ###
        
    DATA = renamecountry_record( DATA );
    DATA = verify_countrynamestring( DATA );

    for item in colnames[2:]:
        DATA[ item ] = DATA[ item ].apply(lambda x: convert_digits(x))
        
    return DATA, DATA.shape[0];
```

### 🧸💬 Using the lambda function for the external function process results in the same as the internal process is the possible way by applying lambda function.

🦤💬 There are matrix summary, and aggregation functions from Pandas, Numpy library, and sci-kit library and one way to complete this requirement without transforming data or creating a counter is to access an external function from the lambda function. </br>
💃( 👩‍🏫 )💬 Once they called a hacker function, this hacks the Pandas and working library function by accessing external function ability from its working memory. </br>
👨🏻‍🏫💬 Otherwise you need to access the evaluation matrixes by creating a custom class because you need a class initiated to work with external functions. </br>

```
def answer_eleven():
    # This function should return a DataFrame with index named Continent 
    # ['Asia', 'Australia', 'Europe', 'North America', 'South America'] and columns ['size', 'sum', 'mean', 'std']
    import statistics;
    
    ContinentDict  = {'China':'Asia', 
              'United States':'North America', 
              'Japan':'Asia', 
              'United Kingdom':'Europe', 
              'Russian Federation':'Europe', 
              'Canada':'North America', 
              'Germany':'Europe', 
              'India':'Asia',
              'France':'Europe', 
              'South Korea':'Asia', 
              'Italy':'Europe', 
              'Spain':'Europe', 
              'Iran':'Asia',
              'Australia':'Australia', 
              'Brazil':'South America'};

    dataset = answer_one();
    dataset["Continents"] = dataset.index.to_series().map(ContinentDict);
    dataset["Estimates population"] = dataset["Energy Supply"].astype("float") / dataset["Energy Supply per Capita"].astype("float");
    
    result = dataset.set_index("Continents").groupby( "Continents" )["Estimates population"].agg([ ('size', lambda x: np.size(x)), ('sum', lambda x: np.nansum(x)) ,
                                                                                                   ('mean', lambda x: np.nanmean(x)), ('std', lambda x: np.nanstd(x))
                                                                                                 ]);
    
    return result;
```

### 🧸💬 Final evaluation from the dataset.

<p align="center" width="100%">
    <img width="100%" src="https://github.com/jkaewprateep/lessonfrom_Introduction_to_Data_Science_in_Python/blob/main/01.png">
</p>

👨🏻‍🏫💬 We used C programming language in communications instruments, there are no actual continuous but discrete values with intelligence scopes. </br>
<p align="center" width="100%">
    <img width="100%" src="https://github.com/jkaewprateep/lessonfrom_Introduction_to_Data_Science_in_Python/blob/main/02.png">
</p>

- - -

### 🧸💬 Custom dataset and the datasets coefficients, find solution for source input data for prediction function and evaluation method.

🐑💬 ➰ We start by creating a custom dataset function and it can be used within the working project in Jupiter notebook, reloading the dataset value or transforming only calling the function. </br>
🦭💬 

### 🧸💬 Create a custom dataset.

```
def create_nfldataset( ):
    
    DATAtype = { "index": "int", "DSRS": "float", "L": "int", "League": "string", "MoV": "float", "OSRS": "float", "PA": "string", "PD": "int", "PF": "int", "SRS": "float", 
     "SoS": "float", "T": "int", "W": "int", "W-L%": "float", "team": "string", "year": "int", "Index": "int", "Cityname": "string" };
 
    nfl_df = pd.read_csv(filename_4)                                                      # 🧸💬 read data from .csv file.

    new_nfldf = nfl_df;                                                                   # 🧸💬 saved data to instant dataset.
    new_nfldf["team"] = new_nfldf["team"].apply(lambda x : remove_unchar(x) );            # 🧸💬 Removed none character from the input.
    new_nfldf["Index"] = new_nfldf.index                                                  # 🧸💬 Create index column from running index.

    # 🧸💬 Verify the city name input.
    new_nfldf["Cityname"] = new_nfldf["team"].apply(lambda x : nfl_find_cityname_fromteamname(x) );
    # 🧸💬 Verify the area name input.     
    new_nfldf = new_nfldf[~new_nfldf["team"].isin(["AFC North", "AFC South", "AFC West", "AFC East", "NFC East", 
                                                   "NFC North", "NFC South", "NFC West"])]
    new_nfldf = new_nfldf[new_nfldf["year"] == 2018]                                      # 🧸💬 Data records selection.   
    new_nfldf = new_nfldf.reset_index();                                                  # 🧸💬 Reset index and create new column name index.
    new_nfldf["Index"] = new_nfldf.index                                                  # 🧸💬 Assigned new index to index column.

    # 🧸💬 Read and assign key and value to new data column associated with keys name.
    ############################################################################
    ###
    for item in DATAtype.items():
        key, value = item
        new_nfldf[key] = new_nfldf[key].astype(value);
    ###
    ############################################################################    
    
    new_nfldf['team_ville'] = new_nfldf['team']                                           # 🧸💬 Assign team_ville column with team values.
    # 🧸💬 Mapping function to assign category value into team_ville column.
    new_nfldf['team_ville'] = new_nfldf['team_ville'].map({'New England Patriots':'Boston', ... });
    
    cities=pd.read_html(filename_5)[1]                                                    # 🧸💬 Create cities dataset from target filename.
    cities=cities.iloc[:-1,[0,3,5,6,7,8]]                                                 # 🧸💬 Selected columns.

    # 🧸💬 Merge dataset by the team_ville column and metropolitan area.
    new_nfldf = pd.merge(new_nfldf, cities, left_on= "team_ville", right_on= "Metropolitan area")
    # 🧸💬 Assign new column names.
    new_nfldf = new_nfldf[["team", "W-L%", "Metropolitan area", "Population (2016 est.)[8]", "year"]]
    # 🧸💬 Dataset columns selection.
    new_nfldf.columns = ["team", "W/L", "Metropolitan area", "Population", "year"]

    return new_nfldf
```
