# Applied-Statistics-Project---Health-Insurance
  This project used Hypothesis Testing and Visualization to leverage customer's health information like smoking habits, bmi, age, and gender for checking statistical evidence to     make valuable decisions of insurance business like charges for health insurance.

EDA: 

  Shape & type of Data.
  Checking the presence of missing values.
  5 point summary of numerical attributes.
  Distribution of ‘bmi’, ‘age’ and ‘charges’ columns.
  Measure of skewness of ‘bmi’, ‘age’ and ‘charges’ columns.
  Checking the presence of outliers in ‘bmi’, ‘age’ and ‘charges columns.
  Distribution of categorical columns.
  Pair plot that includes all the columns of the data frame.

Hypothesis Testing:

  Do charges of people who smoke differ significantly from the people who don't?
  Does bmi of males differ significantly from that of females?
  Is the proportion of smokers significantly different in different genders?
  Is the distribution of bmi across women with no children, one child and two children, the same?
  
Statistical Analysis used:
 
  Categorical vs Categorical: chi-square. 
  Categorical vs Continuous: T-test (two-way T-test in our case) or Z-test(2-sample Z-test). 
  Checking statistical significance between more than two independent groups : one-way ANOVA. 
  Test for proportions based on normal (Z) test.
  
Post-Mortem:

  EDA work is thorough with supporting inferences.  
  Providing observations by using Visual plots is attempted along with concluding results using Statistical hypothesis testing techniques. 

Future improvements:

  Pair plot analysis: Inferences from Pair plot analysis are missing. e.g. - There's an interesting pattern between 'age' and 'charges. Could be because for the same ailment,     older people are charged more than the younger ones - The only obvious correlation of 'charges' is with 'smoker' - Looks like smokers claimed more money than non-smokers.
