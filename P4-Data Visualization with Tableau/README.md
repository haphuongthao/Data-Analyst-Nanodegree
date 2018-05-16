# Data Story Telling with Tableau
*Create a data visualization using Tableau that tells a story or highlights trends or patterns in a data set. This work should be a reflection of the theory and practice of data visualization, such as visual encodings, design principles, and effective communication.*

### Summary
Given the Titanic dataset, containing demographic and passenger information on board the Titanic, the ship which struck an iceberg on its maiden voyage and sank in 1912, this project aims to use Tableau visualization in order to figure out the pattern between passengers who survived and who died after the tragedy. The dataset provides a set of variables relating to each passenger such as gender, age, fare, number of family members… here I use a number of visualizations to investigate any potential insight to explore the data.

### Design
Approaching the dataset, I initially concentrated on visualizing the basic information on the number of passengers onboard which is divided by gender, by class of society and embarked locations. 
Ticket price and a number of the family member including parents, sibling, children are also indicated through histograms.
In compliance with the law of the sea, woman and children boarded the lifeboats first; only when there were no children or children nearby were men permitted to boats. Digging deeper into the survival likelihood of the passengers, I would like to deliver the message that female, children and upper-class group has a better chance of being rescued after this calamity. I displayed the fraction between death-survival of each segment with pie charts and bar charts.

**Pre-feedback visualization:**
https://public.tableau.com/profile/thao1267#!/vizhome/Titanic_519/Titanic-Story


### Feedback
**Reader 1**
"1st page: I think the title header with stats on the side is a great opener, I really like it. As for the plots, I think more consistency in chart types and color palette would perhaps be easier to understand (like 2 histograms side by side, one per gender, or a side by side bar chart by cutting the age variable into categories; the by Port chart does not show gender information and it has a different color palette).
2nd page: double-check the Family Size charts tooltips: they report 0.1122% (!?) everywhere.
3rd page: love the header stats here too!"

**Reader 2 (Udacity Reviewer)**
“Please use a filter in any one of the dashboards. They are the most powerful Tableau tool.”

**After-feedback visualization:**
https://public.tableau.com/profile/thao1267#!/vizhome/Titanic-feedback/Titanic-Story
* Redesigned the consistency in chart and color palette.
* Provided port chart with gender information.
* Cut the age variable into smaller categories.
* Checked the "aggregate analysis" and categorize the family size.
* Added filters on sex and social class to each dashboard.

### Resources
* Prepare for this project with: [Data Visualization in Tableau](https://www.udacity.com/course/data-visualization-in-tableau--ud1006)
* Install Tableau Public [Here](https://public.tableau.com/s/)


