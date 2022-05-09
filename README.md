# Data-analysis
Practice Data analysis with Kaggle


# Choosing Plot Types and Custom Styles

![image](https://user-images.githubusercontent.com/68217111/162891220-b30dddd2-4f2e-445e-b870-03b75b3c6cd9.png)

Since it's not always easy to decide how to best tell the story behind your data, we've broken the chart types into three broad categories to help with this.


## 1. Trends - A trend is defined as a pattern of change

### sns.lineplot


Line charts are best to show trends over a period of time, and multiple lines can be used to show trends in more than one group.

![image](https://user-images.githubusercontent.com/68217111/162891787-e9443cd4-0047-4f4c-84c0-3db0465a7096.png)
  

## 2. Relationship - There are many different chart types that you can use to understand relationships between variables in your data.

### sns.barplot


Bar charts are useful for comparing quantities corresponding to different groups.

![image](https://user-images.githubusercontent.com/68217111/162891841-2f14354b-9980-42ef-95dc-609d67747f87.png)


### sns.heatmap


Heatmaps can be used to find color-coded patterns in tables of numbers.

![image](https://user-images.githubusercontent.com/68217111/162891863-527eb3d2-5593-48cb-8a68-e18df40aff11.png)


### sns.scatterplot


Scatter plots show the relationship between two continuous variables; if color-coded, we can also show the relationship with a third categorical variable.

![image](https://user-images.githubusercontent.com/68217111/162892045-c4f77bcc-147a-41b7-9509-2cbc3d29a963.png)


### sns.regplot


Including a regression line in the scatter plot makes it easier to see any linear relationship between two variables.

![image](https://user-images.githubusercontent.com/68217111/162892419-067a439f-801d-4a60-ae5b-9321053f3404.png)



### sns.lmplot


This command is useful for drawing multiple regression lines, if the scatter plot contains multiple, color-coded groups.

![image](https://user-images.githubusercontent.com/68217111/162892340-0280b8e4-1af8-4d17-afca-f672a08ad211.png)


### sns.swarmplot



Categorical scatter plots show the relationship between a continuous variable and a categorical variable.

![image](https://user-images.githubusercontent.com/68217111/162892459-a73c51a7-c234-423a-9ace-4a1ed5db1980.png)


## 3. Distribution - We visualize distributions to show the possible values that we can expect to see in a variable, along with how likely they are.


### sns.distplot


Histograms show the distribution of a single numerical variable.


![image](https://user-images.githubusercontent.com/68217111/162892959-0b049c41-ef38-4d34-838e-a3f001f2945b.png)


### sns.kdeplot


KDE plots (or 2D KDE plots) show an estimated, smooth distribution of a single numerical variable (or two numerical variables).


![image](https://user-images.githubusercontent.com/68217111/162893072-d968ff2d-2d9f-49e0-8a1c-cbc71365d989.png)


### sns.jointplot
This command is useful for simultaneously displaying a 2D KDE plot with the corresponding KDE plots for each individual variable.


![image](https://user-images.githubusercontent.com/68217111/162893150-ecdf4e16-862d-4397-8c93-a2f75e499179.png)


