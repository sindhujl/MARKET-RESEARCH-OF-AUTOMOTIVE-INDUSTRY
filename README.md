# impact-of-automobile-features-
questions to ask before analysis. Once, you try to come with questions it will clearly help with your analysis. At time's you will feel like you are stuck so coming with these questions for yourself will clear your thoughts and give's a broader spectre for analysis:
Here are my questions, It might help to kick-start your thought process:
1) what are the important features.
2) How price varies with the features and brands?
3) why high end brands are consistent with the sales?
4) can we compare premium cars to normal cars, if so on what bases?
5) how car features are correlated to each other?

Please refer the sheet I've utilized pivot tables, conditional formatting, boxplots for outliers and statistical methods in excel.

Key components in the power bi report, I'm highlighting only which i think made impact to my report:
1) use of custom tooltip, helps use to visualize multiple features
2) Quick Insights always provide the detailed summary of the report, so utilized that.
3) KPI and slicers
4) scatter plot for bi variate and multi variate analysis.
5) Time intelligence DAX Functions, cummulative totals.
6) Data model

Result: If I had a chance to re-do the project, Although I've done outlier analysis in excel, recommend you to utilize python for data normalization and pre-processing,
still i did it in excel to explore advance excel lookup formulas, stat formulas , pivot tables, pivot charts, visualizations.
and in power bi visuals I'll focus on padding , grouping the visuals, building robust model for the tables to reduce load time.

Tips for power bi:
If you are incorporating custom background make sure to turn of background in charts, adjust ur padding to make the visuals look pleasing.
Always keep your dimension tables on top and flat tables in bottom for detailed model view, seperate table for date is a best practice.
Create new table and store the key measures.
only create calculated columns in need, always opt for measures as it calculates on a fly and doesn't store data. 
