
# Bike Sales Dashboard Project

This project is a full Excel data analysis and dashboard build based on a bike sales dataset. The work covers data cleaning,
transformation, pivot tables, visualization, and dashboard creation — all done step-by-step in Excel.

## Project Overview
. Goal: Create a complete Excel project including data cleaning, pivot tables, and an interactive dashboard.

. The dataset contains customer demographics and whether they purchased a bike.

. Final product: A dashboard with visuals and filters that users can interact with

## Project Objective

To analyze a bike sales dataset and build a dynamic, interactive Excel dashboard that provides insights into customer demographics and purchasing behavior.

## Tools 

   Microsoft Excel

        Functions: IF, nested IF, VALUE IF FALSE

        Features: Pivot Tables, Pivot Charts, Slicers, Formatting

## Steps Followed
 
1. 🧹 Data Cleaning

    Removed duplicates from the dataset.

    Standardized number formats (e.g., income set to currency).

    Reviewed and confirmed consistency in columns like Education, Occupation, Commute Distance.

    Fixed field naming issues (e.g., “m” and “s” replaced with “married” and “single” incorrectly — corrected to “Marital Status”).

2. 🧮 Data Transformation

    Created a new Age Bracket column using nested IF statements:

        Age < 31 → Adolescent

        Age 31–54 → Middle Age

        Age ≥ 55 → Old

3. 📌 Pivot Tables

Three pivot tables were built to analyze:

    Average Income by Gender and Bike Purchase

    Count of Bike Purchases by Commute Distance

    Bike Purchases by Age Bracket

    Some field labels like "10 miles" were renamed (e.g., “More than 10 miles”) to correct sorting issues in pivot views.

4. 📈 Charts and Visualizations

    Charts were created from pivot tables using Recommended Charts.

    Style elements were added:

        Axis titles (e.g., Income, Gender)

        Chart titles (e.g., Average Income per Purchase, Customer Commute, Age Bracket)

        Decimal places and comma formatting were cleaned for readability.

5. 📊 Dashboard Creation

    Moved visualizations to a new dashboard sheet.

    Removed Excel gridlines for a clean look.

    Created a Dashboard Header using "Merge & Center".

    Aligned charts using Shape Format > Align tools.

6. 🎛️ Interactivity with Slicers

    Added slicers for filtering visuals by:

        Marital Status

        Region

        Education

    Used Report Connections to link slicers to all pivot tables.

    Final dashboard allows filtering by demographics (e.g., Single, Graduate Degree, Europe region) with real-time chart updates.

## Key Insights

    Middle-aged individuals (31–54) are the most likely to buy bikes.

    Higher-income individuals are more likely to purchase.

    Commute distance affects purchase behavior.

    Married people earn more on average than single individuals in this dataset.

📎 Repository Content


