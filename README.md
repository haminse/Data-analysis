# Kaggle-Data-analysis
Practice Data analysis with Kaggle


# Choosing Plot Types and Custom Styles

![image](https://user-images.githubusercontent.com/68217111/162891220-b30dddd2-4f2e-445e-b870-03b75b3c6cd9.png)
Since it's not always easy to decide how to best tell the story behind your data, we've broken the chart types into three broad categories to help with this.


## 1. Trends - - A trend is defined as a pattern of change

- sns.lineplot
Line charts are best to show trends over a period of time, and multiple lines can be used to show trends in more than one group.
  

## 2. Relationship - There are many different chart types that you can use to understand relationships between variables in your data.

sns.barplot - Bar charts are useful for comparing quantities corresponding to different groups.
sns.heatmap - Heatmaps can be used to find color-coded patterns in tables of numbers.
sns.scatterplot - Scatter plots show the relationship between two continuous variables; if color-coded, we can also show the relationship with a third categorical variable.
sns.regplot - Including a regression line in the scatter plot makes it easier to see any linear relationship between two variables.
sns.lmplot - This command is useful for drawing multiple regression lines, if the scatter plot contains multiple, color-coded groups.
sns.swarmplot - Categorical scatter plots show the relationship between a continuous variable and a categorical variable.

