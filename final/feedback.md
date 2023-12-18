# Feedback on your final

**Final Score: 53/60**

The grading rubric for the final can be found in GitHub: https://github.com/paulboal/hds5210-2023/blob/main/final/final-instructions.pdf

**Functional Requirements**
* 5 points - Uses data from at least two different sources: local file, internet, web service, relational database, AWS S3, etc; and formats: CSV, JSON, database, XML, Excel, etc
* 5 points - Data from multiple sources has to be joined together at least twice
* 5 points - Data is aggregated or pivoted at least twice during the program
* 5 points - Some kind of field-level transformation is performed at least 5 times
* 5 points - The program creates 3 or more data visualizations 
* 5 points - The program serves a theoretical purpose described in documentation, that could potentially do something in healthcare or another industry of interest

**Modularity / Style**
* 15 points - The code is broken up into various functions or classes to make testing and reuse easier

**Documentation and Professionalism**
* 15 points - All functions are documented and notebook cells include annotations and explanations.


**(-3) Both of your files were CSV and the requirement for full credit was two different file types.**

**(-2) You merged these two dataframes using only Age and HighBP.  However, there are multiple records for each combination of Age and HighBP.  As a result, you will duplicate your data when the join matches every Age/HighBP combination row with every other matching combination's rows.  The result will be incorrect results for all of your aggregations.**

**(-2) You did not do all of the required field-level transformations.  You used sklearn ColumnTransformer, but that's a specific type of transformation for machine learning.  You were required to do several field level transformations for direct analysis purposes.**

**Overall I thought your project was good.  You covered a lot from data cleansing to machine learning (which wasn't required).  It wasn't always clear where your work was headed and some minor logical failures lead to points off here and there.  Overall, you're demonstrating that you can use Python, though!!**