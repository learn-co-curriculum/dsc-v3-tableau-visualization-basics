# Tableau - Useful Visualizations and the Show Me Pane

## Introduction
Data visualizations are not a “one-size fits all” solution so it is important to select a visualization that works for your data and the story that you want to tell. Tableau can generate a diverse collection of **vizzes** (Tableau's special word for visualizations) that you can customize for your use case. In this lesson, we will discuss **Measures** and **Dimensions** and how you should choose them to build a viz. Then, we discuss the Show Me pane and highlight a few of the most essential visualizations - the bar chart, the regional plot, and the time-series plot.

## Objectives
You will be able to:
* Identify the dimensions and measures needed to generate a viz
* Apply a visualization to data using the Show Me Pane
* Describe bar charts, regional plots, and time-series plots.

## Measures and Dimensions
If we return to the Data Pane, you might notice that the names of the columns have two distinct colors, <font color='green'>**green**</font> and <font color='blue'>**blue**</font>. These colors help to distinguish between **Measures** and **Dimensions**.

In Tableau, dimensions and measures are two essential concepts that help users to create interactive and informative data visualizations. Dimensions are categorical variables that provide context to the data, such as time, location, or category. Measures, on the other hand, are quantitative variables that can be measured and aggregated, such as sales, profit, or quantity. 

By dragging and dropping dimensions and measures onto the Rows and Columns shelves, users can create various types of charts, such as bar charts, line charts, scatterplots, and more. 

Additionally, Tableau allows users to manipulate dimensions and measures with various calculations and functions, such as filtering, grouping, sorting, and aggregating, to gain more insights into their data. 

Dimensions and measures are the building blocks of Tableau visualizations, and understanding their roles and functionalities is crucial for creating effective and engaging dashboards.

Let's review some of the most important things to remember about dimensions and measures.

#### Measures
1. Measures are continuous data points. They contain the quantitative values that can be measured such as sales, height, and age. <br>
2. Measures can be aggregated. When you add the measure to your workspace Tableau automatically applies a default aggregation, which is usually a sum.
3. If you look just before the name of each measure, you will see a small icon. These icons represent data types and are automatically generated by Tableau.
4. If the data type is not accurate or you just want to customize it, you can do so by hovering over the measure and then clicking the arrow to open the options menu.

<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src = "https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/barchart.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>

#### Dimensions
1. Dimensions are categorical data points. They contain qualitative values like month, state, and date.
2. When added to the workspace, dimensions will impact the level of detail in the view.
3. If you look just before the name of each dimension, you will see a small icon. These icons represent data types and are automatically generated by Tableau and can be modified.

<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src = "https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/barchart.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>

## Show Me Pane
By selecting measures and dimensions and dragging them from the Data Pane to the Row and Column shelves, we trigger the Show Me pane to display which vizzes could work with the measures and dimensions we have chosen. 

Take a look at the clip below. In the beginning, the Show Me pane in the upper right corner of the screen is deactivated (all of the viz icons are semi-transparent). When we drag a dimension (Sub-Category) and a measure (Sales) and drop them in the Column and Row shelves, the Show Me Pane is activated and the available visualizations appear in full color.
<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src = "https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/barchart.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>

If there is a viz that you would prefer to use and it does not appear to be available, you can hover over the viz and learn what kind of data is needed for that visualization. Then, drag the dimensions or measures indicated to the Row and Column shelves to unlock your desired visualization.

<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src = "https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/barchart.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>

## Bar Chart
Bar charts are a type of chart that is used to display and compare categorical data. Bar charts consist of bars that are proportional in height or length to the values they represent. The bars can be vertical or horizontal, and the x-axis and y-axis represent the categories being compared and the scale of the data. Bar charts are useful for visualizing data that can be grouped into categories or ranges, such as the number of items sold in different categories, the frequency of responses to a survey question, or the distribution of scores on a test.
Bar charts are particularly useful for comparing the values of different categories or groups. For example, a bar chart can be used to compare the sales of different products, the number of visitors to different websites, or the distribution of income among different demographic groups. Bar charts can also be used to show changes in data over time, by using a stacked bar chart or a grouped bar chart to show changes in the distribution of data over time or across different categories.

<p>
An example from the SuperStore Sales data set is <b>Profit (measure) by Sub-Category (dimension)</b>.
<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/bar-chart-1.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>
    

> One way to improve readability is by creating a vertical bar chart. Simply select the vertical bar chart icon on the Show Me pane.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/vertical-bar.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>
    
    
> Tableau has built-in tools to make a simple bar chart more expressive. For example, you can add a diverging orange-blue color palette to indicate whether sales are positive or negative by using the Color on the Marks card. 
<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/Change-Color.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div></li>


> We can also change the title.
<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/change-title.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>
    
>You can add some information to the ends of the bars with the use of the <b>Label card</b> by using the <b>currency</b> formatting option.
<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/add-currency.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

Overall, bar charts are a versatile and widely used tool for visualizing and comparing categorical data, and are particularly useful for identifying patterns and trends in the data.

## Regional Plot
Regional plots are useful because they allow us to visualize and analyze data in a geographical context. By plotting data on a map, we can easily identify patterns, trends, and relationships that may not be apparent in a table or a chart. 

Regional plots can also help us to understand the distribution of our data across different regions, and to identify regional differences or similarities in our data. This can be particularly useful in fields such as business, marketing, and public health, where regional variations can have significant implications for decision-making. 

Additionally, regional plots can be used to create visually compelling and interactive data visualizations that engage audiences and help them to explore and understand complex data sets. Regional plots are a powerful tool for exploring and analyzing data in a geographic context and can provide valuable insights into the relationships between data and location.

To create a regional plot in Tableau, follow these steps:
Prepare your data: Make sure your data has a region column or a geographic identifier column that you can use to plot your data on a map.
Add a map to the worksheet: Drag a map object from the Show Me panel onto the worksheet. Tableau will automatically recognize your region column and plot your data on the map.
Choose your map style: You can choose from a variety of map styles by selecting Map > Map Layers and selecting the style you prefer.
Customize your map: You can customize your map by adding additional layers, changing the colors of your data points, and adjusting the size and opacity of your map elements.
Add additional dimensions and measures: You can add additional dimensions and measures to your regional plot by dragging them onto the Rows and Columns shelves, or by using them to create filters or groups.

> An example from the SuperStore Sales dataset is <b>`Sales` (measure)</b> by <b>Postal `Code` (measure)</b>.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/profit-by-sales.png" alt="This is the alt-text for the image." style="width:700px;"/>
</td></tr></table>
    </center>
</div>


> We can make regional plots more informative by adding dimensions and measures to mark cards and assigning attributes like <b>Color</b>, and <b>Size</b>.

<br>
<br>
<div>
    <center>
<table><tr><td>
<video controls src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/add-colors-size.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

## Time-Series Plot
Time series plots are a type of line plot because they use a continuous line to represent the trend of a variable over time. In a time series plot, the x-axis represents time, and the y-axis represents the value of the variable being measured. The data points are connected by a line, which allows us to see the trend of the variable over time, and to identify patterns and changes in the trend. Like other line plots, time series plots are useful for visualizing continuous data, such as temperature, stock prices, or sales data, and for identifying trends and patterns in the data. Time series plots can also be used to identify outliers or anomalies in the data, and to compare the trends of different variables over time. 

> An example from the SuperStore Sales dataset is <b>Sales (measure)</b> and <b>Order Date (date)</b>.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/sales-by-year.png" alt="This is the alt-text for the image." style="width:700px;"/>
</td></tr></table>
    </center>
</div>
</li>
   
> When we first populate the Row and Column shelves with the Sales and Order Date, our view displays a line plot with Sales by Year. If we hover near the title for X-Axis, a minus sign and or plus sign will appear. Clicking the plus sign allows us to change the time delta (range of times) in the view to quarterly instead of yearly.
</b>.
<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/sales-by-quarter.png" alt="This is the alt-text for the image." style="width:700px;"/>
</td></tr></table>
    </center>
</div>
</li>

> The period of the graph can be adjusted by clicking on the measure in the Columns shelf and choosing the period from the drop-down.

## Accessible Visualizations
Accessible colors are important for data visualization because they ensure that everyone, including people with visual impairments, can interpret and understand the information being presented. Inaccessible color combinations can make it difficult or impossible for people with color blindness or other visual impairments to distinguish between different data points or to read the text on the visualization. This can lead to errors in interpretation or a complete lack of understanding of the data being presented.

Using accessible colors is essential for creating inclusive and effective data visualizations. By choosing colors that provide sufficient contrast and are easily distinguishable, designers can ensure that their visualizations are accessible to a wider range of people. There are many tools and resources available for selecting accessible color palettes, including online color contrast checkers and guidelines from organizations such as the World Wide Web Consortium (W3C). Additionally, designers can choose to use alternative visual cues, such as textures or patterns, to convey information in cases where color alone may not be sufficient. Overall, accessible colors are an important aspect of designing effective and inclusive data visualizations that can be understood and interpreted by everyone.

In future lessons, we will take a closer look at visual best practices. For now, you must remember to avoid color palettes that use green and red, as they can be impossible for people with certain kinds of color blindness to see. Instead, you can use orange and blue.

<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/sales-by-quarter.png" alt="This is the alt-text for the image." style="width:700px;"/>
</td></tr></table>
    </center>
</div>


## Summary
In this lab, we identified the measures and dimensions necessary to create bar charts, scatter plots, and line plots. We also discussed how to use the Show Me Pane to build visualizations from our measures and dimensions. In the upcoming lab, you will have an opportunity to build a visualization from start to finish using the SuperStore Sales dataset. During that lab, you will need the skills we practiced here to select the appropriate visualization for your data and use case.
