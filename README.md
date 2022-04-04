# Kickstarting with Excel

## Overview of Project
An analysis of Kickstarter campaigns was performed on data ranging from years 2009-2017 for campaigns of various budgets, countries of origin, and categories of project. 
### Purpose
This analysis was intended to assist client Louise in forecasting what her priorities should be in planning a successful Kickstarter campaign. This was accomplished by comparing the success or failure of other Kickstarter campaigns to their fundraising goals and launch dates so that Louise can properly plan for the scope and launch of her play's campaign.
## Analysis and Challenges
I began my analysis by applying visual formatting to the data by color-coding the "outcomes" column through conditional formatting. I then further determined *how* successful a campaign was by introducing a new column, "Percentage Funded," in which I calculated to what extent a campaign was funded compared to its original goal. Visual formatting was also applied to this column via a color scale from red to blue. Next, a new column was introduced with the intention of calculating the average donation per campaign backer, calculated by dividing the total pledged (column E) by the number of backers (column L). I noticed that this calculation provided errors for campaigns that had no backers, so I applied the "IFERROR" formula to compensate and clean the data. 

Because Louise indicated she would be campaigning for funding for a play, I decided to seperate the "Category/Subcategory column into two seperate columns, "Parent Category" and "Subcategory." This allowed me to perform a more in-depth analysis utilizing PivotTables, indicating the number of outcomes specifically for the Parent Category "theater" as shown in the screenshot below.

![Parent Category Outcome - Theater](Screenshots/ParentCategoryOutcomesScreenshot.png)

I further analyzed the data by creating a PivotTable utilizing the Subcategory column, showing only the outcomes for the subcategories of theater campaigns. This allowed me to show Louise exactly how many play campaigns has succeeded, failed, or been canceled.

![Subcategory Outcome - Theater](Screenshots/SubcategoryOutcomesScreenshot.png)


### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

### Outcomes Based on Launch Date

![Theatre Outcomes vs. Launch](Resources/Theater_Outcomes_vs_Launch.png)

#### First Conclusion

#### Second Conclusion
- What are two conclusions you can draw about the Outcomes based on Launch Date?

### Outcomes Based on Goals

![Outcomes vs. Goals](Resources/Outcomes_vs_Goals.png)

#### First Conclusion

#### Second Conclusion
- What can you conclude about the Outcomes based on Goals?

### Limitations of Dataset
- What are some limitations of this dataset?

### Further Recommendations
- What are some other possible tables and/or graphs that we could create?

