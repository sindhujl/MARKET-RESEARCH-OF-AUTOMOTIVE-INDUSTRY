# impact-of-automobile-features- 
pbi online file: https://app.powerbi.com/view?r=eyJrIjoiZmUzM2VjNDEtNjk3Yi00NzcwLWI1OWUtMTY1ZjljMjZiMjk5IiwidCI6Ijk2M2JlZWEyLTRiYjQtNDI3MS04Nzg5LWVkMWQ0ZWQ3MmFmYSIsImMiOjEwfQ%3D%3D

Questions to ask before analysis. Once, you try to come with questions it will clearly help with your analysis. At time's you will feel like you are stuck so coming with these questions for yourself will clear your thoughts and give's a broader spectre for analysis:
Here are my questions, It might help to kick-start your thought process:
1) what are the important features.
2) How price varies with the features and brands?
3) why high end brands are consistent with the sales?
4) can we compare premium cars to normal cars, if so on what bases?
5) how car features are correlated to each other?

**SCOPE**:
In a rapidly evolving automotive industry, the challenge is clear: how can a car manufacturer optimize pricing and product development to maximize profitability while meeting consumer demand? Through data analysis, we aim to unravel the intricate relationship between car features, market categories, and pricing. Using techniques like regression analysis and market segmentation, our goal is to inform a strategic pricing approach that balances consumer preferences with profitability. 

**DATA AND FINDINGS:**
The initial dataset, included qualitative data various car features data. It had data on the Car Model , Retail price, No of cylinders, Size and Type of the Vehicle
In our outlier detection analysis ,Exploratory data analysis phase, interesting results were found. For example, we found that the most of the outliers which are crossing the threshold limit are due to electric vehicles and high range vehicles, on further analysis we have found that most high-end vehicles calls have high horse power and more number of cylinders. Bugatti, Maybach, Rolls-Royce brands have higher average retail price.

**APPROACH**:
In order to analyze the Automobile data and generate insights out of it, we followed the process that looked at the data using the following visualizations:
Pre processing, Exploratory Data Analysis using Excel, Power Bi and Python
Regression analysis and correlation.
Univariate, bivariate and multivariate analysis with MSRP and MPG
Building Star schema Data model.
Scatter Plot Chart and Top Brands column chart
Tool Tip customization and Grouping visuals.

**Result**: If I had a chance to re-do the project, Although I've done outlier analysis in excel, recommend you to utilize python for data normalization and pre-processing,
still i did it in excel to explore advance excel lookup formulas, stat formulas , pivot tables, pivot charts, visualizations.
and in power bi visuals I'll focus on padding , grouping the visuals, building robust model for the tables to reduce load time.

**Tips for Power Bi:**
If you are incorporating custom background make sure to turn of background in charts, adjust ur padding to make the visuals look pleasing.
Always keep your dimension tables on top and flat tables in bottom for detailed model view, seperate table for date is a best practice.
Create new table and store the key measures.
only create calculated columns in need, always opt for measures as it calculates on a fly and doesn't store data. 

Update: I've done EDA for similar dataset from kaggle, refer if needed
