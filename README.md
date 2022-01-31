# Tableau for Data Analytics

## Description

Tableau for data analytics. Tableau is a drag-and-drop software and a novel approach to BI. The course has a spiral structure.

## Course structure

<details>
<summary>Course Structure</summary>

1. Get Started
   1. Course Overview
   2. Installation
   3. Exercise
2. Tableau Basics: Bar Chart
   1. Business Challenge
   2. Connecting Tableau to Data
   3. Navigating Tableau
   4. Creating **calculated fields**
   5. Adding colors
   6. Adding labels and formatting
   7. Exporting worksheet
   8. Get the Viz
3. Time Series, Aggregation and Filters
   1. Intro
   2. Working with Data Extracts in Tableau
   3. Working with Time Series
   4. Understanding Aggregation, Granularity, and Level of Detail
   5. Creating an area Chart & Learning about Highlighting
   6. Adding a Filter and Quick Filter
4. Maps, Scatterplots, and Dashboards
   1. Intro
   2. Joining Data
   3. Creating a Map, Working with Hierarchies
   4. Creating a Scatter Plot, Applying Filters to Multiple Worksheets
   5. Create Dashboard
   6. Add an Interactive Action - Filter
   7. Add an Interactive Action - Highlighting
5. Joining and Blending Data, Dual Axis Charts
   1. Intro
   2. Joins
   3. Joins with Dups
   4. Joining on Multiple Fields
   5. Data Blending in Tableau
   6. Joining Data vs Blending Data in Tableau
   7. Dual Axis Chart
   8. Creating Calculated Fields in a Blend
   9. Recap
6.  Table Calculations: Advanced Dashboards, Storytelling
    1.  Intro
    2.  Downloading the Dataset and Connecting Tableau
    3.  Mapping: How to Set Geographical Roles
    4.  Creating Table Calculations For Gender
    5.  Creating Bind and Distributions for Age
    6.  Leveraging the power of Parameters
    7.  How to create a Tree map chart
    8.  Creating a customer segmentation dashboard
    9.  Advanced dashboard interactivity and coloring
    10. Analyzing the Customer Segmentation Dashboard
    11. Creating a Storyline
7.  Advanced Data Preparation
    1.  Intro
    2.  What Format you Data Should Be in
    3.  Data Interpreter
    4.  Pivot
    5.  Splitting a Column into Multiple Columns
    6.  Metadata Grid
    7.  Fixing Geographical Data Errors
8.  What's New in Tableau 10
    1.  Section intro
    2.  Challenge: Startup Expansion Analytics
    3.  **Custom Territories** via Groups
    4.  Custom Territories via Geographic Roles
    5.  Adding highlighter
    6.  **Clustering** in Tableau 10
    7.  **Cross-database Joins**
    8.  Modeling with Clusters
    9.  Saving your clusters
    10. New Design Features
    11. Mobile Features
    12. Recap
9.  Conclusion

</details>

## Tableau Basics

[Download datasets](https://www.artofvisualization.com/pages/tableau). **Challenge**: Identify the top three employees in each region. Employees are measured against total sales.

In the Data tab we see **Dimensions** and **Measures**. These are different roles any data element can take.

- Dimensions include categorical (qualitative) data. These are independent variables; highlighted blue. 
- Measures include numerical values. These are dependent variables; highlighted green. 

Right click on Measures and create a calculated field. 

Presentation (**Color**) and ease of understanding (**Labels and Formatting**) are very important to effectively communicate with our visualization. 

We can format Label over the Mark menu or by right clicking on the label (or axis). 

## Time Series, Aggregation and Filters

When dealing with the time axis (in Columns) we can aggregate by year as a category (Dimensions) or as a numerical value (Measures). Tableau highlights the field differently depending on the type. 

Tableau aggregates measures at the level of granularity of your worksheet. The level of granularity is set by: 

- Columns
- Color
- Detail 
- Shapes (in Shape Plot)

Filters are an option but Measures as filters are usually the better choice. 

## Maps, Scatterplots, and Dashboards

**Update**: When dragging different sheets to our data source Tableau creates a Relationship (previously a Join). Now there is a logic layer for tables. By double clicking the sheet we can go to the physical layer and join or union tables in the sheets. 

Tableau aggregates by default. We have to options to see more granular data: 

- Go to `Analyis > Aggregate Measures`
- Change the Columns, Color, Detail, or Shape int he worksheet

There are two types of action for the user to interact with a dashboard. The most basic ones are: 

- Filtering 
- Highlighting

## Joining, Blending and Relationships

Continue here! 
