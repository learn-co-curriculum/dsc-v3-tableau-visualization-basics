# Tableau - Basic Visualizations and the Show Me Pane

## Introduction
Data visualizations are not a “one-size fits all” solution so it is important to select a visualization that works for your data and the story that you want to tell. Tableau can generate a diverse collection of **vizzes** (Tableau's special word for visualizations) that you can customize for your use case. In this lesson, we will discuss **Measures** and **Dimensions** and how you should choose them to build a viz. Then, we discuss the **Show Me pane** and highlight a few of the most essential visualizations - the bar chart, the regional plot, and the time-series plot.

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
1. Measures are continuous data points. They contain the quantitative values that can be measured such as sales, height, and age.
2. Measures can be aggregated. When you add the measure to your workspace Tableau automatically applies a default aggregation, which is usually a sum.
3. If you look just before the name of each measure, you will see a small icon. These icons represent data types and are automatically generated by Tableau.
4. If the data type is not accurate or you just want to customize it, you can do so by hovering over the measure and then clicking the arrow to open the options menu.

#### Dimensions
1. Dimensions are categorical data points. They contain qualitative values like month, state, and date.
2. When added to the workspace, dimensions will impact the level of detail in the view.
3. If you look just before the name of each dimension, you will see a small icon. These icons represent data types and are automatically generated by Tableau and can be modified.

## Show Me Pane
By selecting measures and dimensions and dragging them from the Data Pane to the Row and Column shelves, we trigger the Show Me pane to display which vizzes could work with the measures and dimensions we have chosen. 

Take a look at the clip below. In the beginning, the Show Me pane in the upper right corner of the screen is deactivated (all of the viz icons are semi-transparent). When we drag a dimension (`Sub-Category`) and a measure (`Sales`) and drop them in the Column and Row shelves, the Show Me Pane is activated and the available visualizations appear in full color.

<br>
<div>
    <center>
<table><tr><td>
<video controls src = "https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/show-me-features.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>
<br>

If there is a viz that you would prefer to use and it does not appear to be available, you can hover over the viz and learn what kind of data is needed for that visualization. Then, simply drag the dimensions or measures indicated to the Row and Column shelves to unlock your desired visualization.

<br>
<div>
    <center>
<table><tr><td>
<video controls src = "https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/show-me-features.mov" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>
<br>

## The Marks Card
Tableau has built-in tools to make a simple bar chart more expressive. These tools appear on the __Marks card__, which is shown in the image below. As we describe some basic visualizations and their use cases, we will also indicate how you can use attributes like __Color__, __Size__, __Label__, __Detail__, and __Tooltip__ to enhance the value of visualizations in  Tableau. In future lessons and labs, we will explore the Marks card and its attributes in further detail. 

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-marks-card-1.png" alt="Tableau Marks Card." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

## Basic Vizzes

### Bar Chart
Bar charts are a type of chart that is used to display and compare categorical data. Bar charts consist of bars that are proportional in height or length to the values they represent. The bars can be vertical or horizontal, and the x-axis and y-axis represent the categories being compared and the scale of the data. 

Bar charts are useful for visualizing data that can be grouped into categories or ranges, such as the number of items sold in different categories, the frequency of responses to a survey question, or the distribution of scores on a test.

Bar charts are particularly useful for comparing the values of different categories or groups. For example, a bar chart can be used to compare the sales of different products, the number of visitors to different websites, or the distribution of income among different demographic groups. 

Bar charts can also be used to show changes in data over time, by using a stacked bar chart or a grouped bar chart to show changes in the distribution of data over time or across different categories.

A bar chart that we can build from the SuperStore Sales data set is **Profit by Sub-Category**. In this case, `Profit` is the measure and `Sub-Category` is the dimension. This bar chart provides value by allowing viewers to quickly compare the profitiability of various sub-categories in the data.

In the image below, we have dragged the `Sub-Category` pill to the Columns shelf and the `Profit` pill to the Rows shelf. 

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-1.png" alt="Sub-Category and Profit on the Row and Column Shelves" style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

**Vertical Bar Chart**

One way to improve readability is by creating a vertical bar chart. 

Simply select __Swap Rows and Columns__ icon on the Show Me pane, as shown in the image below.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-2.png" alt="Vertical bar chart." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

You can also use the __Show Me Pane__ and select the vertical bar chart viz.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-2-1.png" alt="Vertical bar chart." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

**Sorted Values**

Since the topic of our visualization related to profits and losses, it is also helpful to viewers if the value of the measures are sorted from ascending and descending order.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-3.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

**Add a Title**

We can also add a title by selecting the tab for the worksheet from the Sheets tab, then double-clicking and typing the new title. This will also change the title above the visualization on the worksheet.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-4-1.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

**Format a Title**
You can format the title by double-clicking the title above the viz. This will open up a pane where you can adjust the font-size, color, alignment, and more.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-5.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

**Adding Color**

Using the Marks card, we can use the __Color attribute__ to apply a diverging orange-blue color palette to indicate whether sales are positive or negative. This is useful for viewers because it provides a clear visual indication of the degree to which a sub-category is profitable or unprofitable.

This can be accomplished by dragging the `Profits` pill from the Data pane to the Marks card and selecting the icon directly to the left of the `Profits` pill, then selecting color. A window will appear where a color pallete can be selected and the values can be customized.

Take a look at the clip below to view a demonstration of this procedure.

<br>
<div>
    <center>
<table><tr><td>
<video controls src ="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-color-1.mov" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

In the first part of the clip, we dragged the `Profits` pill from the Data pane and dropped it onto the Color attribute. This automatically changed our visuzaliation from plain blue to a blue-orange diverging palette. 

In the second part of the the clip, we demonstrate how to further customize the Color attribute by clicking on the Color attribute on the Marks card, and select edit color.  From there, we can change the color palette, or the number of steps (discrete colors) in the palette.

**Color and Accessibility in Data Visualizations**

Accessible colors are important for data visualization because they ensure that everyone can interpret and understand the information being presented.  Inaccessible color combinations can make it difficult or impossible for people with color blindness or other visual impairments to distinguish between different data points or to read the text on the visualization. This can lead to errors in interpretation or a complete lack of understanding of the data being presented.

By choosing colors that provide sufficient contrast and are easily distinguishable, designers can ensure that their visualizations are accessible to a wider range of people. There are many tools and resources available for selecting accessible color palettes, including online color contrast checkers and guidelines from organizations such as the World Wide Web Consortium (W3C). Additionally, designers can choose to use alternative visual cues, such as textures or patterns, to convey information in cases where color alone may not be sufficient.

In future lessons, we will take a closer look at visual best practices. For now, you must remember to avoid color palettes that use green and red, as they can be impossible for people with certain kinds of color blindness to see. Instead, you can use orange and blue.

**Labels**

Labels are useful for highlighting important data points that might otherwise remain unseen unless explicitly annotated. Labels can be added to a viz by using the **Label** attribute on the Marks card.  In our case, labels are useful to indicate the dollar amount of the profits in each sub-category.

**Format Labels**

First, we want to change the **Format** settings to make sure that our labels will be clear and readable.

To get started, select one of the bars in the chart and right-click. Then, select **Format** from the menu.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-7.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

This will open the **Format pane** on the left side of the screen.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-7-1.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

Then, use this procedure to format the numbers to currency.

2. On the upper right corner of the Format pane, select **Feilds > SUM(Profit)**.
3. Then, click the __Pane__ button directly below, Select the icon directly next to the example under **Default > Numbers**. (See item 1 in image below).
4. This will open the **Number Format pane**. Select **Currency (Custom)**. (See item 2 in the image below).
5. Finally, change the number of decimal places to zero. (See item 3 in the image below).

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-7-2.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

With the formatting in place, we can close the Format Pane and start adding labels to the viz.

The next step is to drag the `Profits` pill to the Marks card. Then, select the __More Options__ icon directly to the left of the `Profits` pill on the Marks card. Select __Label__. Now, the proft for each sub-category is displayed on the visualization, in the formatting that we specified. 

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-8.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

With the labels applied, our chart looks like this:

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-bar-8-1.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

Bar charts are a versatile and widely used tool for visualizing and comparing categorical data, and are particularly useful for identifying patterns and trends in the data. They can be made even more useful with helpful enhancements like color and labels.

### Regional Plot
Regional plots are useful because they allow us to visualize and analyze data in a geographical context. By plotting data on a map, we can easily identify patterns, trends, and relationships that may not be apparent in a table or a chart. 

Regional plots can also help us to understand the distribution of our data across different regions, and to identify regional differences or similarities in our data. This can be particularly useful in fields such as business, marketing, and public health, where regional variations can have significant implications for decision-making. 

Additionally, regional plots can be used to create visually compelling and interactive data visualizations that engage audiences and help them to explore and understand complex data sets from a location-based perspective. Regional plots are a powerful tool for exploring and analyzing data in a geographic context and can provide valuable insights into the relationships between data and location.

To create a regional plot in Tableau, there are a few things you need before you begin. 

1. **Geospatial Data**: Make sure your data has a region column or a geographic identifier column that you can use to plot your data on a map. In our case, we have `Postal-Code`, `City`, `County`, `Region`, and `State/Province`. 

2. **Measures**: The regional plot will visualize the quantity of a particular measure/measures in the data set. In our case, we have columns such as `Sales`, `Orders`, and `Profit` that we could quantify over a given location.

For example, we can visualize Orders by State/Province with a regional map with the following procedure.

1. First, we create a new worksheet. Rename it "Orders by State/Province". 

2. Then, we drag `State/Province` to the Columns shelf and `Orders` to the Rows shelf.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-map-1.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

3. Now, we have a bar chart, that looks like this. We can turn it into a regional map using the Show Me Pane and selecting the map visualization. Make sure you select the maps visualization, and not the symbol maps visualization for this example. 

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-map-2.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

4. You will notice that a few key things automatically change when we change the viz to the regional map. `Longitude` and `Latitude` have replaced `Orders` and `State/Province` in the Row and Column shelves. `Orders` and `State/Province` have moved to the Marks card, so that the quantity of orders can be indicated by the color shade, and so that the state/province can be indicated in the tooltip when we hover over a state. 

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-map-3.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

6. To make the map more descriptive, you can add `CNT(Orders)` to the Marks card and click More Options to apply a label indicating the number of orders per state.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-map-4.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

7. This looks pretty good, however one of the labels in cramped and difficult to read.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-map-6.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

We can fix this selecting the label:

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-map-7.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

Then dragging it over slightly:

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-map-8.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

Now, our regional map looks like this.

<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/5_data_viz/tableau-viz-map-9.png" alt="Sorted Values." style="width: 700px;"/>
</td></tr></table>
    </center>
    </div>

## Summary
In this lesson, we discussed the basic elements needed to create data visualizations in Tableau. Then, we created two of the most common visualizations, the bar chart and the regional map.

First, we reviewed dimensions and measures and explained how dimensions represent categorical data and that measures represent continuous data. Then, we described how you can use the Show Me pane to determine what kinds of dimensions and measures you should add to the Row and Column shelves to create your desired visualizations.

We created a bar chart to represent Profits by Sub-Category, and demonstrated how to use the Marks card to add attributes to your data visualizations, like Color and Labels. Then, we showed you how to use geospatial data to generate a map to visualize orders by state/province.

In the lab that follows this lesson, you will use these procedures to build more visualizations with Tableau.
