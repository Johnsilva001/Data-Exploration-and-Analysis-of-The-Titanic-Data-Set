# Group5-Python-Assignment

Visualisation and Analysis of Titanic Dataset

## Data Source <br>
[Titanic Datasets](https://www.kaggle.com/competitions/titanic/data)

## Data Description <br>
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

Titanic Data - Contains demographics and passenger information from 891 of the 2224 passengers and crew on board the Titanic.


 | Variables | Definition    | Key
| ----------- | ----------- | ----------- | 
| Survived | Survival | 0 = No, 1 = Yes
| Pclass   | Ticket class| 1 = First Class, 2 = Second Class, 3 = Third Class
| Sex |  Sex| 0 = Male. 1 = Female
| Age |  Age in years | 
| Sibsp| No. of siblings / spouses aboard the Titanic 
| Parch | No. of parents / children aboard the Titanic
| Ticket| Ticket number
| Fare | Passenger fare
| Cabin | Cabin number
| Embarked | Port of Embarked | C = Cherbourg, Q = Queenstown,S = Southampton


**Pclass:** A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

**Age:** Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**Sibsp:** The dataset defines family relations in this way: <br>
 - Sibling = brother sister, stepbrother, stepsister
 - Spouse = husband, wife (mistresses and fiancés were ignored)

**Parch:** The dataset defines family relations in this way:<br>
 - Parent = mother, father
 - Child = daughter, son, stepdaughter, stepson
 - Some children travelled only with a nanny, therefore parch=0 for them.

## Libraries Imported

1. Pandas - Pandas is a Python library used for working with data sets.
            It has the functions for analysing, cleaning, exploring, and manipulating data. <br>
    Why Pandas? - It allows us to analyse big data and make conclusions based on statistical theories.

2. NumPy- Is a Python library used for working with arrays and also has functions for working in domain of linear algebra, fourier transform, and matrices. <br>
    Why NumPy? - It helped us by providing an array object that is up to 50x faster than traditional Python lists.

3. Matplotlib - Is a low level graph plotting library in python that serves as a visualisation tool.

4. Seaborn - Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures. We used it to explore and understand our data.

5. Pickle - It is a library primarily used to serialised and deserialised

6. Missingno - It is a library used for the exploratory visualisation of missing data.  

7. Scikit-Learn - This is a free machine learning library. It features various algorithms like support vector machine, random forests, and k-neighbours. It also supports numerical and scientific libraries like **Numpy and Scipy**.

8. SciPy - SciPy stands for Scientific Python. It is basically a scientific computation library that feeds NumPy. <br>

    
    
   ## Set Up <br> 
   Anaconda (Window) <br>
    1. Downloaded and installed Anaconda Navigator for Windows
    2. Created a new environment for the project using Anaconda Command Prompt
    3. Insatlled 
      - Python pip
      - Python 3.10 
      - Jupyter
    4. Istalled the afforementioned libraries uisng conda, conda-forge and pip.
    5. Created a directory for the project
   
   Visual Studio Code (Windows) <br>
    1. Downloaded and installed VSCode for Windows
    2. Opened VSCode via Anaconda Command Prompt
    3. Created a Jupyter notebbok folder for the project
    4. Selected Project (Python 3.10) as the kernnel
    5. Enabled lintinng and installed Pylint using conda install on the terminal
    6. Installed some extentions from Marketplace 
      - Python
      - Jupyter
      - Kite
      - Code Runner
      - Tabnine Autocomplete AI
      - Indent Rinbow
  
  GitHub <br>
    1. Created a group GitHub account for the project <br>
      [Group 5](https://github.com/pygroup5DataScience/Group5-Python-Assignment/blob/dfb7e578176ae4e65de17f833d2c046f1c8a827b/Python_project.ipynb) <br>
      **Password:** group5@glos.ac.uk <br>
    2. Divided the assignment and shared tasks.<br>
    3. collaborated and worked together. <br>
    
 ## Workflow: <br>
 1. Introduction <br>
 2. Event (from embark to time of sinking ) Timeline
 3.  Exploratory Data Analysis. <br>
  - Surviving rate
  - Pclass
  - Name
  - Sex
  - Age
  - SibSp, Parch
  - Ticket
  - Fare
  - Cabin
  - Embarked
3. Feature Engineering  <br>
  - Imputation on Embarked and Age columns
  - Title extraction
  - Ticket first letters
  - Cabin first letters
  - Encoding sex column
  - Family size
  - One Hot Encoding for all categorical variables
4. Machine Learning
  - Split data into train and test sets
  - Initialize a Random Forest Classifier
  - Hyperparameter Tuning with Grid Search
  - Prediction

